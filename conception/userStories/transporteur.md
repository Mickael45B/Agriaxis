# Catégorie : Transporteur (interne)


| **ID** | **Titre**                                              | **Description**                                                                                                                         | **Sprint** |
| ------ | ------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------- | ---------- |
| TR_01  | Consulter ses missions assignées                       | Visualiser les livraisons clients et transferts inter-sites qui lui sont assignés : destination, horaires, chargement attendu, priorité | 17         |
| TR_02  | Accepter une mission                                   | Confirmer la prise en charge d'une mission                                                                                              | 17         |
| TR_03  | Refuser une mission                                    | Signaler une impossibilité (motif obligatoire : véhicule indisponible, surcharge, empêchement)                                          | 17         |
| TR_04  | Démarrer une mission                                   | Marquer le départ avec horodatage automatique, kilométrage départ, site d'origine                                                       | 17         |
| TR_05  | Clôturer une mission                                   | Marquer la fin de mission : horodatage, kilométrage retour, statut global (complète / partielle / échouée)                              | 17         |
| TR_06  | Suspendre une mission en cours                         | Interrompre temporairement une mission (panne, accident, conditions routières) avec motif et horodatage                                 | 17         |
| TR_07  | Consulter l'itinéraire d'une mission                   | Accéder à l'itinéraire détaillé : ordre des arrêts, adresses, contacts, créneaux horaires, instructions spécifiques par client          | 17         |
| TR_08  | Modifier l'ordre des arrêts d'une tournée              | Réorganiser l'ordre de livraison en cours de route (embouteillage, client absent…) avec motif                                           | 17         |
| TR_09  | Consulter un bon de livraison                          | Accéder au bon de livraison d'une commande : contenu, quantités, client, instructions de dépôt                                          | 17         |
| TR_10  | Valider une livraison effectuée                        | Confirmer la remise effective d'une commande au client : horodatage, signature électronique client si disponible                        | 17         |
| TR_11  | Déclarer une livraison partielle                       | Signaler qu'une commande n'a été livrée qu'en partie avec motif et détail des articles non livrés                                       | 17         |
| TR_12  | Déclarer une livraison échouée                         | Signaler l'impossibilité de livrer (client absent, adresse incorrecte, refus réception) avec motif obligatoire                          | 17         |
| TR_13  | Signaler une anomalie sur une livraison                | Déclarer une anomalie constatée (colis abîmé, quantité incorrecte, produit non conforme) sans la traiter                                | 17         |
| TR_14  | Scanner un colis / lot au chargement                   | Scanner les QR codes ou codes-barres des colis chargés pour vérifier la conformité avec le bon de livraison                             | 17         |
| TR_15  | Consulter ses transferts inter-sites assignés          | Visualiser les transferts de marchandises entre sites : site origine, site destination, contenu, date, priorité                         | 17         |
| TR_16  | Valider un transfert inter-sites effectué              | Confirmer la remise de la marchandise au site destinataire avec horodatage et signature du réceptionnaire                               | 17         |
| TR_17  | Signaler une anomalie sur un transfert                 | Déclarer une anomalie constatée lors d'un transfert inter-sites (casse, manquant, erreur de lot)                                        | 17         |
| TR_18  | Effectuer le chargement                                | Charger les commandes ou lots dans le véhicule en vérifiant la conformité avec les bons de livraison                                    | 17         |
| TR_19  | Signaler un écart au chargement                        | Déclarer une différence entre le bon de livraison et la marchandise physiquement disponible avant départ                                | 17         |
| TR_20  | Effectuer et saisir le contrôle pré-départ véhicule    | Remplir la checklist de contrôle avant départ : niveau carburant, pneus, éclairage, bâchage, température de la remorque si applicable   | 17         |
| TR_21  | Signaler un problème véhicule                          | Déclarer un dysfonctionnement ou une anomalie sur le véhicule (panne, dommage, voyant…) transmis au mécanicien                          | 17         |
| TR_22  | Consulter l'historique de son véhicule                 | Accéder aux interventions passées et maintenances planifiées sur le véhicule qui lui est affecté                                        | 17         |
| TR_23  | Consulter le carnet de bord de son véhicule            | Visualiser l'historique des missions, kilométrages et conducteurs du véhicule affecté                                                   | 17         |
| TR_24  | Remplir un compte-rendu de tournée                     | Saisir le bilan de fin de tournée : missions complétées, incidents, kilométrage total, temps de conduite, observations                  | 17         |
| TR_25  | Modifier un compte-rendu de tournée                    | Corriger un compte-rendu soumis (dans un délai limité, avant validation chef de site)                                                   | 17         |
| TR_26  | Consulter ses statistiques de livraison                | Visualiser ses propres indicateurs : taux de livraison dans les délais, livraisons partielles/échouées, kilométrage, incidents          | 17         |
|        | ------------------------------------------------------ | ------------------------------------------------------- Heritage ---------------------------------------------------------------------- |            |
| TR_27  | consulter son planning                                 | Voir son planning : jours travaillés, congés, absences, horaires                                                                        | 2          |
| TR_28  | Consulter les consignes du jour                        | Visualiser les tâches et instructions assignées par la hiérarchie pour la journée                                                       | 2          |
| TR_29  | signaler une absence/retard                            | Informer la hiérarchie d'un empêchement avec motif et durée estimée                                                                     | 3          |
| TR_30  | Signaler un accident du travail                        | Déclarer un accident survenu pendant le temps de travail, avec description et horodatage                                                | 3          |
| TR_31  | poser des congés                                       | Soumettre une demande de congés pour validation par la hiérarchie                                                                       | 3          |
| TR_32  | modifier des congés                                    | Modifier une demande de congés non encore validée                                                                                       | 3          |
| TR_33  | Annuler des congés                                     | Annuler une demande de congés non encore validée                                                                                        | 3          |
| TR_34  | Consulter ses bulletins de paie                        | Accéder à ses bulletins de salaire mensuels en lecture seule                                                                            | 3          |
| TR_35  | voir ses informations personelles                      | Visualiser ses données personnelles (coordonnées, contrat, poste…)                                                                      | 3          |
| TR_36  | modifier ses informations personelles                  | Mettre à jour certaines informations personnelles (adresse, téléphone…) soumises à validation RH                                        | 3          |
| TR_37  | envoyer un message                                     | Envoyer un message via la messagerie interne à un collègue ou groupe                                                                    | 6          |
| TR_38  | modifier un message                                    | Modifier un message envoyé (dans un délai limité défini par l'admin)                                                                    | 6          |
| TR_39  | supprimer un message                                   | Supprimer un message envoyé (dans un délai limité défini par l'admin)                                                                   | 6          |
| TR_40  | Consulter ses notifications                            | Voir les notifications reçues (tâche assignée, message, validation congé…) et les marquer comme lues                                    | 2          |
| TR_41  | Scanner un lot / une plante                            | Scanner un QR code ou code-barres pour identifier un lot ou une plante et accéder à ses informations                                    | 4          |
| TR_42  | Consulter une fiche de culture                         | Visualiser la fiche de culture d'une plante pour connaître les soins, stade, particularités                                             | 4          |
| TR_43  | Consulter une fiche de sécurité produit                | Accéder aux fiches MSDS / FDS des produits phytosanitaires ou engrais utilisés                                                          | 4          |
| TR_44  | remplir une feuille d'activité                         | Saisir le compte-rendu d'une tâche réalisée (type, durée, quantité, localisation…)                                                      | 4          |
| TR_45  | modifier une feuille d'activité                        | Corriger une feuille d'activité soumise (dans un délai limité, soumis à validation)                                                     | 4          |
| TR_46  | consulter sa productivité                              | Visualiser ses performances : tâches réalisées, volumes, comparatif période, par secteur                                                | 4          |
| TR_47  | remplir un probleme technique                          | Déclarer un dysfonctionnement matériel ou d'infrastructure avec description et localisation                                             | 5          |
| TR_48  | modifier un probleme technique                         | Corriger ou compléter un problème technique tant qu'il n'est pas pris en charge                                                         | 5          |
| TR_49  | remplir une maladie/ravageur                           | Déclarer l'observation d'une maladie ou d'un ravageur sur un lot avec localisation et description                                       | 5          |
| TR_50  | modifier une maladie/ravageur                          | Corriger un signalement soumis tant qu'il n'est pas traité                                                                              | 5          |





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
| 18     |                                                                                                              |
| 19     |                                                                                                              |
| 20     |                                                                                                              |
