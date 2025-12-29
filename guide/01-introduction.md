# Introduction

Welcome to InventoryPro, a comprehensive inventory management system designed for manufacturing businesses.

## What is InventoryPro?

InventoryPro is a multi-tenant SaaS application that helps manufacturers manage their entire production lifecycle:

- **Raw Materials**: Track materials with FIFO (First-In-First-Out) batch tracking
- **Products (SKUs)**: Manage your finished goods catalog
- **Bill of Materials**: Define recipes for producing SKUs from materials
- **Production**: Schedule and track manufacturing jobs
- **Inventory**: Real-time stock levels and transaction history
- **Customers & Deliveries**: Manage orders and shipments

## Multi-Tenant Architecture

InventoryPro supports multiple organizations (tenants) on a single platform. Each tenant has:

- Isolated data (materials, SKUs, inventory, etc.)
- Separate user accounts with role-based access
- Independent configuration and settings

## User Roles

| Role | Permissions |
|------|-------------|
| **Admin** | Full access to all features including user management and settings |
| **User** | Can create, edit, and delete records. Cannot manage users or change settings |
| **Viewer** | Read-only access to all data. Cannot make changes |

## Core Workflow

```
Materials → BOM → Production Job → Finished SKU → Delivery
```

1. **Define Materials**: Add raw materials to your inventory
2. **Create BOMs**: Define how materials combine to create products
3. **Start Jobs**: Create production jobs that consume materials
4. **Track Inventory**: Monitor stock levels and transactions
5. **Deliver Products**: Ship finished goods to customers

## Getting Started

To begin using InventoryPro:

1. [Register or log in](02-authentication.md) to your account
2. Explore the [Dashboard](03-dashboard.md) for an overview
3. Add your [Materials](04-materials.md) and [SKUs](05-skus.md)
4. Create your first [Bill of Materials](06-boms.md)

## Need Help?

Use the search bar at the top to find specific topics, or browse the sidebar navigation to explore all features.
