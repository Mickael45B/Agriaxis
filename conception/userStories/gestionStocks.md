# Catégorie : Gestionnaire de Stock

| **ID** | **Titre**                                              | **Description**                                                                                                                         | **Sprint** |
| ------ | ------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------- | ---------- |
| GS_01  | Enregistrer une entrée en stock                        | Saisir la réception d'un produit ou intrant : référence, quantité, lot, fournisseur, emplacement, date — après validation CQ (CQ_08)    | 18         |
| GS_02  | Enregistrer une sortie de stock                        | Saisir la consommation ou l'expédition d'un article : référence, quantité, motif (production, expédition, casse, péremption)            | 18         |
| GS_03  | Enregistrer un transfert inter-sites                   | Saisir le mouvement de stock entre deux sites : article, quantité, site origine, site destination, date                                 | 18         |
| GS_04  | Enregistrer une casse / perte                          | Déclarer une destruction ou perte de stock avec motif (casse, péremption, vol, sinistre) et quantité                                    | 18         |
| GS_05  | Valider une réservation commerciale                    | Confirmer ou libérer une réservation de stock soumise par un commercial (CO_29)                                                         | 18         |
| GS_06  | Ajuster un stock manuellement                          | Corriger un écart de stock constaté avec motif obligatoire et pièce justificative                                                       | 18         |        
| GS_07  | Consulter l'historique des mouvements                  | Accéder à tous les mouvements de stock par article, par site, par type, par période                                                     | 18         |
| GS_08  | Consulter les niveaux de stock en temps réel           | Visualiser les quantités disponibles, réservées et bloquées par article, par site, par emplacement                                      | 18         |
| GS_09  | Paramétrer les seuils d'alerte par article             | Définir les seuils de stock minimum et maximum déclenchant des alertes de réapprovisionnement ou de surstock par article et par site    | 18         |
| GS_10  | Consulter les alertes de stock actives                 | Visualiser les articles en rupture, sous seuil minimum ou en surstock sur l'ensemble de ses sites                                       | 18         |
| GS_11  | Consulter les stocks bloqués                           | Visualiser les lots bloqués (DAR non écoulé, non-conformité qualité, litige) avec motif et délai estimé de déblocage                    | 18         |
| GS_12  | Consulter les réservations en cours                    | Visualiser toutes les réservations de stock actives : commercial, client, montant, date d'expiration                                    | 18         |
| GS_13  | Créer un emplacement                                   | Définir un nouvel emplacement physique : site, zone, allée, rayon, capacité maximale, type de stockage (ambiant, froid, local phyto…)   | 18         |
| GS_14  | Modifier un emplacement                                | Mettre à jour les informations d'un emplacement (capacité, type, statut actif/inactif)                                                  | 18         |
| GS_15  | Archiver un emplacement                                | Désactiver un emplacement supprimé physiquement (non supprimable — historique des mouvements conservé)                                  | 18         |
| GS_16  | Affecter un article à un emplacement                   | Associer un article ou lot à un emplacement physique                                                                                    | 18         |
| GS_17  | Déplacer un article entre emplacements                 | Enregistrer le déplacement physique d'un article d'un emplacement à un autre sur le même site                                           | 18         |
| GS_18  | Consulter le plan de stockage                          | Visualiser la carte des emplacements d'un site avec taux d'occupation et localisation des articles                                      | 18         |
| GS_19  | Créer un inventaire                                    | Initier un inventaire (partiel ou complet) sur un site : périmètre, date, responsables de comptage                                      | 18         |
| GS_20  | Saisir les résultats de comptage                       | Enregistrer les quantités comptées par article et par emplacement                                                                       | 18         |
| GS_21  | Consulter les écarts d'inventaire                      | Visualiser les différences entre stock théorique et stock compté, avec calcul de la valeur des écarts                                   | 18         |
| GS_22  | Valider un inventaire                                  | Approuver les résultats de comptage et appliquer les ajustements automatiques au stock théorique                                        | 18         |
| GS_23  | Consulter l'historique des inventaires                 | Accéder aux inventaires passés avec résultats, écarts et ajustements appliqués                                                          | 18         |
| GS_24  | Soumettre un besoin de réapprovisionnement             | Déclarer un besoin en article avec référence, quantité, urgence, site concerné, fournisseur suggéré — transmis à l'acheteur / direction | 18         |
| GS_25  | Traiter une demande d'intrants (chef de culture)       | Prendre en charge une demande d'intrants soumise par le chef de culture (CC_28) : vérification stock, transmission si besoin de commande| 18         |
| GS_26  | Traiter une demande de pièces détachées (mécanicien)   | Prendre en charge une demande de pièces soumise par le mécanicien (ME_16) : vérification stock, allocation ou commande                  | 18         |
| GS_27  | Traiter une demande de produits phyto (employé phyto)  | Prendre en charge une demande de produits phytosanitaires soumise par l'employé phyto (EPH_26)                                          | 18         |
| GS_28  | Suivre les commandes fournisseurs en cours             | Consulter l'état des commandes passées par l'acheteur / direction : statut, date de livraison prévue, quantité commandée                | 18         |
| GS_29  | Enregistrer la réception d'une commande fournisseur    | Saisir la réception physique d'une commande avec quantité reçue, numéro de lot, date — avant transmission au CQ pour contrôle           | 18         |
| GS_30  | Créer une fiche article                                | Créer la référence d'un article dans le catalogue stock : nom, type, unité, fournisseurs, seuils min/max, conditions de stockage        | 18         |
| GS_31  | Modifier une fiche article                             | Mettre à jour les informations d'un article (seuils, fournisseurs, conditions)                                                          | 18         |
| GS_32  | Archiver une fiche article                             | Archiver un article obsolète (non supprimable — historique des mouvements conservé)                                                     | 18         |
| GS_33  | Créer une fiche fournisseur                            | Enregistrer un fournisseur : raison sociale, SIRET, contacts, délais de livraison habituels, articles fournis                           | 18         |
| GS_34  | Modifier une fiche fournisseur                         | Mettre à jour les informations d'un fournisseur                                                                                         | 18         |
| GS_35  | Archiver une fiche fournisseur                         | Archiver un fournisseur inactif (non supprimable)                                                                                       | 18         |
| GS_36  | Consulter les statistiques de stock                    | Visualiser les indicateurs par site : rotation des stocks, taux de rupture, valeur du stock, écarts d'inventaire, taux de service       | 18         |
| GS_37  | Générer un rapport de stock                            | Produire un rapport personnalisé (période, site, type de stock, article) à destination du chef de site ou de la direction               | 18         |
| GS_38  | Consulter la valorisation du stock                     | Accéder à la valeur comptable du stock par article, par type, par site, par période                                                     | 18         |
|        | ------------------------------------------------------ | ------------------------------------------------------- Heritage ---------------------------------------------------------------------- |            |
| GS_39  | consulter son planning                                 | Voir son planning : jours travaillés, congés, absences, horaires                                                                        | 2          |
| GS_40  | Consulter les consignes du jour                        | Visualiser les tâches et instructions assignées par la hiérarchie pour la journée                                                       | 2          |
| GS_41  | signaler une absence/retard                            | Informer la hiérarchie d'un empêchement avec motif et durée estimée                                                                     | 3          |
| GS_42  | Signaler un accident du travail                        | Déclarer un accident survenu pendant le temps de travail, avec description et horodatage                                                | 3          |
| GS_43  | poser des congés                                       | Soumettre une demande de congés pour validation par la hiérarchie                                                                       | 3          |
| GS_44  | modifier des congés                                    | Modifier une demande de congés non encore validée                                                                                       | 3          |
| GS_45  | Annuler des congés                                     | Annuler une demande de congés non encore validée                                                                                        | 3          |
| GS_46  | Consulter ses bulletins de paie                        | Accéder à ses bulletins de salaire mensuels en lecture seule                                                                            | 3          |
| GS_47  | voir ses informations personelles                      | Visualiser ses données personnelles (coordonnées, contrat, poste…)                                                                      | 3          |
| GS_48  | modifier ses informations personelles                  | Mettre à jour certaines informations personnelles (adresse, téléphone…) soumises à validation RH                                        | 3          |
| GS_49  | envoyer un message                                     | Envoyer un message via la messagerie interne à un collègue ou groupe                                                                    | 6          |
| GS_50  | modifier un message                                    | Modifier un message envoyé (dans un délai limité défini par l'admin)                                                                    | 6          |
| GS_51  | supprimer un message                                   | Supprimer un message envoyé (dans un délai limité défini par l'admin)                                                                   | 6          |
| GS_52  | Consulter ses notifications                            | Voir les notifications reçues (tâche assignée, message, validation congé…) et les marquer comme lues                                    | 2          |
| GS_53  | Scanner un lot / une plante                            | Scanner un QR code ou code-barres pour identifier un lot ou une plante et accéder à ses informations                                    | 4          |
| GS_54  | Consulter une fiche de culture                         | Visualiser la fiche de culture d'une plante pour connaître les soins, stade, particularités                                             | 4          |
| GS_55  | Consulter une fiche de sécurité produit                | Accéder aux fiches MSDS / FDS des produits phytosanitaires ou engrais utilisés                                                          | 4          |
| GS_56  | remplir une feuille d'activité                         | Saisir le compte-rendu d'une tâche réalisée (type, durée, quantité, localisation…)                                                      | 4          |
| GS_57  | modifier une feuille d'activité                        | Corriger une feuille d'activité soumise (dans un délai limité, soumis à validation)                                                     | 4          |
| GS_58  | consulter sa productivité                              | Visualiser ses performances : tâches réalisées, volumes, comparatif période, par secteur                                                | 4          |
| GS_59  | remplir un probleme technique                          | Déclarer un dysfonctionnement matériel ou d'infrastructure avec description et localisation                                             | 5          |
| GS_60  | modifier un probleme technique                         | Corriger ou compléter un problème technique tant qu'il n'est pas pris en charge                                                         | 5          |
| GS_61  | remplir une maladie/ravageur                           | Déclarer l'observation d'une maladie ou d'un ravageur sur un lot avec localisation et description                                       | 5          |
| GS_62  | modifier une maladie/ravageur                          | Corriger un signalement soumis tant qu'il n'est pas traité                                                                              | 5          |


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
| 8      | **Management d'équipe** — Supervision multi-groupes, pool de tâches, planning global, escalades, clôtures   |
| 9      | **Management de site** — Tableau de bord site, planning multi-secteurs, consignes, stats, recrutement        |
| 10     | **Culture & production** — Fiches culture, protocoles, catalogue végétal, plannings production, intrants     |
| 11     | **Phytosanitaire** — Signalements, diagnostics, prescriptions, registre réglementaire, alertes multi-sites  |
| 12     | **Maintenance** — Ordres de travail, fiches machines, interventions, préventif, pièces détachées             |
| 13     | **Syndical & RH avancé** — CSE, BDES, négociation, accords, élections, défense individuelle, délégation     |
| 14     | **CRM & vente B2B** — Fiches clients, devis, contrats, commandes, stocks, tarifs, stats commerciales        |
| 15     | **Comptabilité** — Encaissements, paiements fournisseurs, rapprochements bancaires, TVA, clôtures, exports  |
| 16     | **Recrutement** — Offres, candidatures, pipeline entretiens, validation embauche                             |
| 17     | **Transport & logistique** — Missions, tournées, livraisons, transferts inter-sites, véhicules               |
| 18     | **Gestion des stocks** — Articles, fournisseurs, emplacements, mouvements, inventaires, alertes, demandes   |
| 19     |                                                                                                              |
| 20     |                                                                                                              |
| 21     |                                                                                                              |
| 22     |                                                                                                              |
| 23     |                                                                                                              |
| 24     |                                                                                                              |
| 25     |                                                                                                              |
| 26     |                                                                                                              |
| 27     |                                                                                                              |
| 28     |                                                                                                              |
| 29     |                                                                                                              |
| 30     |                                                                                                              |
