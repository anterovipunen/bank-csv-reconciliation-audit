# Bank CSV Reconciliation Audit

**Turn a messy exported bank CSV and an expected-payment list into a deterministic exception report.**

## Fixed-scope offer

For a single bank-export shape, the audit delivers:

- a documented column mapping;
- matched and missing expected payments;
- stable duplicate transaction detection;
- JSON and Markdown reports; and
- a small local Python runner/config you can keep.

**Typical fixed scope:** €150–€350 for one CSV format and one expected-payment ledger.  
**Starter integration:** discussed only after the audit has proven the mapping.

## Designed for

- small landlords or property operators reconciling rent receipts;
- small businesses reconciling expected receipts from a CSV export; and
- finance/ERP product teams adding a safe CSV-import workflow.

## Privacy and scope

This is a local-file, read-only workflow. Never post bank statements, transaction data, credentials, or personal data in a public GitHub issue. A scope discussion starts with headers, date/decimal conventions, and a synthetic or anonymized sample only.

## Evidence-backed workflow

1. Confirm one export format and the expected-payment columns.
2. Run a local mapping and reconciliation pass.
3. Review duplicates and exceptions.
4. Deliver a sanitized report, configuration, and rerunnable tool.

## Inquiry

Email `antero.vipunen.dev@gmail.com` for a safe scope review. In the first message include only CSV column names, date/decimal conventions, and the desired outcome — never bank data, credentials, customer data, account numbers, or transaction descriptions. A secure data-sharing route is agreed only after the scope is accepted.

## What this is not

- It does not connect to a bank or request credentials.
- It does not perform accounting, payment initiation, or financial advice.
- It does not process real customer data in the public repository.

## Demand evidence

Public product-maintainer issues illustrate recurring demand for CSV imports, duplicate detection, payment tracking, and per-bank mapping:

- https://github.com/IssamSayyaf/my-budget/issues/7
- https://github.com/ivanleekk/finance-tracker/issues/231
- https://github.com/kgz/Funds-Manager/issues/189
- https://github.com/alexbessedonato/Rentaly/issues/25

These links are market evidence, not affiliations or paid leads.
