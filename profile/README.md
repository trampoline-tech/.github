# FableRoom

We build the operational infrastructure behind **[Fableroom](https://fableroom.com)**, a home furnishing and lifestyle brand shipping from artisan manufacturing hubs in Jodhpur and Bhadohi, India to customers in the UK.

## What we build

Supply chain, end to end: purchase order to customer doorstep. Vendor management, SKU-level production tracking, container planning, UK warehouse intake and last-mile fulfilment.

| System | What it does |
|---|---|
| Purchase Order & EDD Tracker | Tracks every SKU across production phases, handover dates and delivery windows per PO line |
| Cargonaut | Container planning: allocating SKUs to FCL/LCL shipments, vessel schedules, freight rates |
| Order & Inventory Management | Stock control, order allocation and backorders for the Shopify store |
| Ops Hub & Jarvis | Internal dashboards for operations, allocation, launches and quality control |
| Vendor Portal | Vendor-facing production updates, purchase orders and order visibility |
| QC & Tracking | Quality control workflows and carrier tracking with Shopify fulfilment updates |
| Mobile apps | Native Fableroom shopping apps for Android and iOS |

## Active repositories

| Repo | What it is | Stack |
|---|---|---|
| `trampoline` | Monorepo: backend API, Ops Hub, vendor onboarding, agents and scheduled jobs | Django, PostgreSQL |
| `admin-dashboard-frontend` | Jarvis, the internal admin dashboard | Next.js |
| `supplier-portal` | Vendor Portal: live orders and PO management (the rest of the portal lives in `trampoline`) | Next.js |
| `fableroom-app-android` | Fableroom Android app | Kotlin, Jetpack Compose |
| `fableroom-app-ios` | Fableroom iOS app | SwiftUI |
| `trampoline-terraform` | AWS infrastructure | Terraform |

Repositories prefixed `DEPRECATED-` are retired and kept for reference only.

## Stack

Django 5.1 · Django REST Framework · PostgreSQL · Next.js · Kotlin · SwiftUI · Shopify · AWS (ECS Fargate, RDS, EC2, S3)

---

> Internal tooling. Not open source.
