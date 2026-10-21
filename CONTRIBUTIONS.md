# Contributions — ERPNext Hotel Front Desk

I contributed **177 commits** to [`pmm-tech/front-desk`](https://github.com/pmm-tech/front-desk) between **December 2023 and July 2025**, while at Core Initiative Studio. This fork is a working copy; the upstream repository is canonical.

## What I worked on

### Front desk & folio
- Added the transfer-to-folio flow and corrected folio transaction validation.
- Fixed folio rounding adjustments on transfers.
- Added booking codes to guest bookings and a channel field to folios.

### POS & cashier
- Added overhandled POS invoice handling when closing a profile.
- Fixed tax-exclusion flows for reservations and "post all charges."
- Fixed POS settings and cashier-name edge cases.

### Rooms & housekeeping
- Added breakfast/room-card handling.
- Fixed room-card ownership and out-of-order room calculations.
- Overrode shift-status fields for the INN workflow.

### Purchasing
- Added purchase-order history, last-purchase sync, and printable purchase requests with previous data.
- Fixed purchase-order queries and daily table-order naming.

### Reports & audit
- Added daily `actual_room_rate` to the audit report.
- Fixed audit-report filters, date ranges, and reserved-status exclusions.
- Added room-occupancy reporting.

### Permissions & workspace
- Added per-DocType permissions and a role-generation button.
- Fixed role-permission generation and workspace bugs.

### Billing, tax & customer
- Fixed accumulated-amount counting and credit-commission accounts.
- Fixed account party-type correction and breakfast-commission reversal.
- Synced customer creation with INN customer creation.

## Selected commits

- [`2eb9634`](https://github.com/pmm-tech/front-desk/commit/2eb963412b) — feat: add flow transfer to folio
- [`f6b4ea0`](https://github.com/pmm-tech/front-desk/commit/f6b4ea0cd7) — feat: add flow to exclude reservation from generate tax
- [`c2020a8`](https://github.com/pmm-tech/front-desk/commit/c2020a887e) — feat: add overhandle POS invoice on closing profile
- [`89910a2`](https://github.com/pmm-tech/front-desk/commit/89910a2742) — feat: add report room occupancy
- [`bd6947b`](https://github.com/pmm-tech/front-desk/commit/bd6947bfe8) — feat: audit report to include actual_room_rate everyday
- [`1583a6d`](https://github.com/pmm-tech/front-desk/commit/1583a6d366) — feat: add permission for each doctype
- [`30f87ca`](https://github.com/pmm-tech/front-desk/commit/30f87caecf) — fix: rounding adjustment in transfer folio
- [`30d55ae`](https://github.com/pmm-tech/front-desk/commit/30d55aeeb9) — fix: create customer now also create inn customer

Full history filtered to my commits:
https://github.com/pmm-tech/front-desk/commits?author=anhilmy

## Context

- ERPNext / Frappe application for hotel front-office operations: reservations, folios, POS, housekeeping, purchasing, and audit reporting.
- Stack: Python, Frappe Framework, ERPNext, JavaScript, MariaDB.
- Upstream license: MIT.

This file is a portfolio summary, not part of the upstream project.
