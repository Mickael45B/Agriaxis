# Catégorie : Employé Informatique

| **ID** | **Titre**                                              | **Description**                                                                                                                         | **Sprint** |
| ------ | ------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------- | ---------- |
| EI_01  | Consulter les tickets de support ouverts               | Accéder à la liste des tickets en cours : demandeur, priorité, catégorie, statut, site concerné                                         | 21         |
| EI_02  | Prendre en charge un ticket                            | S'assigner un ticket et le passer en statut "en cours"                                                                                  | 21         |
| EI_03  | Traiter un ticket                                      | Saisir les actions effectuées et la solution apportée                                                                                   | 21         |
| EI_04  | Clôturer un ticket                                     | Marquer un ticket comme résolu avec commentaire de clôture et demande de confirmation au demandeur                                      | 21         |
| EI_05  | Escalader un ticket                                    | Transmettre un ticket hors de son périmètre de compétence à un prestataire externe ou à la direction                                    | 21         |
| EI_06  | Rouvrir un ticket clôturé                              | Réouvrir un ticket si le problème n'est pas réellement résolu                                                                           | 21         |
| EI_07  | Consulter l'historique des tickets                     | Accéder à tous les tickets passés filtrables par utilisateur, site, catégorie, période, statut                                          | 21         |
| EI_08  | Consulter les statistiques helpdesk                    | Visualiser les KPIs : volume tickets, temps de résolution moyen, taux de résolution, répartition par catégorie et site                  | 21         |
| EI_09  | Créer un compte utilisateur                            | Créer un compte pour un nouvel employé : identifiant, rôle initial, site(s), mot de passe temporaire                                    | 21         |
| EI_10  | Modifier un compte utilisateur                         | Mettre à jour les informations d'un compte (identifiant, site d'affectation, statut actif/inactif)                                      | 21         |
| EI_11  | Soumettre une demande de suppression de compte         | Initier la suppression d'un compte utilisateur soumise à validation RH ou direction                                                     | 21         |
| EI_12  | Réinitialiser un mot de passe                          | Forcer la réinitialisation du mot de passe d'un utilisateur avec envoi du lien sécurisé                                                 | 21         |
| EI_13  | Suspendre / réactiver un compte                        | Bloquer temporairement l'accès d'un utilisateur (incident, congé longue durée) ou le réactiver                                          | 21         |
| EI_14  | Consulter la liste des comptes utilisateurs            | Accéder à la liste complète des comptes avec statut, rôle, dernière connexion, site                                                     | 21         |
| EI_15  | Consulter les connexions actives                       | Visualiser les sessions utilisateurs en cours en temps réel                                                                             | 21         |
| EI_16  | Forcer la déconnexion d'un utilisateur                 | Invalider immédiatement toutes les sessions actives d'un utilisateur                                                                    | 21         |
| EI_17  | Consulter les rôles et permissions existants           | Accéder à la matrice complète des rôles RBAC et attributs ABAC définis dans le système                                                  | 21         |
| EI_18  | Assigner un rôle à un utilisateur                      | Attribuer ou modifier le rôle RBAC d'un utilisateur                                                                                     | 21         |
| EI_19  | Modifier les attributs ABAC d'un utilisateur           | Ajuster les attributs contextuels d'un utilisateur (site_ids, sector_ids, portfolio…)                                                   | 21         |
| EI_20  | Créer un nouveau rôle                                  | Définir un nouveau rôle RBAC avec ses permissions associées                                                                             | 21         |
| EI_21  | Modifier les permissions d'un rôle existant            | Ajuster les permissions attachées à un rôle existant                                                                                    | 21         |
| EI_22  | Consulter l'historique des modifications de rôles      | Accéder à l'audit trail complet des changements de rôles et permissions (qui, quoi, quand)                                              | 21         |
| EI_23  | Consulter les permissions effectives d'un utilisateur  | Visualiser en temps réel les permissions réellement actives pour un utilisateur donné (RBAC + ABAC combinés)                            | 21         |
| EI_24  | Consulter les logs système                             | Accéder aux logs applicatifs, d'accès et d'erreurs (Winston / Pino) filtrables par niveau, date, service, utilisateur                   | 21         |
| EI_25  | Consulter les logs d'audit                             | Accéder à l'audit trail des actions sensibles : modifications de rôles, accès aux données RH/finance, exports, suppressions             | 21         |
| EI_26  | Consulter les alertes de sécurité                      | Visualiser les alertes de sécurité actives : tentatives de connexion échouées, accès suspects, anomalies de trafic                      | 21         |
| EI_27  | Déclarer un incident de sécurité                       | Ouvrir un incident de sécurité : description, périmètre impacté, niveau de criticité, actions immédiates prises                         | 21         |
| EI_28  | Traiter un incident de sécurité                        | Saisir les actions correctives, la chronologie et la résolution d'un incident                                                           | 21         |
| EI_29  | Clôturer un incident de sécurité                       | Marquer un incident comme résolu avec rapport post-incident obligatoire                                                                 | 21         |
| EI_30  | Gérer les sauvegardes                                  | Consulter l'état des sauvegardes automatiques, déclencher une sauvegarde manuelle, vérifier l'intégrité                                 | 21         |
| EI_31  | Lancer une restauration                                | Initier la restauration d'une sauvegarde sur un environnement donné                                                                     | 21         |
| EI_32  | Consulter le tableau de bord de sécurité               | Visualiser les indicateurs de sécurité : disponibilité, tentatives d'intrusion, certificats SSL expirant, état des sauvegardes          | 21         |
| EI_33  | Consulter l'état des serveurs et services              | Visualiser en temps réel l'état des serveurs, services applicatifs (Apollo, Redis, BullMQ…), bases de données                           | 21         |
| EI_34  | Déclarer une maintenance planifiée                     | Annoncer une fenêtre de maintenance avec impact, durée estimée et périmètre                                                             | 21         |
| EI_35  | Clôturer une maintenance                               | Marquer la fin d'une maintenance avec rapport des opérations effectuées                                                                 | 21         |
| EI_36  | Gérer les certificats SSL / TLS                        | Consulter les dates d'expiration des certificats et déclencher leur renouvellement                                                      | 21         |
| EI_37  | Gérer les variables d'environnement et secrets         | Consulter et mettre à jour les configurations sensibles (hors clés de production — gérées via vault)                                    | 21         |
| EI_38  | Consulter les métriques de performance                 | Accéder aux métriques applicatives : temps de réponse GraphQL, charge serveur, utilisation Redis, queues BullMQ                         | 21         |
| EI_39  | Créer une fiche matériel                               | Enregistrer un équipement informatique : type, marque, modèle, numéro de série, site d'affectation, utilisateur assigné, date d'achat   | 21         |
| EI_40  | Modifier une fiche matériel                            | Mettre à jour les informations d'un équipement (mutation, réaffectation, état)                                                          | 21         |
| EI_41  | Archiver une fiche matériel                            | Archiver un équipement mis hors service ou cédé (non supprimable)                                                                       | 21         |
| EI_42  | Consulter l'inventaire du parc matériel                | Visualiser l'ensemble du parc informatique par site, par utilisateur, par état                                                          | 21         |
| EI_43  | Gérer l'annuaire interne                               | Créer, modifier et archiver les contacts et postes téléphoniques de l'annuaire interne (consulté par l'hôte d'accueil HA_16)            | 21         |
|        | ------------------------------------------------------ | ------------------------------------------------------- Heritage ---------------------------------------------------------------------- |            |
| EI_44  | consulter son planning                                 | Voir son planning : jours travaillés, congés, absences, horaires                                                                        | 2          |
| EI_45  | Consulter les consignes du jour                        | Visualiser les tâches et instructions assignées par la hiérarchie pour la journée                                                       | 2          |
| EI_46  | signaler une absence/retard                            | Informer la hiérarchie d'un empêchement avec motif et durée estimée                                                                     | 3          |
| EI_47  | Signaler un accident du travail                        | Déclarer un accident survenu pendant le temps de travail, avec description et horodatage                                                | 3          |
| EI_48  | poser des congés                                       | Soumettre une demande de congés pour validation par la hiérarchie                                                                       | 3          |
| EI_49  | modifier des congés                                    | Modifier une demande de congés non encore validée                                                                                       | 3          |
| EI_50  | Annuler des congés                                     | Annuler une demande de congés non encore validée                                                                                        | 3          |
| EI_51  | Consulter ses bulletins de paie                        | Accéder à ses bulletins de salaire mensuels en lecture seule                                                                            | 3          |
| EI_52  | voir ses informations personelles                      | Visualiser ses données personnelles (coordonnées, contrat, poste…)                                                                      | 3          |
| EI_53  | modifier ses informations personelles                  | Mettre à jour certaines informations personnelles (adresse, téléphone…) soumises à validation RH                                        | 3          |
| EI_54  | envoyer un message                                     | Envoyer un message via la messagerie interne à un collègue ou groupe                                                                    | 6          |
| EI_55  | modifier un message                                    | Modifier un message envoyé (dans un délai limité défini par l'admin)                                                                    | 6          |
| EI_56  | supprimer un message                                   | Supprimer un message envoyé (dans un délai limité défini par l'admin)                                                                   | 6          |
| EI_57  | Consulter ses notifications                            | Voir les notifications reçues (tâche assignée, message, validation congé…) et les marquer comme lues                                    | 2          |
| EI_58  | Scanner un lot / une plante                            | Scanner un QR code ou code-barres pour identifier un lot ou une plante et accéder à ses informations                                    | 4          |
| EI_59  | Consulter une fiche de culture                         | Visualiser la fiche de culture d'une plante pour connaître les soins, stade, particularités                                             | 4          |
| EI_60  | Consulter une fiche de sécurité produit                | Accéder aux fiches MSDS / FDS des produits phytosanitaires ou engrais utilisés                                                          | 4          |
| EI_61  | remplir une feuille d'activité                         | Saisir le compte-rendu d'une tâche réalisée (type, durée, quantité, localisation…)                                                      | 4          |
| EI_62  | modifier une feuille d'activité                        | Corriger une feuille d'activité soumise (dans un délai limité, soumis à validation)                                                     | 4          |
| EI_63  | consulter sa productivité                              | Visualiser ses performances : tâches réalisées, volumes, comparatif période, par secteur                                                | 4          |
| EI_64  | remplir un probleme technique                          | Déclarer un dysfonctionnement matériel ou d'infrastructure avec description et localisation                                             | 5          |
| EI_65  | modifier un probleme technique                         | Corriger ou compléter un problème technique tant qu'il n'est pas pris en charge                                                         | 5          |
| EI_66  | remplir une maladie/ravageur                           | Déclarer l'observation d'une maladie ou d'un ravageur sur un lot avec localisation et description                                       | 5          |
| EI_67  | modifier une maladie/ravageur                          | Corriger un signalement soumis tant qu'il n'est pas traité                                                                              | 5          |


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
| 15     | **Comptabilité** — Encaissements, paiements fournisseurs, rapprochements bancaires, TVA, clôtures, exports   |
| 16     | **Recrutement** — Offres, candidatures, pipeline entretiens, validation embauche                             |
| 17     | **Transport & logistique** — Missions, tournées, livraisons, transferts inter-sites, véhicules               |
| 18     | **Gestion des stocks** — Articles, fournisseurs, emplacements, mouvements, inventaires, alertes, demandes    |
| 19     | **Contrôle qualité** — Grilles, réception, production, expédition, retours clients, conformité, rapports     |
| 20     | **Vente au détail** — Caisse, catalogue, fidélité, retours, rayons, étiquetage, stats vendeur                |
| 21     | **Informatique & sécurité** — Comptes, rôles RBAC/ABAC, helpdesk, logs, incidents, infra, parc matériel      |
| 22     |                                                                                                              |
| 23     |                                                                                                              |
| 24     |                                                                                                              |
| 25     |                                                                                                              |
| 26     |                                                                                                              |
| 27     |                                                                                                              |
| 28     |                                                                                                              |
| 29     |                                                                                                              |
| 30     |                                                                                                              |
