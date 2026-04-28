# Catégorie : Commercial


| **ID** | **Titre**                                              | **Description**                                                                                                                                     | **Sprint** |
| ------ | ------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------- | ---------- |
| CO_01  | Créer une fiche client                                 | Créer un nouveau compte client : raison sociale / nom, type (particulier / détaillant / semi-grossiste / grossiste), coordonnées, SIRET, TVA intra  | 14         |
| CO_02  | Modifier une fiche client                              | Mettre à jour les informations d'un client existant                                                                                                 | 14         |
| CO_03  | Archiver une fiche client                              | Archiver un client inactif (non supprimable — lié à des commandes et factures passées)                                                              | 14         |
| CO_04  | Consulter son portefeuille clients                     | Visualiser l'ensemble de ses clients avec statut, dernière commande, chiffre d'affaires, alertes (impayés, contrat expirant…)                       | 14         |
| CO_05  | Consulter la fiche détaillée d'un client               | Accéder au profil complet d'un client : historique commandes, devis, contrats, CA, contacts, notes commerciales                                     | 14         |
| CO_06  | Ajouter une note commerciale sur un client             | Saisir une note libre sur un client (compte-rendu de visite, observation, point d'attention)                                                        | 14         |
| CO_07  | Planifier une action commerciale                       | Créer un rappel ou une tâche commerciale liée à un client : relance, visite, renouvellement contrat, suivi devis                                    | 14         |
| CO_08  | Consulter les actions commerciales planifiées          | Visualiser ses tâches et rappels à venir, filtrables par client, type, échéance                                                                     | 14         |
| CO_09  | Créer un devis                                         | Générer un devis pour un client : produits, quantités, prix (grille tarifaire auto-appliquée selon type client), remise encadrée, validité          | 14         |
| CO_10  | Modifier un devis                                      | Corriger un devis non encore accepté par le client                                                                                                  | 14         |
| CO_11  | Dupliquer un devis                                     | Créer un nouveau devis à partir d'un existant (même client ou client différent)                                                                     | 14         |
| CO_12  | Envoyer un devis au client                             | Transmettre un devis par email au client via le système                                                                                             | 14         |
| CO_13  | Relancer un devis                                      | Envoyer une relance automatique ou manuelle sur un devis sans réponse client                                                                        | 14         |
| CO_14  | Marquer un devis comme accepté                         | Enregistrer l'acceptation d'un devis par le client — déclenche la création automatique de la commande                                               | 14         |
| CO_15  | Marquer un devis comme refusé / perdu                  | Clore un devis refusé avec motif (prix, délai, concurrent…) pour analyse des pertes                                                                 | 14         |
| CO_16  | Consulter ses devis                                    | Accéder à la liste de ses devis filtrables par statut (brouillon, envoyé, relancé, accepté, refusé, expiré), client, date, montant                  | 14         |
| CO_17  | Créer un contrat client                                | Rédiger un contrat cadre pour un client B2B : conditions tarifaires négociées, volumes engagés, périodicité, durée, clauses spécifiques             | 14         |
| CO_18  | Modifier un contrat                                    | Mettre à jour un contrat en cours (avenant) avec motif et nouvelle version                                                                          | 14         |
| CO_19  | Envoyer un contrat au client                           | Transmettre un contrat pour signature via le système (email + signature électronique)                                                               | 14         |
| CO_20  | Marquer un contrat comme signé                         | Enregistrer la signature du contrat avec date et document signé joint                                                                               | 14         |
| CO_21  | Résilier un contrat                                    | Initier la résiliation d'un contrat avec motif et date d'effet                                                                                      | 14         |
| CO_22  | Consulter ses contrats                                 | Accéder à la liste de ses contrats filtrables par statut (actif, expirant, expiré, résilié), client, date                                           | 14         |
| CO_23  | Créer une commande manuellement                        | Saisir une commande pour un client (téléphone, visite, email) sans passer par le devis                                                              | 14         |
| CO_24  | Consulter les commandes de son portefeuille            | Accéder à toutes les commandes de ses clients : statut, montant, livraison prévue, alertes                                                          | 14         |
| CO_25  | Suivre l'avancement d'une commande                     | Consulter le statut détaillé d'une commande : préparation, expédition, livraison, retour éventuel                                                   | 14         |
| CO_26  | Annuler une commande                                   | Initier l'annulation d'une commande avec motif                                                                                                      | 14         |
| CO_27  | Consulter le stock en temps réel                       | Accéder aux niveaux de stock complets par produit, variété, site, lot — avec statut de disponibilité et alertes DAR                                 | 14         |
| CO_28  | Consulter les disponibilités prévisionnelles           | Visualiser les prévisions de production (plannings de culture) pour anticiper les disponibilités futures à proposer aux clients                     | 14         |
| CO_29  | Réserver un stock pour un client                       | Bloquer une quantité de stock pour une commande ou un devis en cours de finalisation                                                                | 14         |
| CO_30  | Consulter les grilles tarifaires                       | Accéder aux grilles tarifaires par type de client (particulier, détaillant, semi-grossiste, grossiste) et par produit                               | 14         |
| CO_31  | Appliquer une remise encadrée                          | Appliquer une remise sur un devis ou une commande dans la limite du seuil autorisé pour son profil                                                  | 14         |
| CO_32  | Soumettre une demande de remise exceptionnelle         | Demander une remise hors plafond pour un client stratégique avec justification                                                                      | 14         |
| CO_33  | Consulter ses statistiques commerciales                | Visualiser ses KPIs : CA réalisé vs objectif, taux de transformation devis, panier moyen, répartition par type client, pertes et motifs             | 14         |
| CO_34  | Consulter le tableau de bord de son portefeuille       | Accéder à une vue synthétique : clients actifs / inactifs, devis en cours, contrats expirant, alertes impayés, commandes en attente                 | 14         |
| CO_35  | Exporter ses données commerciales                      | Exporter en CSV / Excel ses commandes, devis ou statistiques sur une période donnée                                                                 | 14         |
|        | ------------------------------------------------------ | ------------------------------------------------------- Heritage ---------------------------------------------------------------------------------- |            |
| CO_36  | consulter son planning                                 | Voir son planning : jours travaillés, congés, absences, horaires                                                                                    | 2          |
| CO_37  | Consulter les consignes du jour                        | Visualiser les tâches et instructions assignées par la hiérarchie pour la journée                                                                   | 2          |
| CO_38  | signaler une absence/retard                            | Informer la hiérarchie d'un empêchement avec motif et durée estimée                                                                                 | 3          |
| CO_39  | Signaler un accident du travail                        | Déclarer un accident survenu pendant le temps de travail, avec description et horodatage                                                            | 3          |
| CO_40  | poser des congés                                       | Soumettre une demande de congés pour validation par la hiérarchie                                                                                   | 3          |
| CO_41  | modifier des congés                                    | Modifier une demande de congés non encore validée                                                                                                   | 3          |
| CO_42  | Annuler des congés                                     | Annuler une demande de congés non encore validée                                                                                                    | 3          |
| CO_43  | Consulter ses bulletins de paie                        | Accéder à ses bulletins de salaire mensuels en lecture seule                                                                                        | 3          |
| CO_44  | voir ses informations personelles                      | Visualiser ses données personnelles (coordonnées, contrat, poste…)                                                                                  | 3          |
| CO_45  | modifier ses informations personelles                  | Mettre à jour certaines informations personnelles (adresse, téléphone…) soumises à validation RH                                                    | 3          |
| CO_46  | envoyer un message                                     | Envoyer un message via la messagerie interne à un collègue ou groupe                                                                                | 6          |
| CO_47  | modifier un message                                    | Modifier un message envoyé (dans un délai limité défini par l'admin)                                                                                | 6          |
| CO_48  | supprimer un message                                   | Supprimer un message envoyé (dans un délai limité défini par l'admin)                                                                               | 6          |
| CO_49  | Consulter ses notifications                            | Voir les notifications reçues (tâche assignée, message, validation congé…) et les marquer comme lues                                                | 2          |
| CO_50  | Scanner un lot / une plante                            | Scanner un QR code ou code-barres pour identifier un lot ou une plante et accéder à ses informations                                                | 4          |
| CO_51  | Consulter une fiche de culture                         | Visualiser la fiche de culture d'une plante pour connaître les soins, stade, particularités                                                         | 4          |
| CO_52  | Consulter une fiche de sécurité produit                | Accéder aux fiches MSDS / FDS des produits phytosanitaires ou engrais utilisés                                                                      | 4          |
| CO_53  | remplir une feuille d'activité                         | Saisir le compte-rendu d'une tâche réalisée (type, durée, quantité, localisation…)                                                                  | 4          |
| CO_54  | modifier une feuille d'activité                        | Corriger une feuille d'activité soumise (dans un délai limité, soumis à validation)                                                                 | 4          |
| CO_55  | consulter sa productivité                              | Visualiser ses performances : tâches réalisées, volumes, comparatif période, par secteur                                                            | 4          |
| CO_56  | remplir un probleme technique                          | Déclarer un dysfonctionnement matériel ou d'infrastructure avec description et localisation                                                         | 5          |
| CO_57  | modifier un probleme technique                         | Corriger ou compléter un problème technique tant qu'il n'est pas pris en charge                                                                     | 5          |
| CO_58  | remplir une maladie/ravageur                           | Déclarer l'observation d'une maladie ou d'un ravageur sur un lot avec localisation et description                                                   | 5          |
| CO_59  | modifier une maladie/ravageur                          | Corriger un signalement soumis tant qu'il n'est pas traité                                                                                          | 5          |







## Signification des sprints

| Sprint | Thème                                                                                                        |
| ------ | ------------------------------------------------------------------------------------------------------------ |
| 1      | **Socle technique** — Auth JWT + RBAC/ABAC, schéma BDD PostgreSQL, API GraphQL Apollo Server socle           |
| 2      | **MVP Employé Polyvalent** — Planning, consignes, notifications, infos entreprise                            |
| 3      | **RH de base** — Congés, absences, accidents, bulletins, infos personnelles                                  |
| 4      | **Terrain** — Scan lots, fiches culture/sécurité, feuilles d'activité, productivité                          |
| 5      | **Signalements** — Problèmes techniques, maladies/ravageurs, red tag, green tag                              |
| 6      | **Messagerie interne** — Envoi, modification, suppression de messages                                        |
| 7      | **Management de groupe** — Pointage, tâches, planning, validation feuilles, signalements, rapports           |
| 8      | **Management d'équipe** — Supervision multi-groupes, pool de tâches, planning global, escalades, clôtures    |
| 9      | **Management de site** — Tableau de bord site, planning multi-secteurs, consignes, stats, recrutement        |
| 10     | **Culture & production** — Fiches culture, protocoles, catalogue végétal, plannings production, intrants     |
| 11     | **Phytosanitaire** — Signalements, diagnostics, prescriptions, registre réglementaire, alertes multi-sites   |
| 12     | **Maintenance** — Ordres de travail, fiches machines, interventions, préventif, pièces détachées             |
| 13     | **Syndical & RH avancé** — CSE, BDES, négociation, accords, élections, défense individuelle, délégation      |
| 14     | **CRM & vente B2B** — Fiches clients, devis, contrats, commandes, stocks, tarifs, stats commerciales         |
| 15     |                                                                                                              |
| 16     |                                                                                                              |
| 17     |                                                                                                              |
| 18     |                                                                                                              |
| 19     |                                                                                                              |
| 20     |                                                                                                              |
