# AgriAxis — ERP + E-Commerce Agricole

> Système de gestion intégré pour les entreprises horticoles et maraîchères.  
> Couvre la gestion des cultures, du phytosanitaire, des RH, de la comptabilité, des stocks, du transport, du contrôle qualité et d'un e-commerce complet.

---

## Architecture — 1 dépôts regrouppant

| Dépôt | Stack | Rôle |
|---|---|---|
| `erp-backend` | Node.js + Apollo Server (GraphQL) + Prisma + TypeScript | API unique — source de vérité |
| `erp-frontend` | React 19 + Vite + Tailwind + Apollo Client + Zustand | ERP interne + portails B2B + espace contrôleur |
| `ecommerce-frontend` | Next.js 15 + React 19 + Tailwind + Apollo Client | Boutique publique SEO + tunnel de commande |
| `mobile-app` | React Native (Expo) + TypeScript + Apollo Client | Terrain — scan lots, feuilles d'activité, notifications |

Communication : **GraphQL HTTP + WebSocket Subscriptions**

---

## Stack technique

| Couche | Technologie |
|---|---|
| Backend | Node.js + Apollo Server + TypeScript + Prisma |
| Base de données | PostgreSQL 16 ×2 (ERP + E-commerce) + Redis |
| Stockage fichiers | MinIO (S3-compatible, auto-hébergé) |
| Sécurité | JWT RS256 + RBAC/ABAC + AES-256-GCM (double couche) + Argon2 |
| Validation | Zod (partagé frontend/backend) + sanitize-html |
| Paiement | Stripe (3DS, webhooks) |
| Emails | Resend |
| Infra | Docker Desktop + Docker Compose |

---

## Prérequis

- **Docker Desktop** (Windows/macOS/Linux) avec au moins 4 Go de RAM alloués
- **Node.js** ≥ 20 (pour les scripts hors Docker)
- **Expo CLI** (`npm install -g expo-cli`) — uniquement pour `mobile-app`

---

## Installation et démarrage local

### 1. Cloner les dépôts

```bash
git clone 
```

### 2. Variables d'environnement

Dans chaque dépôt, copier `.env.example` en `.env` et remplir les valeurs :

```bash
cp .env.example .env
```

> ⚠️ Ne jamais versionner les fichiers `.env` — ils sont dans `.gitignore`.

### 3. Démarrer la stack

Depuis le dépôt `erp-backend` (qui contient le `docker-compose.yml` racine) :

```bash
docker-compose up -d
```

Cela démarre automatiquement :
- `postgres-erp` (port 5432)
- `postgres-ecommerce` (port 5433)
- `redis` (port 6379)
- `minio` (port 9000, console 9001)
- `erp-backend` (port 4000 — GraphQL endpoint)
- `erp-frontend` (port 3000)
- `ecommerce-frontend` (port 3001)

### 4. Appliquer les migrations

```bash
cd erp-backend
npx prisma migrate dev
```

### 5. Application mobile

```bash
cd mobile-app
npm install
npx expo start
```

Scanner le QR code avec Expo Go (iOS/Android) ou lancer sur émulateur.

---

## Structure du backend

```
erp-backend/src/
  auth/           JWT, RBAC/ABAC, permissions
  employe/        Planning, signalements, messagerie (Sprints 2-6)
  management/     Groupes, équipes, sites (Sprints 7-9)
  culture/        Production, catalogue végétal (Sprint 10)
  phyto/          Phytosanitaire, registre (Sprint 11)
  maintenance/    Machines, ordres de travail (Sprint 12)
  entreprise/     RH, syndical, comptabilité, recrutement (Sprints 13-16)
  logistique/     Transport, stocks, qualité (Sprints 17-19)
  commerce/       Vente, informatique, dirigeant (Sprints 20-22)
  admin/          Contrôleur administratif externe (Sprint 23)
  ecommerce/      Particulier, B2B, grossiste (Sprints 24-27)
```

---

## Endpoints

| Service | URL locale | Description |
|---|---|---|
| GraphQL API | http://localhost:4000/graphql | Apollo Sandbox (dev) |
| ERP Frontend | http://localhost:3000 | Interface ERP |
| E-commerce | http://localhost:3001 | Boutique publique |
| MinIO Console | http://localhost:9001 | Gestion fichiers |

---

## Base de données

- **205 tables** organisées en 13 blocs fonctionnels
- Schéma ERD complet : `/docs/schema.plantuml`
- Migrations Prisma : `/prisma/migrations/`

```bash
# Générer le client Prisma après une modification du schéma
npx prisma generate

# Créer une nouvelle migration
npx prisma migrate dev --name nom_de_la_migration

# Visualiser la BDD
npx prisma studio
```

---

## Tests

```bash
# Tests unitaires et intégration
cd erp-backend
npm run test

# Avec couverture
npm run test:coverage

# Tests E2E (nécessite Docker)
npm run test:e2e
```

---

## Sécurité — points clés

- Les **données personnelles** sont chiffrées AES-256-GCM en double couche avant stockage
- Les **mots de passe** sont hashés Argon2 — jamais stockés en clair
- Les **tokens Stripe** ne sont jamais loggués
- L'**introspection GraphQL** est désactivée en production (`GRAPHQL_INTROSPECTION=false`)
- Les **secrets** ne sont jamais dans le code — uniquement dans `.env`

---

## Documentation

- **Cahier des charges complet** : `/docs/cahierCharges/`
- **GraphQL Schema** : Apollo Sandbox sur http://localhost:4000/graphql (dev)
- **Documentation TypeDoc** : `npm run docs` → `/docs/api/`

---

## Planification — 27 sprints

| Phase | Sprints | Contenu |
|---|---|---|
| Fondations | 1-6 | Socle technique, employé polyvalent, RH base, terrain, signalements, messagerie |
| Management & production | 7-12 | Groupes, équipes, sites, culture, phyto, maintenance |
| Fonctions support | 13-23 | RH avancé, CRM, comptabilité, recrutement, transport, stocks, qualité, caisse, IT, dirigeant, contrôleur |
| E-commerce & portails | 24-27 | Particulier, détaillant, semi-grossiste, grossiste |

---

## Licence

Projet privé — tous droits réservés.
