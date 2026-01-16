---
title: "Livestock"
weight: 3
---

# Livestock Module

Manage your livestock including cattle, poultry, goats, sheep, and pigs. Track animals by purpose, monitor yields, and optionally track dairy cattle individually for detailed production records.

## Key Features

### Animal Types
Support for Cattle, Poultry, Goat, Sheep, Pig, and Others. Each type has specific "Raised For" options.

### Purpose Tracking
Specify why you're raising the livestock: Dairy, Meat, Breeding, Egg production, or Others.

### Individual Tracking
For dairy cattle, enable individual tracking to monitor each animal separately with detailed yield and health records.

### Yield Management
Track milk production, egg collection, or other yields. Individual tracking allows yield recording per animal.

---

## Animal Types & Options

| Animal Type | Raised For Options |
|-------------|-------------------|
| **Cattle** | Dairy, Meat, Breeding, Others |
| **Poultry** | Egg, Meat, Breeding, Others |
| **Goat** | Meat, Dairy, Breeding, Others |
| **Sheep** | Meat, Breeding, Others |
| **Pig** | Meat, Breeding, Others |
| **Others** | Meat, Dairy, Breeding, Others |

---

## Yield Units by Purpose

The "Raised For" purpose determines how yields are measured:

| Raised For | Yield Unit | Example |
|------------|------------|---------|
| **Dairy/Milk** | Liters | 15 Liters of milk per day |
| **Egg** | Units | 120 eggs collected |
| **Meat** | Kg | 25 Kg of meat |
| **Breeding** | Heads/Units | 2 calves born |
| **Others** | Kg | Default weight measurement |

---

## Individual Tracking for Dairy Cattle

Individual tracking allows you to create detailed records for each animal in your dairy herd.

### Availability
Individual tracking is available only when:
- Animal Type is **Cattle**
- Raised For is **Dairy**
- **Track Individually** option is turned ON

### Benefits
- Track each cow/buffalo with individual profiles
- Record milk yields per animal
- Monitor individual health and breeding records
- Identify top performers and low producers
- Make informed decisions about culling or breeding

### Animal Profile Features

| Feature | Description |
|---------|-------------|
| **Basic Info** | Name/ID, Breed, Gender, Date of Birth |
| **Growth Stage** | Track the animal's current life stage |
| **Breeding Cycle** | Open, Bred, or Pregnant status |
| **Milking Status** | Dry or Milking |
| **Lactation Number** | Number of completed lactation cycles |
| **Parentage** | Sire (father) and Dam (mother) records |
| **Status** | Active, Sold, or Deceased |

> **When to use:** Enable individual tracking for dairy cattle where you want to monitor each animal's milk production and health separately. This is ideal for farms with smaller herds where individual animal performance matters.

> **When not to use:** For large herds, meat production, or poultry, group tracking is more practical as individual records would be too time-consuming to maintain.

---

## Supported Actions

| Action | Usage | Availability |
|--------|-------|--------------|
| **Animals** | Add and manage individual animal profiles | Only with individual tracking enabled |
| **Income** | Record sales of animals, milk, eggs, or other products | All livestock |
| **Expenses** | Track costs including feed, veterinary care, medications, housing | All livestock |
| **Tasks** | Schedule vaccinations, health checkups, breeding activities | All livestock |
| **Notes** | Record health observations, behavioral changes, breeding notes | All livestock |
| **Yields** | Track milk production, egg collection, or other outputs | All livestock |
| **Documents** | Store vaccination records, purchase documents, health reports | All livestock |

---

## Reports

Each livestock entry has a dedicated report available at the bottom of the livestock summary screen.

### Accessing Livestock Report

Navigate to: **Livestock → [Specific Entry] → Report** (at bottom of summary)

### Report Features

- **View** - See complete livestock summary including income, expenses, yields, and profitability
- **Download PDF** - Get a formatted report for printing or sharing
- **Download CSV** - Export raw data for spreadsheet analysis

This module-level report combines all data for that specific livestock entry in one place, making it easy to analyze performance and profitability.

---

## Tips

- Choose the correct "Raised For" purpose as it determines available features and reporting.
- Enable individual tracking only for dairy cattle where you need per-animal yield records.
- For poultry and large herds, use group tracking to save time on record keeping.
- Record milk yields daily to identify production trends and top-performing animals.
- Use tasks to set vaccination and health checkup reminders.
- Link income to buyer contacts to track which buyers purchase your livestock products.
- Track feed expenses from inventory to calculate cost per animal or per liter of milk.
- Document parentage for breeding stock to maintain lineage records.

---

## Frequently Asked Questions

<details>
<summary><strong>When should I use individual tracking?</strong></summary>

Use individual tracking for dairy cattle when you want to monitor each animal's milk production separately. This helps identify high and low producers. For meat animals, poultry, or large herds, group tracking is more practical.
</details>

<details>
<summary><strong>Why can't I see the Animals action?</strong></summary>

The Animals action is only available when: 1) Animal type is Cattle, 2) Raised For is Dairy, and 3) Track Individually is turned ON. Check these settings in your livestock entry.
</details>

<details>
<summary><strong>Can I track individual animals for poultry?</strong></summary>

Individual tracking is currently available only for dairy cattle. Poultry is typically managed as a flock/group due to the large numbers involved.
</details>

<details>
<summary><strong>How do I record milk yield per animal?</strong></summary>

First, enable individual tracking for your dairy cattle. Then add each animal using the Animals action. When recording yields, you can select the specific animal to attribute the milk production to.
</details>

<details>
<summary><strong>Can I change from group tracking to individual tracking later?</strong></summary>

Yes, you can enable individual tracking for existing dairy cattle entries. After enabling, you can start adding individual animal records.
</details>

<details>
<summary><strong>What are the breeding cycle options?</strong></summary>

You can track female animals as: Open (not bred, ready for breeding), Bred (mated but not confirmed pregnant), or Pregnant (confirmed pregnancy). Update this as the animal progresses through the cycle.
</details>

<details>
<summary><strong>What is milking status?</strong></summary>

Milking status indicates whether a dairy animal is currently producing milk. Options are: Milking (actively producing) or Dry (not producing, typically during late pregnancy or rest period).
</details>

<details>
<summary><strong>What is lactation number?</strong></summary>

Lactation number tracks how many times the animal has calved and started a new milk production cycle. First-time mothers are in their 1st lactation, and this increases with each subsequent calving.
</details>

<details>
<summary><strong>How do I record when an animal is sold or dies?</strong></summary>

Open the animal's profile and update the status to "Sold" or "Deceased". This keeps the animal's historical records while removing it from active herd counts.
</details>

<details>
<summary><strong>What is the difference between Sire and Dam?</strong></summary>

Sire refers to the father of the animal, and Dam refers to the mother. Recording both helps you track lineage, identify genetic traits, and make better breeding decisions.
</details>
