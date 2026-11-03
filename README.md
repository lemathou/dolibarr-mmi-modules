# Dolibarr MMI modules

**English** · [Français](README.fr.md)

Open-source Dolibarr modules by **Mathieu Moulin / iProspective** (MMI), published on GitHub.
Module IDs **437800–437827** (ID 437817 is not published).

All MMI modules depend on **MMICommon**, which must be enabled first.

## Modules

| Module | ID | Version | Description | Requires |
|---|---:|---|---|---|
| [MMICommon](https://github.com/lemathou/dolibarr-module-mmicommon) | 437800 | 1.2 | Shared foundation for all MMI modules: setup renderer, about page, home-page components, helpers, utility classes and common triggers. | — |
| [MMIAtelier](https://github.com/lemathou/dolibarr-module-mmiatelier) | 437801 | 1.0 | Workshop management: manufacturing orders, planning and workstation tracking. | mmicommon |
| [MMIAvisVerifies](https://github.com/lemathou/dolibarr-module-mmiavisverifies) | 437802 | 1.0 | Avis Vérifiés (NetReviews) connector: collect and export customer reviews. | mmicommon |
| [MMICompta](https://github.com/lemathou/dolibarr-module-mmicompta) | 437803 | 1.0 | Accounting add-ons: deferred revenue (PCA), accounting export, paid-invoice correction and deposit handling. | mmicommon |
| [MMICRM](https://github.com/lemathou/dolibarr-module-mmicrm) | 437804 | 1.2.1 | CRM: customer follow-up, reminders, loyalty, product campaigns, invoice/order comments and short links. | mmicommon |
| [MMIDocuments](https://github.com/lemathou/dolibarr-module-mmidocuments) | 437805 | 1.2.0 | Document and PDF/ODT enhancements: extra fields, print options, shipping documents, situation invoices, PDF renaming and VAT exemption notices. | mmicommon |
| [MMIEntrepots](https://github.com/lemathou/dolibarr-module-mmientrepots) | 437806 | 1.1 | Warehouse location management (storage locations on products) and related stock tools. | mmicommon, categorie |
| [MMIFilters](https://github.com/lemathou/dolibarr-module-mmifilters) | 437807 | 1.1 | List filters and mass actions on quotes, orders, invoices and shipments. | mmicommon |
| [MMIFournisseurPrice](https://github.com/lemathou/dolibarr-module-mmifournisseurprice) | 437808 | 1.0 | Supplier prices: price lists, history, comparison and cost price including shipping. | mmicommon, mmishipping, mmiproduct, product, fournisseur, reception |
| [MMIPayments](https://github.com/lemathou/dolibarr-module-mmipayments) | 437809 | 1.5 | Payment hub: a Payments tab on third parties, quotes, orders and invoices, a global payment list, payment links and an extension API for payment modules. | mmicommon |
| [MMIPrestaSync](https://github.com/lemathou/dolibarr-module-mmiprestasync) | 437810 | 1.1.0 | PrestaShop ↔ Dolibarr synchronization: products, customers, addresses, orders, invoices, payments and stock. | mmicommon, mmiproduct, mmifournisseurprice, mmipayments, mmiworkflow |
| [MMIProduct](https://github.com/lemathou/dolibarr-module-mmiproduct) | 437811 | 1.1.2 | Advanced product management: price and margin calculation, cost stacking, competitor monitoring, replenishment, stock and inventory, REST API. | mmicommon, product |
| [MMIProductDluo](https://github.com/lemathou/dolibarr-module-mmiproductdluo) | 437812 | 1.0 | DLUO/DLC and batch management: batch selection, anti-waste, composed stock, tier pricing and picking. | mmicommon, productbatch, mmiproduct |
| [MMIProject](https://github.com/lemathou/dolibarr-module-mmiproject) | 437813 | 1.0.3 | Project management: time tracking, profitability, BTP/workshop projects and simplified timesheets. | mmicommon, projet |
| [MMIStats](https://github.com/lemathou/dolibarr-module-mmistats) | 437814 | 1.0.1 | Dashboards and statistics for sales representatives, products and margins. | mmicommon |
| [MMIVATEEC](https://github.com/lemathou/dolibarr-module-mmivateec) | 437815 | 1.0 | VAT and eco-contribution handling for intra-EU B2C sales. | mmicommon |
| [MMIWorkflow](https://github.com/lemathou/dolibarr-module-mmiworkflow) | 437816 | 1.3.0 | Sales workflow automation: one-click invoice and shipment, reopen as draft, shipment/receipt tracking, email shortcuts and a REST endpoint. | mmicommon, mmipayments |
| [MMIShipping](https://github.com/lemathou/dolibarr-module-mmishipping) | 437818 | 1.1 | Advanced shipping and receiving: DF recipient assignment, direct warehouse flows, port/VAT self-liquidation, carrier cost analysis and PDF hooks. | mmicommon, product, fournisseur, expedition, reception |
| [MMISecurity](https://github.com/lemathou/dolibarr-module-mmisecurity) | 437819 | 1.0 | Security hardening: IP allow-list filtering for non-privileged users. | mmicommon |
| [MMIRedmine](https://github.com/lemathou/dolibarr-module-mmiredmine) | 437820 | 1.0 | Redmine synchronization of projects, issues and time entries. | mmicommon, projet |
| [MMIGED](https://github.com/lemathou/dolibarr-module-mmiged) | 437821 | 1.0 | Document management: attach documents to suppliers, link them to products and email them to customers. | mmicommon, ecm |
| [MMISAV](https://github.com/lemathou/dolibarr-module-mmisav) | 437822 | 1.0 | After-sales support through tickets: interventions, returns and supplier/customer communication. | mmicommon, ticket |
| [MMIWildx](https://github.com/lemathou/dolibarr-module-mmiwildx) | 437823 | 1.0 | WildX telephony connector: retrieve call history into the agenda and history. | mmicommon |
| [MMIBrevo](https://github.com/lemathou/dolibarr-module-mmibrevo) | 437824 | 1.1 | Brevo connector: email/SMS campaigns, contacts and statistics. | mmicommon |
| [MMIYounited](https://github.com/lemathou/dolibarr-module-mmiyounited) | 437825 | 1.1.3 | Younited Pay financing: loan/payment creation, offers, redirects, webhook and status tracking. | mmicommon, mmipayments |
| [MBIETransactions](https://github.com/lemathou/dolibarr-module-mbietransactions) | 437826 | 1.3.0 | MBI ETransactions (MBI + ETransactions, now Up2Pay) card payments: payment page, return pages, reconciliation and payment-tab integration. Fork of the original MBI ETransactions module. | mmicommon, mmipayments |
| [MMIAtombox](https://github.com/iprospective/dolibarr-module-mmiatombox) | 437827 | 0.1.0 | AtomBox mail: mail exchanges on third-party, quote, order, invoice and project records, tags, an Exchanges tab and delegated webmail. | mmicommon |

## Module details

### [MMICommon](https://github.com/lemathou/dolibarr-module-mmicommon)
**ID 437800** · **v1.2** · Requires: —

Shared foundation for all MMI modules: setup renderer, about page, home-page components, helpers, utility classes and common triggers.

- Shared setup renderer with masked secrets and a reveal button
- MMI home-page header/footer/links/block components
- Price, date and statistics helpers
- Common triggers, product/project tabs and comment actions

### [MMIAtelier](https://github.com/lemathou/dolibarr-module-mmiatelier)
**ID 437801** · **v1.0** · Requires: mmicommon

Workshop management: manufacturing orders, planning and workstation tracking.

- Manufacturing orders
- Planning and workstation tracking
- Workshop menus and setup

### [MMIAvisVerifies](https://github.com/lemathou/dolibarr-module-mmiavisverifies)
**ID 437802** · **v1.0** · Requires: mmicommon

Avis Vérifiés (NetReviews) connector: collect and export customer reviews.

- Customer review collection and FTP export (production/test)
- Cron job for scheduled sends
- FTP and send-tracking configuration

### [MMICompta](https://github.com/lemathou/dolibarr-module-mmicompta)
**ID 437803** · **v1.0** · Requires: mmicommon

Accounting add-ons: deferred revenue (PCA), accounting export, paid-invoice correction and deposit handling.

- Deferred revenue (PCA) calculation and tracking
- Accounting export with account-label options
- Paid-invoice correction (status/settlement)
- Deposit VAT handling

### [MMICRM](https://github.com/lemathou/dolibarr-module-mmicrm)
**ID 437804** · **v1.2.1** · Requires: mmicommon

CRM: customer follow-up, reminders, loyalty, product campaigns, invoice/order comments and short links.

- Customer reminders and loyalty
- Product campaigns and message templates
- Invoice and order comments
- Short links and customer/order pages

### [MMIDocuments](https://github.com/lemathou/dolibarr-module-mmidocuments)
**ID 437805** · **v1.2.0** · Requires: mmicommon

Document and PDF/ODT enhancements: extra fields, print options, shipping documents, situation invoices, PDF renaming and VAT exemption notices.

- Complementary document fields (deposit, terms, line/product/supplier refs, SIRET…)
- PDF/ODT display and column options
- Shipping document options (weight, batch, date, images, message)
- Situation invoices and configurable PDF renaming
- VAT exemption notices selected from the third party and context

### [MMIEntrepots](https://github.com/lemathou/dolibarr-module-mmientrepots)
**ID 437806** · **v1.1** · Requires: mmicommon, categorie

Warehouse location management (storage locations on products) and related stock tools.

- Storage locations per product
- Inventory and database tools
- Shipping PDF display
- Warehouse menus and setup

### [MMIFilters](https://github.com/lemathou/dolibarr-module-mmifilters)
**ID 437807** · **v1.1** · Requires: mmicommon

List filters and mass actions on quotes, orders, invoices and shipments.

- Bulk assignment of a sales representative
- Additional list filters
- Shipment filter functional test

### [MMIFournisseurPrice](https://github.com/lemathou/dolibarr-module-mmifournisseurprice)
**ID 437808** · **v1.0** · Requires: mmicommon, mmishipping, mmiproduct, product, fournisseur, reception

Supplier prices: price lists, history, comparison and cost price including shipping.

- Supplier price lists and history
- Price comparison
- Cost price including shipping costs
- Supplier price card hooks

### [MMIPayments](https://github.com/lemathou/dolibarr-module-mmipayments)
**ID 437809** · **v1.5** · Requires: mmicommon

Payment hub: a Payments tab on third parties, quotes, orders and invoices, a global payment list, payment links and an extension API for payment modules.

- Unified Payments tab and global payment list
- Separates completed payments from payment attempts
- Extension hooks so each payment module contributes its own rows
- Secure payment links on quotes and orders
- Cheque and bank-transfer information on the payment page

### [MMIPrestaSync](https://github.com/lemathou/dolibarr-module-mmiprestasync)
**ID 437810** · **v1.1.0** · Requires: mmicommon, mmiproduct, mmifournisseurprice, mmipayments, mmiworkflow

PrestaShop ↔ Dolibarr synchronization: products, customers, addresses, orders, invoices, payments and stock.

- Products, customers, addresses, orders, invoices, payments and stock
- Authenticated web service and manual resynchronization
- Synchronization queue and resilience
- Configurable synchronized object types

### [MMIProduct](https://github.com/lemathou/dolibarr-module-mmiproduct)
**ID 437811** · **v1.1.2** · Requires: mmicommon, product

Advanced product management: price and margin calculation, cost stacking, competitor monitoring, replenishment, stock and inventory, REST API.

- Price and margin calculation tab
- Cost price stacking (logistics, packaging, shipping, misc.)
- Competitor price monitoring
- Replenishment with EOQ and service level
- Stock regularisation, inventory update and REST API

### [MMIProductDluo](https://github.com/lemathou/dolibarr-module-mmiproductdluo)
**ID 437812** · **v1.0** · Requires: mmicommon, productbatch, mmiproduct

DLUO/DLC and batch management: batch selection, anti-waste, composed stock, tier pricing and picking.

- Best-before dates and batch picker
- Anti-waste handling
- Composed stock
- Tier pricing and picking
- Dedicated API

### [MMIProject](https://github.com/lemathou/dolibarr-module-mmiproject)
**ID 437813** · **v1.0.3** · Requires: mmicommon, projet

Project management: time tracking, profitability, BTP/workshop projects and simplified timesheets.

- Time entry and monthly summary
- Site planning
- Work contracts
- Profitability and statistics
- Resource categories

### [MMIStats](https://github.com/lemathou/dolibarr-module-mmistats)
**ID 437814** · **v1.0.1** · Requires: mmicommon

Dashboards and statistics for sales representatives, products and margins.

- Sales representative dashboard
- Product dashboard
- Margin analysis and indicators

### [MMIVATEEC](https://github.com/lemathou/dolibarr-module-mmivateec)
**ID 437815** · **v1.0** · Requires: mmicommon

VAT and eco-contribution handling for intra-EU B2C sales.

- Intra-EU B2C VAT
- VIES check hooks
- Eco-contribution handling
- VAT history

### [MMIWorkflow](https://github.com/lemathou/dolibarr-module-mmiworkflow)
**ID 437816** · **v1.3.0** · Requires: mmicommon, mmipayments

Sales workflow automation: one-click invoice and shipment, reopen as draft, shipment/receipt tracking, email shortcuts and a REST endpoint.

- One-click invoice and shipment (with automatic batch picking)
- Deferred invoicing and automatic invoice email
- Reopen shipped orders and paid invoices as draft
- Shipment/receipt tracking with extra fields
- REST endpoint for external shipment creation

### [MMIShipping](https://github.com/lemathou/dolibarr-module-mmishipping)
**ID 437818** · **v1.1** · Requires: mmicommon, product, fournisseur, expedition, reception

Advanced shipping and receiving: DF recipient assignment, direct warehouse flows, port/VAT self-liquidation, carrier cost analysis and PDF hooks.

- DF recipient assignment and direct warehouse receipt/shipment
- Port editing and VAT self-liquidation on purchase orders
- Carrier cost analysis from CSV import
- Shipping/receiving PDF hooks (sorting, receiving address)
- Self-liquidation correction tool

### [MMISecurity](https://github.com/lemathou/dolibarr-module-mmisecurity)
**ID 437819** · **v1.0** · Requires: mmicommon

Security hardening: IP allow-list filtering for non-privileged users.

- IP-based access filtering
- Configurable allowed ranges
- Login and main hooks
- Dedicated setup page

### [MMIRedmine](https://github.com/lemathou/dolibarr-module-mmiredmine)
**ID 437820** · **v1.0** · Requires: mmicommon, projet

Redmine synchronization of projects, issues and time entries.

- Project and issue synchronization
- Time entries
- User and product mapping
- Manual synchronization pages

### [MMIGED](https://github.com/lemathou/dolibarr-module-mmiged)
**ID 437821** · **v1.0** · Requires: mmicommon, ecm

Document management: attach documents to suppliers, link them to products and email them to customers.

- DMS/ECM integration
- Supplier document attachment
- Product links
- Email documents to customers

### [MMISAV](https://github.com/lemathou/dolibarr-module-mmisav)
**ID 437822** · **v1.0** · Requires: mmicommon, ticket

After-sales support through tickets: interventions, returns and supplier/customer communication.

- SAV tickets
- Interventions and returns
- Supplier/customer communication
- Dedicated triggers

### [MMIWildx](https://github.com/lemathou/dolibarr-module-mmiwildx)
**ID 437823** · **v1.0** · Requires: mmicommon

WildX telephony connector: retrieve call history into the agenda and history.

- Call history retrieval
- Agenda/history integration
- Synchronization class
- Connector setup

### [MMIBrevo](https://github.com/lemathou/dolibarr-module-mmibrevo)
**ID 437824** · **v1.1** · Requires: mmicommon

Brevo connector: email/SMS campaigns, contacts and statistics.

- SMS sending from quotes, orders, invoices and third parties
- Campaigns and contacts
- Statistics
- Brevo API configuration

### [MMIYounited](https://github.com/lemathou/dolibarr-module-mmiyounited)
**ID 437825** · **v1.1.3** · Requires: mmicommon, mmipayments

Younited Pay financing: loan/payment creation, offers, redirects, webhook and status tracking.

- Loan/payment creation and offers via the Younited API
- Sandbox/production configuration
- Webhook with server-side status re-query
- Customer return pages
- Maturity tracking

### [MBIETransactions](https://github.com/lemathou/dolibarr-module-mbietransactions)
**ID 437826** · **v1.3.0** · Requires: mmicommon, mmipayments

MBI ETransactions (MBI + ETransactions, now Up2Pay) card payments: payment page, return pages, reconciliation and payment-tab integration. Fork of the original MBI ETransactions module.

- MBI ETransactions payment page
- Accepted, cancelled, refused and return pages
- Return journal and reconciliation
- Payment tab and secure payment links
- Email triggers and invoice/order/quote hooks


## Dolibarr MMI fork

The modules are developed against the MMI Dolibarr fork:
<https://github.com/lemathou/dolibarr>

Published branches include `14.0-mmi`, `16.0-mmi`, `17.0-mmi`, `18.0-mmi`, `19.0-mmi`
(the current production fork) and `20.0-mmi-merge` (migration to Dolibarr 20).

## License

Each module is distributed under the GNU GPL v3 or later (see the `COPYING` file in
each repository); documentation is under the GFDL. Some modules also require core
changes shipped in the MMI fork.

### [MMIAtombox](https://github.com/iprospective/dolibarr-module-mmiatombox)
**ID 437827** · **v0.1.0** · Requires: mmicommon

Links Dolibarr to AtomBox: Dolibarr objects become tags, customer replies are filed on the right record and each record shows its exchanges.

- Six tag axes: quotes, orders, invoices, projects, supplier orders and supplier invoices
- "Exchanges" tab on records
- Integrated delegated AtomBox webmail
- Message-ID host declaration and object synchronization
- Configuration: AtomBox URL, application token and account mapping

