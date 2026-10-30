# Modules Dolibarr MMI

[English](README.md) · **Français**

Modules Dolibarr open source de **Mathieu Moulin / iProspective** (MMI), publiés sur GitHub.
IDs de modules **437800–437826** (l'ID 437817 n'est pas publié).

Tous les modules MMI dépendent de **MMICommon**, qui doit être activé en premier.

## Modules

| Module | ID | Version | Description | Dépend de |
|---|---:|---|---|---|
| [MMICommon](https://github.com/lemathou/dolibarr-module-mmicommon) | 437800 | 1.2 | Socle commun de tous les modules MMI : renderer de configuration, page « à propos », composants de page d'accueil, helpers, classes utilitaires et triggers communs. | — |
| [MMIAtelier](https://github.com/lemathou/dolibarr-module-mmiatelier) | 437801 | 1.0 | Gestion d'atelier : ordres de fabrication, planning et suivi des postes de travail. | mmicommon |
| [MMIAvisVerifies](https://github.com/lemathou/dolibarr-module-mmiavisverifies) | 437802 | 1.0 | Connecteur Avis Vérifiés (NetReviews) : collecte et export des avis clients. | mmicommon |
| [MMICompta](https://github.com/lemathou/dolibarr-module-mmicompta) | 437803 | 1.0 | Compléments de comptabilité : produits constatés d'avance (PCA), export comptable, correction des factures payées et gestion des acomptes. | mmicommon |
| [MMICRM](https://github.com/lemathou/dolibarr-module-mmicrm) | 437804 | 1.2.1 | CRM : suivi clients, relances, fidélité, campagnes produits, commentaires de factures/commandes et liens courts. | mmicommon |
| [MMIDocuments](https://github.com/lemathou/dolibarr-module-mmidocuments) | 437805 | 1.2.0 | Améliorations des documents et PDF/ODT : champs complémentaires, options d'impression, documents d'expédition, factures de situation, renommage des PDF et mentions d'exonération de TVA. | mmicommon |
| [MMIEntrepots](https://github.com/lemathou/dolibarr-module-mmientrepots) | 437806 | 1.1 | Gestion des emplacements dans les entrepôts (pour l'instant sur les produits) et outils de stock associés. | mmicommon, categorie |
| [MMIFilters](https://github.com/lemathou/dolibarr-module-mmifilters) | 437807 | 1.1 | Filtres de listes et actions de masse sur les devis, commandes, factures et expéditions. | mmicommon |
| [MMIFournisseurPrice](https://github.com/lemathou/dolibarr-module-mmifournisseurprice) | 437808 | 1.0 | Prix fournisseurs : tarifs, historiques, comparaison et prix de revient incluant le transport. | mmicommon, mmishipping, mmiproduct, product, fournisseur, reception |
| [MMIPayments](https://github.com/lemathou/dolibarr-module-mmipayments) | 437809 | 1.5 | Hub de paiements : onglet Paiements sur les tiers, devis, commandes et factures, liste globale des paiements, liens de paiement et API d'extension pour les modules de paiement. | mmicommon |
| [MMIPrestaSync](https://github.com/lemathou/dolibarr-module-mmiprestasync) | 437810 | 1.1.0 | Synchronisation PrestaShop ↔ Dolibarr : produits, clients, adresses, commandes, factures, paiements et stocks. | mmicommon, mmiproduct, mmifournisseurprice, mmipayments, mmiworkflow |
| [MMIProduct](https://github.com/lemathou/dolibarr-module-mmiproduct) | 437811 | 1.1.2 | Gestion produit avancée : calcul de prix et de marge, empilement des coûts, veille concurrentielle, réapprovisionnement, stock et inventaire, API REST. | mmicommon, product |
| [MMIProductDluo](https://github.com/lemathou/dolibarr-module-mmiproductdluo) | 437812 | 1.0 | Gestion DLUO/DLC et des lots : sélection de lots, antigaspi, stock composé, prix par bande et picking. | mmicommon, productbatch, mmiproduct |
| [MMIProject](https://github.com/lemathou/dolibarr-module-mmiproject) | 437813 | 1.0.3 | Gestion de projets : suivi du temps, rentabilité, chantiers BTP/atelier et saisie simplifiée des temps. | mmicommon, projet |
| [MMIStats](https://github.com/lemathou/dolibarr-module-mmistats) | 437814 | 1.0.1 | Tableaux de bord et statistiques pour les commerciaux, les produits et les marges. | mmicommon |
| [MMIVATEEC](https://github.com/lemathou/dolibarr-module-mmivateec) | 437815 | 1.0 | Gestion de la TVA et de l'éco-participation pour les ventes B2C intracommunautaires. | mmicommon |
| [MMIWorkflow](https://github.com/lemathou/dolibarr-module-mmiworkflow) | 437816 | 1.3.0 | Automatisation du workflow de vente : facture et expédition en 1 clic, réouverture en brouillon, suivi expéditions/réceptions, raccourcis e-mail et endpoint REST. | mmicommon, mmipayments |
| [MMIShipping](https://github.com/lemathou/dolibarr-module-mmishipping) | 437818 | 1.1 | Expéditions et réceptions avancées : affectation du destinataire DF, flux directs entrepôt, autoliquidation port/TVA, analyse des coûts transporteur et hooks PDF. | mmicommon, product, fournisseur, expedition, reception |
| [MMISecurity](https://github.com/lemathou/dolibarr-module-mmisecurity) | 437819 | 1.0 | Durcissement de la sécurité : filtrage par liste d'IP autorisées pour les utilisateurs non privilégiés. | mmicommon |
| [MMIRedmine](https://github.com/lemathou/dolibarr-module-mmiredmine) | 437820 | 1.0 | Synchronisation Redmine des projets, tickets et temps passés. | mmicommon, projet |
| [MMIGED](https://github.com/lemathou/dolibarr-module-mmiged) | 437821 | 1.0 | Gestion électronique des documents : rattachement aux fournisseurs, liens avec les produits et envoi par e-mail aux clients. | mmicommon, ecm |
| [MMISAV](https://github.com/lemathou/dolibarr-module-mmisav) | 437822 | 1.0 | SAV par tickets : interventions, retours et communication fournisseur/client. | mmicommon, ticket |
| [MMIWildx](https://github.com/lemathou/dolibarr-module-mmiwildx) | 437823 | 1.0 | Connecteur de téléphonie WildX : récupération de l'historique des appels dans l'agenda et l'historique. | mmicommon |
| [MMIBrevo](https://github.com/lemathou/dolibarr-module-mmibrevo) | 437824 | 1.1 | Connecteur Brevo : campagnes e-mail/SMS, contacts et statistiques. | mmicommon |
| [MMIYounited](https://github.com/lemathou/dolibarr-module-mmiyounited) | 437825 | 1.1.3 | Financement Younited Pay : création de prêt/paiement, offres, redirections, webhook et suivi des statuts. | mmicommon, mmipayments |
| [MBIETransactions](https://github.com/lemathou/dolibarr-module-mbietransactions) | 437826 | 1.3.0 | Paiement CB Monetico (MBE) / Up2Pay : page de paiement, pages de retour, rapprochement et intégration à l'onglet Paiements. Fork du module MBE Transactions d'origine. | mmicommon, mmipayments |

## Détail des modules

### [MMICommon](https://github.com/lemathou/dolibarr-module-mmicommon)
**ID 437800** · **v1.2** · Dépend de : —

Socle commun de tous les modules MMI : renderer de configuration, page « à propos », composants de page d'accueil, helpers, classes utilitaires et triggers communs.

- Renderer de configuration partagé, secrets masqués et bouton « Révéler »
- Composants de page d'accueil MMI (header/footer/links/block)
- Helpers prix, dates et statistiques
- Triggers communs, onglets produit/projet et actions de commentaires

### [MMIAtelier](https://github.com/lemathou/dolibarr-module-mmiatelier)
**ID 437801** · **v1.0** · Dépend de : mmicommon

Gestion d'atelier : ordres de fabrication, planning et suivi des postes de travail.

- Ordres de fabrication
- Planning et suivi des postes
- Menus et configuration atelier

### [MMIAvisVerifies](https://github.com/lemathou/dolibarr-module-mmiavisverifies)
**ID 437802** · **v1.0** · Dépend de : mmicommon

Connecteur Avis Vérifiés (NetReviews) : collecte et export des avis clients.

- Collecte et export FTP des avis clients (prod/test)
- Cron de envoi planifié
- Configuration FTP et suivi des envois

### [MMICompta](https://github.com/lemathou/dolibarr-module-mmicompta)
**ID 437803** · **v1.0** · Dépend de : mmicommon

Compléments de comptabilité : produits constatés d'avance (PCA), export comptable, correction des factures payées et gestion des acomptes.

- Calcul et suivi des produits constatés d'avance (PCA)
- Export comptable avec options de libellé de compte
- Correction des factures payées (statut/encaissement)
- Gestion de la TVA des acomptes

### [MMICRM](https://github.com/lemathou/dolibarr-module-mmicrm)
**ID 437804** · **v1.2.1** · Dépend de : mmicommon

CRM : suivi clients, relances, fidélité, campagnes produits, commentaires de factures/commandes et liens courts.

- Relances clients et fidélité
- Campagnes produits et templates de messages
- Commentaires de factures et de commandes
- Liens courts et pages clients/commandes

### [MMIDocuments](https://github.com/lemathou/dolibarr-module-mmidocuments)
**ID 437805** · **v1.2.0** · Dépend de : mmicommon

Améliorations des documents et PDF/ODT : champs complémentaires, options d'impression, documents d'expédition, factures de situation, renommage des PDF et mentions d'exonération de TVA.

- Champs complémentaires documents (acompte, CGV/CPV, réf. ligne/produit/fournisseur, SIRET…)
- Options d'affichage et de colonnes PDF/ODT
- Options des documents d'expédition (poids, lot, date, images, message)
- Factures de situation et renommage configurable des PDF
- Mentions d'exonération de TVA selon le tiers et le contexte

### [MMIEntrepots](https://github.com/lemathou/dolibarr-module-mmientrepots)
**ID 437806** · **v1.1** · Dépend de : mmicommon, categorie

Gestion des emplacements dans les entrepôts (pour l'instant sur les produits) et outils de stock associés.

- Emplacements de stockage par produit
- Outils d'inventaire et de base
- Affichage dans les PDF d'expédition
- Menus et configuration entrepôts

### [MMIFilters](https://github.com/lemathou/dolibarr-module-mmifilters)
**ID 437807** · **v1.1** · Dépend de : mmicommon

Filtres de listes et actions de masse sur les devis, commandes, factures et expéditions.

- Assignation en masse d'un commercial
- Filtres de listes supplémentaires
- Test fonctionnel du filtre expédition

### [MMIFournisseurPrice](https://github.com/lemathou/dolibarr-module-mmifournisseurprice)
**ID 437808** · **v1.0** · Dépend de : mmicommon, mmishipping, mmiproduct, product, fournisseur, reception

Prix fournisseurs : tarifs, historiques, comparaison et prix de revient incluant le transport.

- Tarifs fournisseurs et historiques
- Comparaison des prix
- Prix de revient incluant les frais de transport
- Hooks de la fiche prix fournisseur

### [MMIPayments](https://github.com/lemathou/dolibarr-module-mmipayments)
**ID 437809** · **v1.5** · Dépend de : mmicommon

Hub de paiements : onglet Paiements sur les tiers, devis, commandes et factures, liste globale des paiements, liens de paiement et API d'extension pour les modules de paiement.

- Onglet Paiements unifié et liste globale des paiements
- Distingue les encaissements des tentatives de paiement
- Hooks d'extension pour que chaque module de paiement contribue ses lignes
- Liens de paiement sécurisés sur devis et commandes
- Informations chèque et virement sur la page de paiement

### [MMIPrestaSync](https://github.com/lemathou/dolibarr-module-mmiprestasync)
**ID 437810** · **v1.1.0** · Dépend de : mmicommon, mmiproduct, mmifournisseurprice, mmipayments, mmiworkflow

Synchronisation PrestaShop ↔ Dolibarr : produits, clients, adresses, commandes, factures, paiements et stocks.

- Produits, clients, adresses, commandes, factures, paiements et stocks
- Web service authentifié et resynchronisation manuelle
- File de synchronisation et résilience
- Types d'objets synchronisés configurables

### [MMIProduct](https://github.com/lemathou/dolibarr-module-mmiproduct)
**ID 437811** · **v1.1.2** · Dépend de : mmicommon, product

Gestion produit avancée : calcul de prix et de marge, empilement des coûts, veille concurrentielle, réapprovisionnement, stock et inventaire, API REST.

- Onglet de calcul de prix et de marge
- Empilement du prix de revient (logistique, emballage, transport, divers)
- Veille concurrentielle
- Réapprovisionnement avec EOQ et niveau de service
- Régularisation de stock, mise à jour d'inventaire et API REST

### [MMIProductDluo](https://github.com/lemathou/dolibarr-module-mmiproductdluo)
**ID 437812** · **v1.0** · Dépend de : mmicommon, productbatch, mmiproduct

Gestion DLUO/DLC et des lots : sélection de lots, antigaspi, stock composé, prix par bande et picking.

- Dates DLUO/DLC et sélecteur de lots
- Gestion antigaspi
- Stock composé
- Prix par bande et picking
- API dédiée

### [MMIProject](https://github.com/lemathou/dolibarr-module-mmiproject)
**ID 437813** · **v1.0.3** · Dépend de : mmicommon, projet

Gestion de projets : suivi du temps, rentabilité, chantiers BTP/atelier et saisie simplifiée des temps.

- Saisie du temps et récapitulatif mensuel
- Planning de chantiers
- Contrats de travail
- Rentabilité et statistiques
- Catégories de ressources

### [MMIStats](https://github.com/lemathou/dolibarr-module-mmistats)
**ID 437814** · **v1.0.1** · Dépend de : mmicommon

Tableaux de bord et statistiques pour les commerciaux, les produits et les marges.

- Tableau de bord commerciaux
- Tableau de bord produits
- Analyse des marges et indicateurs

### [MMIVATEEC](https://github.com/lemathou/dolibarr-module-mmivateec)
**ID 437815** · **v1.0** · Dépend de : mmicommon

Gestion de la TVA et de l'éco-participation pour les ventes B2C intracommunautaires.

- TVA B2C intracommunautaire
- Hooks de contrôle VIES
- Gestion de l'éco-participation
- Historique de TVA

### [MMIWorkflow](https://github.com/lemathou/dolibarr-module-mmiworkflow)
**ID 437816** · **v1.3.0** · Dépend de : mmicommon, mmipayments

Automatisation du workflow de vente : facture et expédition en 1 clic, réouverture en brouillon, suivi expéditions/réceptions, raccourcis e-mail et endpoint REST.

- Facture et expédition en 1 clic (avec picking automatique des lots)
- Facturation différée et envoi automatique de la facture
- Réouverture en brouillon des commandes expédiées et factures payées
- Suivi expéditions/réceptions via extrafields
- Endpoint REST pour la création d'expédition externe

### [MMIShipping](https://github.com/lemathou/dolibarr-module-mmishipping)
**ID 437818** · **v1.1** · Dépend de : mmicommon, product, fournisseur, expedition, reception

Expéditions et réceptions avancées : affectation du destinataire DF, flux directs entrepôt, autoliquidation port/TVA, analyse des coûts transporteur et hooks PDF.

- Affectation du destinataire DF et réception/envoi direct entrepôt
- Édition du port et autoliquidation de TVA sur commandes fournisseur
- Analyse des coûts transporteur par import CSV
- Hooks PDF expédition/réception (tri, adresse de réception)
- Outil de correction d'autoliquidation

### [MMISecurity](https://github.com/lemathou/dolibarr-module-mmisecurity)
**ID 437819** · **v1.0** · Dépend de : mmicommon

Durcissement de la sécurité : filtrage par liste d'IP autorisées pour les utilisateurs non privilégiés.

- Filtrage des accès par IP
- Plages autorisées configurables
- Hooks login et main
- Page de configuration dédiée

### [MMIRedmine](https://github.com/lemathou/dolibarr-module-mmiredmine)
**ID 437820** · **v1.0** · Dépend de : mmicommon, projet

Synchronisation Redmine des projets, tickets et temps passés.

- Synchronisation des projets et tickets
- Temps passés
- Mapping utilisateurs et produits
- Pages de synchronisation manuelle

### [MMIGED](https://github.com/lemathou/dolibarr-module-mmiged)
**ID 437821** · **v1.0** · Dépend de : mmicommon, ecm

Gestion électronique des documents : rattachement aux fournisseurs, liens avec les produits et envoi par e-mail aux clients.

- Intégration GED/ECM
- Rattachement des documents fournisseurs
- Liens avec les produits
- Envoi des documents aux clients par e-mail

### [MMISAV](https://github.com/lemathou/dolibarr-module-mmisav)
**ID 437822** · **v1.0** · Dépend de : mmicommon, ticket

SAV par tickets : interventions, retours et communication fournisseur/client.

- Tickets SAV
- Interventions et retours
- Communication fournisseur/client
- Triggers dédiés

### [MMIWildx](https://github.com/lemathou/dolibarr-module-mmiwildx)
**ID 437823** · **v1.0** · Dépend de : mmicommon

Connecteur de téléphonie WildX : récupération de l'historique des appels dans l'agenda et l'historique.

- Récupération de l'historique des appels
- Intégration agenda/historique
- Classe de synchronisation
- Configuration du connecteur

### [MMIBrevo](https://github.com/lemathou/dolibarr-module-mmibrevo)
**ID 437824** · **v1.1** · Dépend de : mmicommon

Connecteur Brevo : campagnes e-mail/SMS, contacts et statistiques.

- Envoi de SMS depuis devis, commandes, factures et tiers
- Campagnes et contacts
- Statistiques
- Configuration de l'API Brevo

### [MMIYounited](https://github.com/lemathou/dolibarr-module-mmiyounited)
**ID 437825** · **v1.1.3** · Dépend de : mmicommon, mmipayments

Financement Younited Pay : création de prêt/paiement, offres, redirections, webhook et suivi des statuts.

- Création de prêt/paiement et offres via l'API Younited
- Configuration sandbox/production
- Webhook avec re-interrogation du statut côté serveur
- Pages de retour client
- Suivi des maturités

### [MBIETransactions](https://github.com/lemathou/dolibarr-module-mbietransactions)
**ID 437826** · **v1.3.0** · Dépend de : mmicommon, mmipayments

Paiement CB Monetico (MBE) / Up2Pay : page de paiement, pages de retour, rapprochement et intégration à l'onglet Paiements. Fork du module MBE Transactions d'origine.

- Page de paiement Monetico
- Pages accepté, annulé, refusé et retour
- Journal des retours et rapprochement
- Onglet Paiements et liens de paiement sécurisés
- Triggers e-mail et hooks facture/commande/devis


## Fork Dolibarr MMI

Les modules sont développés avec le fork Dolibarr MMI :
<https://github.com/lemathou/dolibarr>

Branches publiées : `14.0-mmi`, `16.0-mmi`, `17.0-mmi`, `18.0-mmi`, `19.0-mmi`
(fork de production actuel) et `20.0-mmi-merge` (migration vers Dolibarr 20).

## Licence

Chaque module est distribué sous GNU GPL v3 ou ultérieure (voir le fichier `COPYING`
du dépôt) ; la documentation est sous GFDL. Certains modules nécessitent également des
modifications du cœur fournies par le fork MMI.
