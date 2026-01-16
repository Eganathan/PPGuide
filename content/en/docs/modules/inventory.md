---
title: "Inventory"
weight: 5
---

# Inventory Module

Track your farm inventory including seeds, fertilizers, pesticides, fuel, spare parts, and more. Monitor stock levels, usage history, and link inventory items to expenses across all your farm operations.

## Key Features

### Stock Management
Track inventory levels with Add and Use transactions. Monitor current stock and closing balances for all items.

### Category Organization
Organize inventory by categories: Seeds, Fertilizers, Pesticides, Herbicides, Fuel, Spare Parts, Feed, Health products, and Yields.

### Cost Tracking
Track cost per unit and total inventory value. Update cost per unit anytime to reflect current market prices.

### Transaction History
View complete history of all inventory transactions including additions, usage, and reversals with closing balances.

### Vendor Tracking
Select vendors from your contacts when adding stock to track where you purchase each item.

### Expense Mapping
Link consumable items to expenses on Crops, Fields, Farms, Livestock, or Machines to track where inventory is used.

---

## Inventory Categories

### Consumables
Items that are purchased and consumed during farming operations.

| Category | Description |
|----------|-------------|
| **Seeds** | Seeds and planting materials for crops |
| **Fertilizers** | Chemical and organic fertilizers for soil nutrition |
| **Pesticides** | Products for pest control and crop protection |
| **Herbicides** | Products for weed control |
| **Fuel** | Diesel, petrol, and other fuels for machinery |
| **Spare Parts** | Replacement parts for machines and equipment |
| **Feed** | Animal feed and fodder for livestock |
| **Health** | Medicines, vaccines, and health products for livestock |

**Transactions:** Added, Used, Reversal

### Producibles
Items that are produced on the farm, like harvested yields.

| Category | Description |
|----------|-------------|
| **Yield** | Harvested produce stored in inventory before sale |

**Transactions:** Produced, Sold, Reversal

---

## Pricing & Cost Tracking

### Cost Per Unit
Set the cost per unit for each inventory item. This can be updated anytime to reflect current market prices.

When you update the cost per unit, new purchases will use the updated price. The existing total cost is preserved.

### Total Cost Calculation
Total cost is calculated incrementally:
```
Old Total + (New Cost Per Unit × New Quantity Added)
```

**Example:** If total cost was ₹100 with cost per unit ₹10, and you update cost per unit to ₹20 then add 1 unit, new total = ₹100 + (₹20 × 1) = ₹120

### Supported Units
| Unit | Use For |
|------|---------|
| **Kg** | Items measured by weight (seeds, fertilizers, feed) |
| **Liters** | Liquid items (fuel, pesticides, herbicides) |
| **Unit** | Countable items (spare parts, tools) |

---

## Transaction History

The History tab shows all transactions for each inventory item, helping you track stock movements over time.

### Transaction Types
| Type | Description |
|------|-------------|
| **Added/Produced** | Stock was added to inventory (purchase for consumables, harvest for producibles) |
| **Used/Sold** | Stock was removed from inventory (consumption for consumables, sale for producibles) |
| **Reversal** | Correction entry to fix mistakes in previous transactions |

### Features
- View all Add, Use, and Reversal transactions
- See transaction dates and quantities
- Track closing balance after each transaction
- Identify usage patterns and consumption rates

---

## Expense Mapping

When recording expenses on Crops, Fields, Farms, Livestock, or Machines, you can select inventory items used. This automatically updates inventory stock.

### Benefits
- Track which crops or livestock consume the most inputs
- Automatically deduct stock when recording expenses
- Calculate input costs per module accurately
- Identify high-consumption areas for cost optimization

---

## Item Management

### Activation Status
Inventory items cannot be deleted to maintain transaction history. Instead, items can be disabled.

- **Disabled:** Cannot be selected when recording new expenses. Historical transactions remain intact.
- **Re-activate:** You can re-activate a disabled inventory item anytime to start using it again.

---

## Supported Actions

| Action | Usage |
|--------|-------|
| **Expenses** | Record purchase costs when adding new inventory stock |
| **Tasks** | Set reminders for restocking, inventory checks, or expiry monitoring |
| **Notes** | Add notes about storage conditions, batch numbers, or usage instructions |
| **Documents** | Attach purchase invoices, product labels, safety data sheets |

---

## Tips

- Record inventory additions immediately after purchase to maintain accurate stock counts.
- Update cost per unit when prices change to ensure new purchases reflect current market rates.
- Use the "Bought From" field to track vendors and compare prices across suppliers.
- Use the expense mapping feature to automatically track where consumables are used.
- Check the History tab regularly to monitor consumption patterns and plan restocking.
- Disable unused inventory items instead of leaving them active to keep your list clean.
- Record batch numbers and expiry dates in Notes for products that expire.
- Link fuel inventory to machine expenses to track fuel consumption per tractor.
- Use Feed and Health categories to track livestock input costs separately.
- Choose the appropriate unit (Kg, Liters, or Unit) based on how you purchase and use the item.

---

## Frequently Asked Questions

<details>
<summary><strong>How do I add new stock to inventory?</strong></summary>

Open the inventory item and use the Add transaction to record new stock. Enter the quantity and optionally link it to an expense record for cost tracking.
</details>

<details>
<summary><strong>How do I record inventory usage?</strong></summary>

You can either use the Use transaction directly on the inventory item, or select the inventory item when recording an expense on a Crop, Field, or other module. The second method automatically updates inventory stock.
</details>

<details>
<summary><strong>What's the difference between consumables and producibles?</strong></summary>

Consumables are items you purchase and use (seeds, fertilizers, fuel). Producibles are items you create on the farm (harvested yields). The transaction labels differ: consumables are Added/Used, producibles are Produced/Sold.
</details>

<details>
<summary><strong>Why can't I delete an inventory item?</strong></summary>

Inventory items cannot be deleted to preserve transaction history and maintain accurate records. Instead, disable items you no longer use. You can re-activate them later if needed.
</details>

<details>
<summary><strong>How do I track inventory costs per crop?</strong></summary>

When recording expenses on a crop, select the inventory items used. This links the consumption to that crop, allowing you to see total input costs per crop.
</details>

<details>
<summary><strong>What is a reversal transaction?</strong></summary>

Reversal is used to correct mistakes in previous Add or Use transactions. It adjusts the stock balance without deleting the original transaction, maintaining a complete audit trail.
</details>

<details>
<summary><strong>How do I see current stock levels?</strong></summary>

The inventory list shows current stock for each item. Open an item to see the History tab with detailed transactions and closing balances.
</details>

<details>
<summary><strong>How does cost per unit work?</strong></summary>

You can set and update the cost per unit anytime. When you add new stock, the total cost increases by: new cost per unit × quantity added. Previous total cost is preserved, so your total reflects actual spending over time.
</details>

<details>
<summary><strong>What happens when I update the cost per unit?</strong></summary>

Updating cost per unit only affects future additions. For example, if your total was ₹100 (10 units at ₹10 each) and you change cost per unit to ₹20, then add 1 unit, your new total becomes ₹120 (₹100 + ₹20×1).
</details>

<details>
<summary><strong>How do I track which vendor I bought from?</strong></summary>

When adding stock, use the "Bought From" field to select a contact from your phone. This helps you track purchase sources and compare prices from different vendors.
</details>
