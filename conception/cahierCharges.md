Cahier des Charges
ERP + E-Commerce Agricole — AgriAxis

──────────────────────────────────────────
INTRODUCTION
──────────────────────────────────────────
  1. Contexte et origine du projet  
  2. Objectifs généraux
  3. Périmètre fonctionnel
  4. Contraintes et principes directeurs
     4.1 Contraintes techniques
     4.2 Contraintes réglementaires (RGPD, PCGA, phytosanitaire)
     4.3 Principes de développement (DRY, RBAC/ABAC, sécurité)

──────────────────────────────────────────
PARTIE I — ACTEURS ET BESOINS FONCTIONNELS
──────────────────────────────────────────
  1. Cartographie des rôles
     1.1 Rôles internes (employés)
     1.2 Rôles clients (e-commerce et B2B)
     1.3 Rôles externes (contrôleur administratif)
  2. User stories par rôle
     (un sous-chapitre par rôle — 23 rôles)
  3. Règles métier transverses
     3.1 Système de permissions (RBAC/ABAC)
     3.2 Chiffrement des données personnelles
     3.3 Gestion des exercices comptables
     3.4 Traçabilité et immuabilité des données

──────────────────────────────────────────
PARTIE II — CONCEPTION TECHNIQUE
──────────────────────────────────────────
  1. Architecture globale
     1.1 Vue d'ensemble (4 dépôts)
     1.2 Séparation frontend / backend
     1.3 Architecture modulaire backend (Modular Monolith)
  2. Stack technique
     2.1 Frontend ERP & Portails
     2.2 Frontend E-commerce
     2.3 Application mobile terrain
     2.4 Backend API GraphQL
     2.5 Base de données
     2.6 Sécurité et chiffrement
     2.7 Infrastructure et conteneurisation
  3. Modélisation de la base de données
     3.1 Diagramme Entité-Association (ERD — PlantUML)
     3.2 Organisation des blocs de données
        3.2.1  Utilisateurs, rôles et permissions
        3.2.2  Contrats et RH
        3.2.3  Sites, équipes et planning
        3.2.4  Culture et production
        3.2.5  Phytosanitaire
        3.2.6  Contrôle qualité
        3.2.7  Stocks, articles et commandes
        3.2.8  Machines et maintenance
        3.2.9  Comptabilité et finance
        3.2.10 E-commerce et fidélité
        3.2.11 Transport et logistique
        3.2.12 Messagerie, signalements et accueil
        3.2.13 Contrôle administratif externe
  4. Conception des interfaces
     4.1 Principes UX/UI
     4.2 Zoning des interfaces principales
     4.3 Wireframes
     4.4 Maquettes

──────────────────────────────────────────
PARTIE III — PLANIFICATION
──────────────────────────────────────────
  1. Découpage en sprints
     1.1 Grille des 27 sprints
     1.2 Dépendances entre sprints
  2. Ordre de développement recommandé

──────────────────────────────────────────
PARTIE IV — DÉVELOPPEMENT
──────────────────────────────────────────
  1. Backend — API GraphQL
     1.1 Structure des modules
     1.2 Authentification et autorisation
     1.3 Schéma GraphQL et resolvers
     1.4 Sécurité applicative (Helmet, Zod, sanitize-html)
  2. Frontend ERP & Portails
     2.1 Structure des composants
     2.2 Gestion d'état (Zustand)
     2.3 Consommation GraphQL (Apollo Client)
  3. Frontend E-commerce
     3.1 SSR et SEO (Next.js)
     3.2 Tunnel de commande
     3.3 Programme de fidélité
  4. Application mobile terrain
     4.1 Scan de lots (QR code)
     4.2 Fonctionnement offline
  5. Intégrations externes
     5.1 Paiement (Stripe)
     5.2 Emails transactionnels (Resend)
     5.3 Stockage fichiers (MinIO)

──────────────────────────────────────────
PARTIE V — QUALITÉ ET MISE EN PRODUCTION
──────────────────────────────────────────
  1. Tests
     1.1 Tests unitaires
     1.2 Tests d'intégration
     1.3 Tests end-to-end
  2. Documentation technique
     2.1 Documentation API (GraphQL Playground / Introspection)
     2.2 README des dépôts
  3. Déploiement
     3.1 Conteneurisation Docker
     3.2 Variables d'environnement et secrets
     3.3 Stratégie de sauvegarde

──────────────────────────────────────────
CONCLUSION ET PERSPECTIVES
──────────────────────────────────────────
  1. Récapitulatif des livrables
  2. Évolutions envisagées
     2.1 Migration vers microservices si nécessaire
     2.2 Application mobile native complète
     2.3 Module IA (prévisions de production, détection précoce maladies)

──────────────────────────────────────────
ANNEXES
──────────────────────────────────────────
  A. Glossaire métier
  B. Schéma ERD complet (PlantUML)
  C. Grille complète des sprints
  D. Récapitulatif des user stories par rôle