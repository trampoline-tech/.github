# Trampoline Tech

We build the operational infrastructure behind **Trampoline** (B2B wholesale) and **Fableroom** (B2C) - two home furnishings brands shipping from artisan manufacturing hubs in Jodhpur and Bhadohi, India to customers and trade buyers in the UK.

## What we're building

**Supply chain, end to end.** Our platform handles the full journey from purchase order to customer doorstep, vendor management, SKU level production tracking, container planning, vessel scheduling, UK warehouse intake, and last-mile order fulfilment.

### Core systems

- **Purchase Order & EDD Tracker** - tracks every SKU across production phases, handover dates, and estimated delivery windows per purchase order line
- **Cargonaut** - internal container planning tool for allocating SKUs to FCL/LCL shipments, managing vessel schedules, freight forwarder rates, and shipping line comparisons
- **Inventory & Order Management** - real-time stock control and order allocation across wholesale and DTC channels
- **Fableroom Backend** - powers the B2C store including Shopify inventory sync, order webhooks, and fulfilment flows
- **Supplier & Seller Portals** - vendor-facing interfaces for production updates and order visibility
- **QC & Tracking** - quality control workflows and shipment tracking integrated with carriers (DHL, FedEx, UPS, etc.)

## Stack

Django 5.1 · PostgreSQL · AWS (RDS + ECS Fargate) · Django REST Framework · Alpine.js

## Brands

| Brand | Channel | Market |
|---|---|---|
| [Trampoline](https://trampolinestore.uk) | B2B wholesale | UK trade |
| [Fableroom](https://fableroom.co.uk) | B2C DTC | UK consumers |

---

> Internal tooling. Not open source.
