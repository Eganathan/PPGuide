# CLAUDE.md - Project Context for AI Agents

## Project Overview

This is the documentation site for **Personal Pannai** (PPG - Personal Pannai Guide), a farm management mobile app. The documentation is built with Hugo using the hugo-book theme.

---

## Important Links & Contacts

| Item | Value |
|------|-------|
| **App Name** | Personal Pannai |
| **Site Name** | PPG (Personal Pannai Guide) |
| **Play Store** | https://play.google.com/store/apps/details?id=com.marudham.farmmanagement |
| **Official Website** | https://pannai.marutham.com |
| **Terms of Service** | https://pannai.marutham.com/terms |
| **Privacy Policy** | https://pannai.marutham.com/privacy |
| **Support Email** | support@marutham.com |
| **Docs URL** | https://personalpannai.guide/ |

---

## App Modules

All modules must be documented **separately** (never merge them):

| Module | Description |
|--------|-------------|
| **Farm** | Central hub - farm profile, team management, farm-level activities |
| **Crops** | Track crops with stages, seasons, field associations |
| **Fields** | Manage agricultural fields, crop rotation history |
| **Livestock** | Cattle, poultry, goat, sheep, pig management |
| **Machines** | Tractors, implements, usage tracking, maintenance |
| **Inventory** | Seeds, fertilizers, fuel, spare parts, yields |
| **Contacts** | Vendors, buyers, transaction history |
| **Roles** | Owner, Manager, Worker access levels |

---

## Actions

Actions are activities performed on modules:

| Action | Available In | Notes |
|--------|--------------|-------|
| **Income** | Crops, Livestock | Can link inventory items |
| **Expenses** | All modules | Types vary by module (see below) |
| **Tasks** | All modules | Scheduling activities |
| **Notes** | All modules | Observations, comments |
| **Yields** | Crops, Livestock | Units vary (see below) |
| **Documents** | All modules | Photos, receipts, files |
| **Animals** | Dairy Cattle only | Individual animal tracking |

---

## Expense Types by Module

**IMPORTANT:** Expense types are module-specific:

| Module | Expense Types |
|--------|---------------|
| **Farm** | Maintenance, Salary, Other |
| **Crop** | Sowing, Weeding, Irrigation, Spraying, Fertilizing, Tilling, Pruning, Harvesting, Other |
| **Machine** | Maintenance, Service, Other |
| **Livestock** | Feed, Milking, Cleaning, Health, Other |
| **Field** | Maintenance, Other |
| **Inventory** | Purchase, Other |

---

## Yield Units

**IMPORTANT:** Yield units depend on module and type:

### Crops
- All crop yields: **Kg**

### Livestock (based on "Raised For" type)
| Raised For | Unit |
|------------|------|
| Milk/Dairy | Liters |
| Eggs | Units |
| Meat | Kg |
| Breeding | Heads/Units |
| Others | Kg |

---

## Yield → Inventory → Income Workflow

**CRITICAL:** Recording a yield does NOT auto-add to inventory.

1. **Record Yield** - Track harvest/production
2. **Create Inventory Item** - Category: "Yield"
3. **Add to Inventory** - Use "Produced" transaction (only saleable quantity)
4. **Link to Income** - When selling, associate inventory item

**Reason:** Not all yield is saleable (some spoilt, damaged, personal use).

---

## Reports

Reports available for Income, Expenses, Yields - can be viewed, downloaded as PDF or CSV.

### Access Patterns
| Level | Navigation |
|-------|------------|
| Module Level | Module → [Specific Entry] → Action → Report |
| Global Level | Home → Action → Report |
| Global Level | Home → Reports → [Report Type] |

### Special Case: Yields
Two separate global reports for Yields:
- **Crop Yield Report** - All crop yields
- **Livestock Yield Report** - All livestock yields

(Separated because units differ)

### Crop/Livestock Module Reports
- Crops → [Specific Crop] → Report (at bottom of summary)
- Livestock → [Specific Entry] → Report (at bottom of summary)
- Crop reports can be **season-specific**

---

## Crop Seasons

Seasons organize crop activities by growth cycle.

### Key Points
- Season names can be edited later
- Annual crops: One season per crop entry
- Perennial crops: Multiple seasons, auto-prompted when marked "Sold"
- Season selector: Tap season info at top of crop detail screen
- Options: Specific Season, All Seasons, Active Season
- Selected season affects data displayed AND which season new actions are recorded under

---

## Livestock Types & Options

| Animal Type | Raised For Options |
|-------------|-------------------|
| Cattle | Dairy, Meat, Breeding, Others |
| Poultry | Egg, Meat, Breeding, Others |
| Goat | Meat, Dairy, Breeding, Others |
| Sheep | Meat, Breeding, Others |
| Pig | Meat, Breeding, Others |
| Others | Meat, Dairy, Breeding, Others |

### Individual Tracking
Only available for: **Cattle + Dairy + Track Individually ON**

---

## Inventory Categories

### Consumables (Added/Used/Reversal)
Seeds, Fertilizers, Pesticides, Herbicides, Fuel, Spare Parts, Feed, Health

### Producibles (Produced/Sold/Reversal)
Yield - harvested produce stored before sale

---

## Documentation Structure

```
content/en/
├── _index.md                 # Homepage
└── docs/
    ├── getting-started/
    │   └── _index.md
    ├── modules/
    │   ├── _index.md
    │   ├── farm.md
    │   ├── crops/
    │   │   ├── _index.md
    │   │   └── seasons.md    # Nested under crops
    │   ├── fields.md
    │   ├── livestock.md
    │   ├── machines.md
    │   ├── inventory.md
    │   ├── contacts.md
    │   └── roles.md
    ├── actions/
    │   ├── _index.md
    │   ├── income.md
    │   ├── expenses.md
    │   ├── tasks.md
    │   ├── notes.md
    │   ├── yields.md
    │   ├── documents.md
    │   └── animals.md
    └── faq/
        └── _index.md
```

---

## Writing Guidelines

### Article Structure
1. Title and intro paragraph
2. Key Features (### headings)
3. Tables for structured data
4. Supported Actions (if module)
5. Reports section (if applicable)
6. Tips
7. Frequently Asked Questions (use `<details>` tags)

### Style
- Keep modules **separate** - never combine (e.g., "Crops & Fields")
- Use tables for structured information
- Use `>` blockquotes for tips and important notes
- Use `<details><summary>` for FAQs
- Navigation paths: **Bold** → [Brackets] → Regular text

### Hugo Shortcodes
- Internal links: `{{< relref "/docs/modules/crops" >}}`
- External links: Standard markdown `[text](url)`

---

## Languages

- English: `content/en/`
- Tamil: `content/ta/` (தமிழ்)

---

## Theme Customization

- Custom CSS: `assets/_custom.scss`
- Custom partials: `layouts/_partials/`
- Menu config: `hugo.toml` under `[menu]`

### CTA Styling
Download App button uses class `cta-download` for green highlighted styling.

---

## Commands

```bash
# Run dev server
hugo server

# Build for production
hugo --minify
```
