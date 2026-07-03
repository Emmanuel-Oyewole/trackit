# Trackit

Trackit is a configurable payment collection and reconciliation platform that enables organizations to assign dedicated virtual accounts to customers, monitor incoming payments in real time, and automatically reconcile transactions.

Instead of building separate systems for schools, landlords, cooperatives, religious organizations, or event organizers, Trackit provides a single configurable workspace where terminology and business rules can be customized while the underlying payment engine remains the same.

---

## Problem

Many organizations still struggle to:

- Track who has paid
- Match bank transfers manually
- Detect underpayments and overpayments
- Refund excess payments efficiently
- Generate payment reports
- Notify customers of payment details

Manual reconciliation is slow, error-prone, and difficult to scale.

---

## Solution

Trackit combines virtual accounts with an intelligent reconciliation engine.

Each customer receives a dedicated virtual account.

When payments arrive:

- Transactions are received through Nomba webhooks.
- Payments are matched automatically.
- Customer obligations are updated.
- Payment status changes instantly.
- Administrators receive real-time visibility.

---

## Core Features

- Configurable Workspaces
- Customer Management
- Bulk CSV Import
- Virtual Account Assignment
- Payment Obligations
- Real-Time Payment Dashboard
- Automatic Reconciliation
- Refund Management
- Notification Center
- Reports & Export
- Audit Logs

---

## Payment Workflow

Customer

↓

Dedicated Virtual Account

↓

Nomba Infrastructure

↓

Merchant Settlement Account

↓

Webhook

↓

Trackit Reconciliation Engine

↓

Dashboard Updates

---

## Architecture

Workspace

↓

Customers

↓

Payment Obligations

↓

Payments

↓

Reconciliation Engine

↓

Notifications

↓

Reports

---

## Technology Stack

Frontend

- Nextjs
- TypeScript

Backend

- Node.js
- nestjs

Database

- PostgreSQL

Authentication

- JWT

Payments

- Nomba Virtual Accounts
- Nomba Webhooks
- Nomba Transactions API
- Nomba Transfers API

---

## Current MVP

- Workspace Management
- Customer Management
- CSV Import
- Virtual Account Generation
- Payment Obligations
- Automatic Reconciliation
- Notifications
- Refund Review
- Reports

---

## Future Roadmap

- SMS Notifications
- Installment Plans
- Multi-admin Support
- Custom Domains
- Customer Self-Service Portal
- Payment Links


---

## Team

Product Manager

Backend Engineer

Frontend Engineer


---

## License

MIT