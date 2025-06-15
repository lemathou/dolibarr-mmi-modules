# Dolibarr Modules List - by MMI alias Mathieu Moulin iProspective

List by Dolibarr Module ID

https://wiki.dolibarr.org/index.php?title=List_of_modules_id

ID 437800 - 437850: iProspective (https://iprospective.fr) - Mathieu Moulin

## Dolibarr-MMI
* Repos : https://github.com/lemathou/dolibarr
* Branches : 14.0-mmi, 15.0-mmi, 16.0-mmi, 17.0-mmi, 18.0-mmi, 19.0-mmi

My Dolibarr Fork, with adjustemts for some of my modules.

I will soon publish the list, and take the time to propose fixes and features in the Core.

## MMICommon
* Num 437800
* Repos : https://github.com/lemathou/dolibarr-module-mmicommon
* Status : OK
* Production : Yes
* Uses :  inHooks

Base module for all my MMI Dolibarr modules

### Features :
* Base classes overloaded
* Déclencher le trigger de mise à jour de l'objet lorsqu'on met à jour une note
* Afficher un picto warning sur les liens client si on a une note privée, et l'afficher dans la popup 

## MMIAtelier
* Num 437801
* Repos : https://github.com/lemathou/dolibarr-module-mmiatelier
* Status : Alpha, Paused
* Production : No

Used to simplify usage of workstations, resources...

## MMIAvisVerifies
* Num 437802
* Repos : https://github.com/lemathou/dolibarr-module-mmiavisverifies
* Status : Beta, Paused
* Production : No

Connector to NetReviews (formerly Avis Vérifiés)

## MMICompta
* Num 437803
* Repos : https://github.com/lemathou/dolibarr-module-mmicompta
* Status : OK
* Version : 1.0

Options on accounting exports an numbers

## MMICRM
* Num 437804
* Repos : https://github.com/lemathou/dolibarr-module-mmicrm
* Status : OK
* Version : 1.0

Summary CRM page to simplify customers follow-up

## MMIDocuments
* Num 437805
* Repos : https://github.com/lemathou/dolibarr-module-mmidocuments
* Status : OK
* Version : 1.0
* Dict

Lots of Enhancements in documents templates

### Features :
* Situation invoices
* Hide refs
* Rename PDF using customer name, etc.
* Affichage des mentions d'exoneration de TVA
* etc.

## MMIEntrepots
* Num 437806
* Repos : https://github.com/lemathou/dolibarr-module-mmientrepots
* Status : OK, few options
* Version : 1.0

Gestion d'emplacements dans les entrepôts, avec affichage dans les PDF d'expédition

## MMIFilters
* Num 437807
* Repos : https://github.com/lemathou/dolibarr-module-mmifilters
* Status : OK

New filters

## MMIFournisseurPrice
* Num 437808
* Repos : https://github.com/lemathou/dolibarr-module-mmifournisseurprice

### Features :
* Calculation of cost price with shipping cost price and other.
* Shipping cost price can be automatically calculated using shipping in recent supplier orders.

## MMIPayments
* Num 437809
* Repos : https://github.com/lemathou/dolibarr-module-mmipayments

Enhance global payment capabilities

### Features :
* Possibiilté de paiement sur les Devis/Commandes
* Affiche des moyens de paiements Chèque et Virement avec les infos sur la page de paiement.
* Ajout des liens de paiement sur les propales et commandes.

## MMIPrestaSync
* Num 437810
* Repos : https://github.com/lemathou/dolibarr-module-mmiprestasync
* Status : OK in production

Synchronisation with Prestashop, using a free open source Middleware

## MMIProduct
* Num 437811
* Repos : https://github.com/lemathou/dolibarr-module-mmiproduct

Enhance products management

## MMIProductDluo
* Num 437812
* Repos : https://github.com/lemathou/dolibarr-module-mmiproductdluo
* Version : 1.0

Enhance products with DLC/DMD management

## MMIProject
* Num 437813
* Repos : https://github.com/lemathou/dolibarr-module-mmiproject
* Status : OK
* Version : 1.0
* Dict, Const, classes, hooks, menu, etc.

### Features :
* Projets pour les chantiers BTP
* Gestion des heures des salariés en modulation du temps de travail avec interface simplifiée pour la saisie du temps sur les tâches de chantiers, tableau récapitulatif des heures effctuées, prévisionnel, etc.

## MMIStats
* Num 437814
* Repos : https://github.com/lemathou/dolibarr-module-mmistats
* Version : 1.0

Features :
* Statistiques commerciaux

## MMIVATEEC
* Num 437815
* Repos : https://github.com/lemathou/dolibarr-module-mmivateec
* Status : OK, few options
* Version : 1.0

Fixtures for VAT in EEC

## MMIWorkflow
* Num 437816
* Repos : https://github.com/lemathou/dolibarr-module-mmiworkflow
* Status : OK
* Version : 1.0

Modification des workflows pour automatiser et réduire les actions manuelles

## MMIShipping
* Num 437818
* Repos : https://github.com/lemathou/dolibarr-module-mmishipping
* Version : 1.0

Advanced shipping options for Dolibarr

### Features :
* Automatic management of direct receipts/shipments from the supplier warehouse using a "virtual" warehouse for direct delivery
* Other useful options

## MMISecurity
* Num 437819
* Repos : https://github.com/lemathou/dolibarr-module-mmisecurity
* Version : 1.0

Security features for Dolibarr

### Features :
* Limitation for non priviliged users by a list of privileged IP Addresses

## MMIRedmine
* Num 437820
* Repos : https://github.com/lemathou/dolibarr-module-mmiredmine
* Version : 1.0
* Status : Bêta

Synchronisation of Redmine Projects, Tasks an Time spent in Dolibarr, with usage of users and associated products.

## MMIGED
* Num 437821
* https://github.com/lemathou/dolibarr-module-mmiged
* Status : Alpha

Attach documents from GED to suppliers, link them to products and send them by email to customers.

## MMISAV
* Num 437822
* https://github.com/lemathou/dolibarr-module-mmisav
* Status : Paused

Gestion du SAV par tickets avec communication fournisseur/client

## MMIWildx
* Num 437823
* https://github.com/lemathou/dolibarr-module-mmiwildx
* Status : OK, few options

Wildx telephony connector to retrieve history in agnda/history

## MMIBrevo
* Num 437824
* https://github.com/lemathou/dolibarr-module-mmibrevo
* Status : OK, few options
* Version : 1.0
* Requirements : Maybe Hook (see my dolibarr fork)

Brevo connector for SMS

## MMIYounited
* Num 437825
* Repos : https://github.com/lemathou/dolibarr-module-mmiyounited
* Status : OK, few options
* Version : 1.0
* Requirements : MMIPayments

Younited Payment Module for Dolibarr

## Forked modules

## MBIEtransactions (fork)
* Num 172370
* Repos : https://github.com/lemathou/dolibarr-module-mbietransactions
* Version : 1.0
* Requirements : MMIPayments
* Many differences with original module

Payment for Crédit Agricole Etransactions / Up2Pay
