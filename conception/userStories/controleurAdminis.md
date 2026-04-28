# Catégorie : Contrôleur administratif

| **ID** | **Titre**                                                        | **Description**                                                                                                                         | **Sprint** |
| ------ | ---------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------- | ---------- |
| CA_01  | Accéder à son espace de contrôle                                 | Se connecter à l'espace dédié au contrôle avec les accès provisionnés par l'EI, limités au périmètre et à la durée définis              | 23         |
| CA_02  | Consulter les documents mis à disposition                        | Accéder aux documents préparés et déposés par le comptable / RH dans son espace : déclarations, registres, bilans, journaux, contrats…  | 23         |
| CA_03  | Télécharger un document                                          | Exporter un document disponible dans son espace en PDF ou format natif                                                                  | 23         |
| CA_04  | Soumettre une demande de document complémentaire                 | Formuler une demande de document ou d'information non encore disponible dans l'espace                                                   | 23         |
| CA_05  | Consulter l'état de ses demandes                                 | Visualiser le statut de ses demandes de documents (en attente, en cours de préparation, disponible)                                     | 23         |
| CA_06  | Consulter l'historique de ses accès et téléchargements           | Accéder au journal de ses propres actions dans l'espace (connexions, consultations, téléchargements, demandes)                          | 23         |
| CA_07  | Consulter les déclarations de cotisations sociales               | Accéder aux DSN (Déclarations Sociales Nominatives) et bordereaux de cotisations sur la période contrôlée                               | 23         |
| CA_08  | Consulter les éléments de masse salariale                        | Accéder aux données agrégées de masse salariale par période (pas les fiches de paie individuelles nominatives)                          | 23         |
| CA_09  | Consulter les contrats de travail en vigueur                     | Accéder aux contrats actifs sur la période contrôlée                                                                                    | 23         |
| CA_10  | Consulter le FEC (Fichier des Écritures Comptables)              | Accéder au FEC généré par le comptable (CP_30) pour l'exercice contrôlé                                                                 | 23         |
| CA_11  | Consulter les déclarations de TVA                                | Accéder aux déclarations TVA (CA3 / CA12) archivées sur la période contrôlée                                                            | 23         |
| CA_12  | Consulter les états de synthèse comptables                       | Accéder au bilan et compte de résultat de l'exercice contrôlé                                                                           | 23         |
| CA_13  | Consulter les journaux comptables                                | Accéder aux journaux des écritures (achats, ventes, banque, OD) sur la période contrôlée                                                | 23         |
| CA_14  | Consulter les contrats de travail et avenants                    | Accéder aux contrats et avenants des employés sur la période contrôlée                                                                  | 23         |
| CA_15  | Consulter les registres du personnel                             | Accéder au registre unique du personnel (entrées, sorties, types de contrats) sur la période contrôlée                                  | 23         |
| CA_16  | Consulter les plannings et temps de travail                      | Accéder aux plannings validés et feuilles d'activité sur la période contrôlée pour vérification du droit du travail                     | 23         |
| CA_17  | Consulter les accidents du travail déclarés                      | Accéder aux déclarations d'accidents du travail sur la période contrôlée                                                                | 23         |
| CA_18  | Consulter le DUERP (Document Unique d'Évaluation des Risques)    | Accéder au document unique d'évaluation des risques professionnels                                                                      | 23         |
| CA_19  | Consulter les registres de formation et habilitations            | Accéder aux formations réalisées et certifications des employés sur la période contrôlée                                                | 23         |
| CA_20  | Consulter le registre phytosanitaire                             | Accéder au registre des traitements phytosanitaires appliqués (CC_21) sur la période contrôlée                                          | 23         |
| CA_21  | Consulter les fiches de culture                                  | Accéder aux fiches de culture en vigueur sur la période contrôlée                                                                       | 23         |
| CA_22  | Consulter les certificats Certiphyto des opérateurs              | Vérifier les certifications Certiphyto des employés phytosanitaires ayant réalisé des traitements                                       | 23         |
| CA_23  | Consulter les fiches de sécurité des produits utilisés           | Accéder aux FDS/MSDS des produits phytosanitaires utilisés sur la période contrôlée                                                     | 23         |
| CA_24  | Consulter les passeports phytosanitaires des lots                | Accéder aux passeports phytosanitaires associés aux lots produits et expédiés sur la période contrôlée                                  | 23         |
| CA_25  | Consulter les alertes phytosanitaires émises                     | Accéder aux alertes phytosanitaires émises par le chef de culture (CC_23) sur la période contrôlée                                      | 23         |
| CA_26  | Consulter les états financiers de l'exercice                     | Accéder au bilan, compte de résultat, annexes sur l'exercice audité                                                                     | 23         |
| CA_27  | Consulter les journaux et écritures comptables                   | Accéder au détail des écritures sur l'exercice audité, avec piste d'audit complète                                                      | 23         |
| CA_28  | Consulter les contrats clients et fournisseurs                   | Accéder aux contrats significatifs sur l'exercice audité pour vérification des engagements hors bilan                                   | 23         |
| CA_29  | Consulter les procès-verbaux de réunions CSE                     | Accéder aux PV de réunions CSE de l'exercice audité (informations sociales)                                                             | 23         |
| CA_30  | Soumettre un rapport d'audit                                     | Déposer le rapport d'audit finalisé dans l'espace dédié pour transmission à la direction et archivage                                   | 23         |
| CA_31  | Consulter ses informations d'accès                               | Voir les paramètres de son compte : périmètre autorisé, type de contrôle, date d'expiration d'accès                                     | 23         |
| CA_32  | Envoyer un message à l'interlocuteur interne désigné             | Contacter le comptable ou RH désigné comme interlocuteur du contrôle via la messagerie interne                                          | 23         |
| CA_33  | Consulter ses notifications                                      | Voir les notifications reçues (document disponible, demande traitée) et les marquer comme lues                                          | 23         |


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
| 22     | **Dirigeant** — Tableaux de bord consolidés, validations, stratégie, crise, tarifs, sites, rapports          |
| 23     | **Contrôle administratif** — Espace contrôleur externe, documents, FEC, RH, phyto, audit, lecture seule      |
| 24     |                                                                                                              |
| 25     |                                                                                                              |
| 26     |                                                                                                              |
| 27     |                                                                                                              |
| 28     |                                                                                                              |
| 29     |                                                                                                              |
| 30     |                                                                                                              |
