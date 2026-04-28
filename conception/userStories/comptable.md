# Catégorie : Comptable


| **ID** | **Titre**                                              | **Description**                                                                                                                         | **Sprint** |
| ------ | ------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------- | ---------- |
| COM_01 | Consulter les factures clients en attente de règlement | Accéder à la liste des factures émises non encore réglées, filtrables par client, montant, échéance, entité juridique                   | 16         |
| COM_02 | Enregistrer un encaissement client                     | Saisir le règlement d'une facture client : montant, mode de paiement, date de valeur, référence bancaire                                | 16         |
| COM_03 | Enregistrer un encaissement partiel                    | Saisir un règlement partiel avec montant reçu et solde restant dû                                                                       | 16         |
| COM_04 | Émettre une relance client                             | Envoyer une relance de paiement (manuelle ou depuis un workflow automatique) avec récapitulatif des factures impayées                   | 16         |
| COM_05 | Consulter les impayés                                  | Visualiser les factures impayées par client, par entité, par ancienneté (0-30j, 30-60j, 60-90j, >90j)                                   | 16         |
| COM_06 | Créer un avoir client                                  | Générer un avoir sur une facture client (retour, erreur de facturation, litige) avec motif obligatoire                                  | 16         |
| COM_07 | Consulter les factures fournisseurs à régler           | Accéder à la liste des factures fournisseurs reçues en attente de paiement, filtrables par fournisseur, échéance, entité                | 16         |
| COM_08 | Valider une facture fournisseur                        | Contrôler et approuver une facture fournisseur avant paiement (conformité bon de commande, montant, TVA)                                | 16         |
| COM_09 | Enregistrer un paiement fournisseur                    | Saisir le règlement d'une facture fournisseur : montant, mode, date, référence bancaire                                                 | 16         |
| COM_10 | Créer un avoir fournisseur                             | Enregistrer un avoir reçu d'un fournisseur (retour, litige, erreur de facturation)                                                      | 16         |
| COM_11 | Consulter l'échéancier fournisseurs                    | Visualiser les paiements fournisseurs à venir sur une période donnée pour anticiper la trésorerie                                       | 16         |
| COM_12 | Importer un relevé bancaire                            | Importer un relevé bancaire (CSV, OFX, QIF) pour rapprochement avec les écritures comptables                                            | 16         |
| COM_13 | Effectuer un rapprochement bancaire                    | Associer manuellement les lignes de relevé non rapprochées automatiquement aux écritures comptables correspondantes                     | 16         |
| COM_14 | Valider un rapprochement bancaire                      | Clôturer un rapprochement bancaire pour une période donnée                                                                              | 16         |
| COM_15 | Consulter l'historique des rapprochements              | Accéder aux rapprochements bancaires passés par compte, par période, par entité juridique                                               | 16         |
| COM_16 | Consulter la trésorerie en temps réel                  | Visualiser les soldes bancaires consolidés par compte et par entité juridique                                                           | 16         |
| COM_17 | Consulter les données de TVA collectée                 | Visualiser la TVA collectée sur les ventes par période et par entité juridique                                                          | 16         |
| COM_18 | Consulter les données de TVA déductible                | Visualiser la TVA déductible sur les achats par période et par entité juridique                                                         | 16         |
| COM_19 | Préparer une déclaration de TVA                        | Générer le récapitulatif de TVA (CA3 / CA12) pour une période donnée à partir des données du système                                    | 16         |
| COM_20 | Valider une déclaration de TVA                         | Confirmer la déclaration de TVA avant transmission à l'administration fiscale                                                           | 16         |
| COM_21 | Archiver une déclaration de TVA                        | Archiver la déclaration soumise avec justificatifs joints (non supprimable — durée légale de conservation)                              | 16         |
| COM_22 | Préparer une clôture mensuelle                         | Vérifier les écritures du mois, lettrer les comptes, identifier les écarts avant clôture                                                | 16         |
| COM_23 | Valider une clôture mensuelle                          | Verrouiller la période mensuelle — aucune écriture ne peut plus être modifiée sur cette période                                         | 16         |
| COM_24 | Préparer une clôture annuelle                          | Générer les états de synthèse (bilan, compte de résultat) à partir des données de l'exercice                                            | 16         |
| COM_25 | Valider une clôture annuelle                           | Verrouiller l'exercice comptable annuel                                                                                                 | 16         |
| COM_26 | Consulter les journaux comptables                      | Accéder aux journaux des écritures (achats, ventes, banque, OD) par période et par entité juridique                                     | 16         |
| COM_27 | Saisir une écriture comptable manuelle                 | Enregistrer une opération diverse (OD) : régularisation, provision, correction d'écriture                                               | 16         |
| COM_28 | Exporter les écritures vers logiciel externe           | Générer un fichier d'export (FEC, CSV, format Sage / EBP / Cegid…) des écritures comptables sur une période                             | 16         |
| COM_29 | Exporter les données de paie                           | Extraire les données de paie (masse salariale, charges) à destination du logiciel de paie ou du cabinet externe                         | 16         |
| COM_30 | Exporter le FEC (Fichier des Écritures Comptables)     | Générer le FEC réglementaire pour une entité juridique et un exercice donné, prêt pour contrôle fiscal                                  | 16         |
| COM_31 | Consulter l'historique des exports                     | Accéder aux exports générés : date, type, période, entité, utilisateur                                                                  | 16         |
| COM_32 | Consulter le tableau de bord financier                 | Visualiser les indicateurs clés : CA, marge, trésorerie, impayés, charges, par entité et par période                                    | 16         |
| COM_33 | Consulter les états de synthèse                        | Accéder au bilan et compte de résultat provisoires ou définitifs par entité et par exercice                                             | 16         |
| COM_34 | Générer un rapport financier                           | Produire un rapport financier personnalisé (période, entité, indicateurs) à destination de la direction                                 | 16         |
|        | ------------------------------------------------------ | ------------------------------------------------------- Heritage ---------------------------------------------------------------------- |            |
| COM_35 | consulter son planning                                 | Voir son planning : jours travaillés, congés, absences, horaires                                                                        | 2          |
| COM_36 | Consulter les consignes du jour                        | Visualiser les tâches et instructions assignées par la hiérarchie pour la journée                                                       | 2          |
| COM_37 | signaler une absence/retard                            | Informer la hiérarchie d'un empêchement avec motif et durée estimée                                                                     | 3          |
| COM_38 | Signaler un accident du travail                        | Déclarer un accident survenu pendant le temps de travail, avec description et horodatage                                                | 3          |
| COM_39 | poser des congés                                       | Soumettre une demande de congés pour validation par la hiérarchie                                                                       | 3          |
| COM_40 | modifier des congés                                    | Modifier une demande de congés non encore validée                                                                                       | 3          |
| COM_41 | Annuler des congés                                     | Annuler une demande de congés non encore validée                                                                                        | 3          |
| COM_42 | Consulter ses bulletins de paie                        | Accéder à ses bulletins de salaire mensuels en lecture seule                                                                            | 3          |
| COM_43 | voir ses informations personelles                      | Visualiser ses données personnelles (coordonnées, contrat, poste…)                                                                      | 3          |
| COM_44 | modifier ses informations personelles                  | Mettre à jour certaines informations personnelles (adresse, téléphone…) soumises à validation RH                                        | 3          |
| COM_45 | envoyer un message                                     | Envoyer un message via la messagerie interne à un collègue ou groupe                                                                    | 6          |
| COM_46 | modifier un message                                    | Modifier un message envoyé (dans un délai limité défini par l'admin)                                                                    | 6          |
| COM_47 | supprimer un message                                   | Supprimer un message envoyé (dans un délai limité défini par l'admin)                                                                   | 6          |
| COM_48 | Consulter ses notifications                            | Voir les notifications reçues (tâche assignée, message, validation congé…) et les marquer comme lues                                    | 2          |
| COM_49 | Scanner un lot / une plante                            | Scanner un QR code ou code-barres pour identifier un lot ou une plante et accéder à ses informations                                    | 4          |
| COM_50 | Consulter une fiche de culture                         | Visualiser la fiche de culture d'une plante pour connaître les soins, stade, particularités                                             | 4          |
| COM_51 | Consulter une fiche de sécurité produit                | Accéder aux fiches MSDS / FDS des produits phytosanitaires ou engrais utilisés                                                          | 4          |
| COM_52 | remplir une feuille d'activité                         | Saisir le compte-rendu d'une tâche réalisée (type, durée, quantité, localisation…)                                                      | 4          |
| COM_53 | modifier une feuille d'activité                        | Corriger une feuille d'activité soumise (dans un délai limité, soumis à validation)                                                     | 4          |
| COM_54 | consulter sa productivité                              | Visualiser ses performances : tâches réalisées, volumes, comparatif période, par secteur                                                | 4          |
| COM_55 | remplir un probleme technique                          | Déclarer un dysfonctionnement matériel ou d'infrastructure avec description et localisation                                             | 5          |
| COM_56 | modifier un probleme technique                         | Corriger ou compléter un problème technique tant qu'il n'est pas pris en charge                                                         | 5          |
| COM_57 | remplir une maladie/ravageur                           | Déclarer l'observation d'une maladie ou d'un ravageur sur un lot avec localisation et description                                       | 5          |
| COM_58 | modifier une maladie/ravageur                          | Corriger un signalement soumis tant qu'il n'est pas traité                                                                              | 5          |



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
| 16     |                                                                                                              |
| 17     |                                                                                                              |
| 18     |                                                                                                              |
| 19     |                                                                                                              |
| 20     |                                                                                                              |
