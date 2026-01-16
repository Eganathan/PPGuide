---
title: "Modules"
weight: 2
bookCollapseSection: true
---

# Farm Modules

Personal Pannai organizes your farm data into modules. Each module focuses on a specific aspect of your farming operation.

## Available Modules

| Module | Description |
|--------|-------------|
| [Farm]({{< relref "/docs/modules/farm" >}}) | Create and manage your farm profile and farm-level activities |
| [Crops]({{< relref "/docs/modules/crops" >}}) | Track crops from planting to harvest with season management |
| [Fields]({{< relref "/docs/modules/fields" >}}) | Manage your agricultural fields and crop rotation history |
| [Livestock]({{< relref "/docs/modules/livestock" >}}) | Manage cattle, poultry, goats, sheep, pigs with optional individual tracking |
| [Machines]({{< relref "/docs/modules/machines" >}}) | Track tractors, implements, usage, and maintenance |
| [Inventory]({{< relref "/docs/modules/inventory" >}}) | Manage seeds, fertilizers, fuel, and other farm inputs |
| [Contacts]({{< relref "/docs/modules/contacts" >}}) | Organize vendors, buyers, and track transaction history |
| [Roles]({{< relref "/docs/modules/roles" >}}) | Manage team access with Owner, Manager, and Worker roles |

## How Modules Work Together

Modules in Personal Pannai are interconnected:

- **Farm** is the central hub containing **Fields**, **Crops**, **Livestock**, **Machines**, and **Inventory**
- **Crops** link to **Fields** to track which areas are being cultivated
- **Expenses** on any module can link to **Machines** and **Inventory** items
- **Contacts** automatically track purchases and sales across modules
- **Roles** control who can access data in each module
