# Catégorie :  Vendeur (vente au détail sur site)

| **ID** | **Titre**                                              | **Description**                                                                                                                         | **Sprint** |
| ------ | ------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------- | ---------- |
| VE_01  | Créer une transaction de vente                         | Initier une vente en caisse : scanner ou rechercher les articles, ajouter au panier, sélectionner le client si compte existant          | 20         |
| VE_02  | Appliquer une remise pré-configurée                    | Appliquer une promotion active ou un avantage fidélité sur une transaction                                                              | 20         |
| VE_03  | Encaisser une vente                                    | Finaliser la transaction : mode de paiement (espèces, CB, chèque…), rendu monnaie, émission du ticket de caisse                         | 20         |
| VE_04  | Annuler une transaction en cours                       | Annuler une vente avant encaissement avec motif                                                                                         | 20         |
| VE_05  | Effectuer un remboursement                             | Rembourser une vente après encaissement (retour produit, erreur de caisse) avec motif et justificatif                                   | 20         |
| VE_06  | Consulter l'historique de ses transactions             | Accéder à l'historique des ventes et remboursements effectués sur sa caisse / session                                                   | 20         |
| VE_07  | Ouvrir / clôturer une session de caisse                | Démarrer une session de caisse avec fond de caisse initial et la clôturer avec comptage final et écart éventuel                         | 20         |
| VE_08  | Consulter le rapport de caisse de sa session           | Accéder au bilan de sa session : ventes, remboursements, modes de paiement, écart de caisse                                             | 20         |
| VE_09  | Consulter la fiche produit d'un article                | Accéder aux informations d'un végétal ou produit : description, entretien, prix, disponibilité, lot, DAR si applicable                  | 20         |
| VE_10  | Scanner un article / lot                               | Scanner le QR code ou code-barres d'un article pour accéder à sa fiche produit et son stock en temps réel                               | 20         |
| VE_11  | Rechercher un article dans le catalogue                | Rechercher un produit par nom, référence, variété, catégorie pour répondre à une question client                                        | 20         |
| VE_12  | Consulter la disponibilité d'un article sur le site    | Vérifier en temps réel la quantité disponible, l'emplacement physique et le statut (disponible / réservé / bloqué)                      | 20         |
| VE_13  | Créer un compte client                                 | Enregistrer un nouveau client particulier pour le programme de fidélité : nom, coordonnées, email, consentement RGPD                    | 20         |
| VE_14  | Consulter la fiche d'un client                         | Accéder au profil d'un client fidélité : solde de points, historique d'achats sur site, coordonnées                                     | 20         |
| VE_15  | Enregistrer un retour client                           | Saisir le retour d'un article : ticket d'origine, article, quantité, motif (insatisfaction, défaut, erreur…)                            | 20         |
| VE_16  | Traiter un retour conforme                             | Valider un retour article en bon état : remboursement ou avoir client + réintégration en stock                                          | 20         |
| VE_17  | Signaler un retour non conforme                        | Transmettre un retour article endommagé ou non conforme au contrôleur qualité pour décision                                             | 20         |
| VE_18  | Émettre un avoir client                                | Générer un avoir sur le compte client ou sous forme de bon d'achat suite à un retour validé                                             | 20         |
| VE_19  | Réceptionner une livraison en magasin                  | Saisir la réception de produits destinés à la vente : vérification du bon de livraison, quantités, état                                 | 20         |
| VE_20  | Enregistrer la mise en rayon                           | Confirmer le placement physique des articles en rayon avec emplacement                                                                  | 20         |
| VE_21  | Signaler une rupture de rayon                          | Alerter le gestionnaire de stock d'un épuisement d'un article en rayon alors que le stock théorique en indique                          | 20         |
| VE_22  | Signaler un article abîmé en rayon                     | Déclarer un article détérioré non vendable avec photo jointe                                                                            | 20         |
| VE_23  | Imprimer une étiquette prix                            | Générer et imprimer l'étiquette d'un article avec prix, référence, QR code                                                              | 20         |
| VE_24  | Signaler une erreur d'étiquetage                       | Déclarer une incohérence entre le prix affiché et le prix en caisse sur un article                                                      | 20         |
| VE_25  | Consulter les promotions actives sur le site           | Accéder à la liste des promotions en cours applicables sur le site courant                                                              | 20         |
| VE_26  | Créditer des points fidélité                           | Attribuer des points à un client suite à un achat (calcul automatique selon les règles du programme)                                    | 20         |
| VE_27  | Débiter des points fidélité                            | Utiliser des points accumulés pour une réduction sur une transaction                                                                    | 20         |
| VE_28  | Consulter le solde de points d'un client               | Afficher le solde de points fidélité d'un client identifié                                                                              | 20         |
| VE_29  | Corriger un solde de points                            | Ajuster manuellement le solde de points d'un client (oubli de crédit, erreur) avec motif obligatoire                                    | 20         |
| VE_30  | Consulter l'historique fidélité d'un client            | Accéder aux mouvements de points (crédits, débits, corrections) d'un client                                                             | 20         |
| VE_31  | Consulter ses statistiques de vente                    | Visualiser ses propres indicateurs : CA réalisé, nombre de transactions, panier moyen, taux de retour, points fidélité distribués       | 20         |
|        | ------------------------------------------------------ | ------------------------------------------------------- Heritage ---------------------------------------------------------------------- |            |
| VE_32  | consulter son planning                                 | Voir son planning : jours travaillés, congés, absences, horaires                                                                        | 2          |  
| VE_33  | Consulter les consignes du jour                        | Visualiser les tâches et instructions assignées par la hiérarchie pour la journée                                                       | 2          |
| VE_34  | signaler une absence/retard                            | Informer la hiérarchie d'un empêchement avec motif et durée estimée                                                                     | 3          |
| VE_35  | Signaler un accident du travail                        | Déclarer un accident survenu pendant le temps de travail, avec description et horodatage                                                | 3          |
| VE_36  | poser des congés                                       | Soumettre une demande de congés pour validation par la hiérarchie                                                                       | 3          |
| VE_37  | modifier des congés                                    | Modifier une demande de congés non encore validée                                                                                       | 3          |
| VE_38  | Annuler des congés                                     | Annuler une demande de congés non encore validée                                                                                        | 3          |
| VE_39  | Consulter ses bulletins de paie                        | Accéder à ses bulletins de salaire mensuels en lecture seule                                                                            | 3          |
| VE_40  | voir ses informations personelles                      | Visualiser ses données personnelles (coordonnées, contrat, poste…)                                                                      | 3          |
| VE_41  | modifier ses informations personelles                  | Mettre à jour certaines informations personnelles (adresse, téléphone…) soumises à validation RH                                        | 3          |
| VE_42  | envoyer un message                                     | Envoyer un message via la messagerie interne à un collègue ou groupe                                                                    | 6          |
| VE_43  | modifier un message                                    | Modifier un message envoyé (dans un délai limité défini par l'admin)                                                                    | 6          |
| VE_44  | supprimer un message                                   | Supprimer un message envoyé (dans un délai limité défini par l'admin)                                                                   | 6          |
| VE_45  | Consulter ses notifications                            | Voir les notifications reçues (tâche assignée, message, validation congé…) et les marquer comme lues                                    | 2          |
| VE_46  | Scanner un lot / une plante                            | Scanner un QR code ou code-barres pour identifier un lot ou une plante et accéder à ses informations                                    | 4          |
| VE_47  | Consulter une fiche de culture                         | Visualiser la fiche de culture d'une plante pour connaître les soins, stade, particularités                                             | 4          |
| VE_48  | Consulter une fiche de sécurité produit                | Accéder aux fiches MSDS / FDS des produits phytosanitaires ou engrais utilisés                                                          | 4          |
| VE_49  | remplir une feuille d'activité                         | Saisir le compte-rendu d'une tâche réalisée (type, durée, quantité, localisation…)                                                      | 4          |
| VE_50  | modifier une feuille d'activité                        | Corriger une feuille d'activité soumise (dans un délai limité, soumis à validation)                                                     | 4          |
| VE_51  | consulter sa productivité                              | Visualiser ses performances : tâches réalisées, volumes, comparatif période, par secteur                                                | 4          |
| VE_52  | remplir un probleme technique                          | Déclarer un dysfonctionnement matériel ou d'infrastructure avec description et localisation                                             | 5          |
| VE_53  | modifier un probleme technique                         | Corriger ou compléter un problème technique tant qu'il n'est pas pris en charge                                                         | 5          |
| VE_54  | remplir une maladie/ravageur                           | Déclarer l'observation d'une maladie ou d'un ravageur sur un lot avec localisation et description                                       | 5          |
| VE_55  | modifier une maladie/ravageur                          | Corriger un signalement soumis tant qu'il n'est pas traité                                                                              | 5          |


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
