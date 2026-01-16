---
title: "Yields"
weight: 5
---

# Yields Action

Track harvest quantities and production output from your crops and livestock. Units are automatically set based on the module and production type.

## Purpose

Record crop harvests, milk production, egg collection, breeding outputs, and other measurable yields to monitor productivity and compare performance across seasons.

## Key Features

- **Automatic units** - Units are set based on module and production type
- **Quality tracking** - Record grades for premium vs regular produce
- **Production trends** - Monitor yield patterns over time
- **Season comparison** - Compare yields across different seasons
- **Individual animal yields** - Track per-animal production for dairy cattle

---

## Yield Units by Module

### Crop Yields

All crop yields are measured in **Kilograms (Kg)**.

| Crop Type | Unit | Example |
|-----------|------|---------|
| All crops | **Kg** | Harvested 500 Kg of tomatoes |

---

### Livestock Yields

Livestock yield units are determined by the **Raised For** purpose set when creating the livestock entry.

| Raised For | Unit | Description |
|------------|------|-------------|
| **Milk** | **Liters** | Daily or session-wise milk production |
| **Eggs** | **Units** | Number of eggs collected |
| **Meat** | **Kg** | Weight of meat produced |
| **Breeding** | **Heads/Units** | Number of offspring born |
| **Others** | **Kg** | Default weight-based measurement |

---

## Examples

### Crop Yield Recording
- Paddy harvest: **2,500 Kg**
- Tomato harvest: **800 Kg**
- Coconut harvest: **350 Kg**

### Livestock Yield Recording

| Livestock | Raised For | Yield Example |
|-----------|------------|---------------|
| Dairy Cattle | Milk | **15 Liters** per day |
| Poultry | Eggs | **120 Units** per day |
| Goat | Meat | **25 Kg** per animal |
| Cattle | Breeding | **1 Head** (calf born) |
| Sheep | Breeding | **2 Heads** (lambs born) |

---

## Available In

- Crops
- Livestock

---

## Tips

- Record yields on harvest day for accuracy
- For dairy cattle with individual tracking, record yields per animal to identify top producers
- Include quality information to track premium vs regular produce
- Compare yields across seasons to identify improvements
- Record partial harvests separately if harvesting over multiple days
- Use notes to document factors affecting yield (weather, pests, inputs)

---

## Best Practices

- Record yields consistently at the same time (e.g., daily for milk)
- Track both quantity and quality metrics
- Note any factors that affected the yield (weather, inputs, timing)
- For breeding livestock, record offspring details in notes
- Review yield trends to optimize feeding and management practices

---

## Yield to Inventory to Income Workflow

Recording a yield does **not** automatically add it to inventory. This is intentional because not all produced yield is suitable for sale - some may be spoilt, damaged, or kept for personal use.

### Step-by-Step Process

1. **Record Yield** - Track your harvest or production output here
2. **Create Inventory Item** - Go to Inventory and create an item with "Yield" category
3. **Add to Inventory** - Manually add the saleable quantity using "Produced" transaction
4. **Record Income** - When selling, link the inventory item to the income record

### Why Manual Entry?

| Yield Recorded | Inventory Added | Reason |
|----------------|-----------------|--------|
| 500 Kg harvested | 450 Kg | 50 Kg spoilt or damaged |
| 100 Liters milk | 90 Liters | 10 Liters for personal use |
| 50 eggs collected | 45 eggs | 5 eggs broken |

This separation gives you accurate records of both total production (yields) and saleable inventory.

---

## Reports

View, download, and analyze your yield data with built-in reports. Reports can be exported as **PDF** or **CSV**.

### Accessing Reports

| Level | Navigation | Data Shown |
|-------|------------|------------|
| **Module Level** | Crops → [Specific Crop] → Yields → Report | Yields for that specific crop only |
| **Module Level** | Livestock → [Specific Entry] → Yields → Report | Yields for that specific livestock only |
| **Global Level** | Home → Yields → Report | Choose Crops or Livestock report |
| **Global Level** | Home → Reports → Crop Yield Report | All crop yields across the farm |
| **Global Level** | Home → Reports → Livestock Yield Report | All livestock yields across the farm |

### Why Separate Yield Reports?

Unlike Income and Expenses, Yields have **two separate global reports** - one for Crops and one for Livestock. This separation avoids confusion since:
- Crop yields are measured in **Kg**
- Livestock yields vary by purpose (Liters, Units, Kg, Heads)

Having separate reports makes it easier to analyze production data for each category.

### Report Features

- **View** - See yield summaries and production trends on screen
- **Download PDF** - Get a formatted report for printing or sharing
- **Download CSV** - Export raw data for spreadsheet analysis

> **Tip:** Use module-level reports to track production for a specific crop or livestock. Use global reports to compare yields across all crops or all livestock.

---

## Frequently Asked Questions

<details>
<summary><strong>Why doesn't yield automatically add to inventory?</strong></summary>

Not all produced yield is fit for sale. Some harvest may be spoilt, damaged, or kept for personal use. By manually adding to inventory, you record only the saleable quantity, giving you accurate production vs sales data.
</details>

<details>
<summary><strong>How do I add yield to inventory?</strong></summary>

1. Go to Inventory module
2. Create a new item with "Yield" category (e.g., "Tomato Harvest")
3. Use the "Produced" transaction to add the saleable quantity
4. When selling, link this inventory item to your Income record
</details>

<details>
<summary><strong>Why can't I change the yield unit?</strong></summary>

Yield units are automatically determined based on the module and production type. Crop yields are always in Kg. Livestock yields depend on the "Raised For" setting (Milk = Liters, Eggs = Units, etc.). This ensures consistent data for reporting and comparison.
</details>

<details>
<summary><strong>How do I record milk yield per cow?</strong></summary>

First, enable individual tracking for your dairy cattle. Add each animal using the Animals action. When recording yields, you can select the specific animal to attribute the milk production to.
</details>

<details>
<summary><strong>Can I record multiple yields per day?</strong></summary>

Yes, you can record yields as often as needed. For dairy cattle, you might record morning and evening milking separately. For crops, you can record each day's harvest during a multi-day harvest period.
</details>

<details>
<summary><strong>How do I track egg production for poultry?</strong></summary>

Create a poultry livestock entry with "Raised For" set to "Egg". When you record yields, the unit will automatically be set to Units (number of eggs).
</details>

<details>
<summary><strong>What's the difference between yield and income?</strong></summary>

Yield tracks the quantity produced (Kg of harvest, liters of milk). Income tracks the money received when you sell. To link them: record yield first, add saleable quantity to inventory, then link that inventory to income when you sell.
</details>
