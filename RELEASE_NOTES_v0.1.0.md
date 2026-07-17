# Bank CSV Reconciliation Audit v0.1.0

Privacy-safe sample package for evaluating a fixed-scope bank CSV reconciliation audit.

## What this release contains

- Finnish landing page for a 249 EUR fixed-scope audit.
- Buyer guide for rent-payment tracking from bank CSV exports.
- Safe 5-minute fit-check page with mailto CTA that asks for headers and format facts only.
- Safe synthetic example-data guide: no real bank exports, account numbers, customer names, credentials, or transaction rows in first contact.
- Synthetic sample report showing matched/missing expected payments, duplicate candidates, and validation warnings.

## Buyer fit

Best fit: a small Finnish landlord, property operator, or small business that already exports bank transactions and wants a read-only exception report for one CSV format and one expected-payment ledger.

Not included: bank login, accounting advice, payment initiation, debt collection, live bank integration, or public data upload.

## Safe inquiry path

Primary CTA: email antero.vipunen.dev@gmail.com with only:

1. desired outcome;
2. CSV column names only, not rows;
3. date and decimal conventions;
4. monthly row/payment volume estimate;
5. confirmation that no bank export, account number, credentials, personal data, or transaction description is attached.

Public landing: https://anterovipunen.github.io/bank-csv-reconciliation-audit/

## Demand signals, not affiliations

Public examples that show recurring demand for bank CSV import and rent tracking:

- https://github.com/Dolibarr/dolibarr/issues/17798
- https://github.com/jguthrie100/rent_tracker

These are market signals only, not customers, leads, affiliations, endorsements, or revenue.
