---
title: "Animals"
weight: 7
---

# Animals Action

Manage individual animal profiles within your dairy cattle livestock for detailed per-animal tracking.

## Purpose

Track detailed information about each dairy animal including breed, health, breeding cycle, lineage, and milk production. This enables per-animal yield recording and helps identify top performers.

---

## Availability

> **Important:** This action is only available when ALL conditions are met:
> - Module: **Livestock**
> - Animal Type: **Cattle**
> - Raised For: **Dairy**
> - **Track Individually**: ON
>
> If you don't see the Animals action, verify these settings in your livestock entry.

---

## Key Features

- **Individual profiles** - Name/ID, breed, gender, birth date
- **Growth tracking** - Monitor life stages from calf to adult
- **Breeding management** - Track reproductive cycle status
- **Milk production** - Record yields per animal
- **Lineage records** - Sire and Dam parentage
- **Lifecycle status** - Active, Sold, or Deceased

---

## Animal Profile Fields

### Basic Information

| Field | Description |
|-------|-------------|
| **Name/ID** | Unique identifier (e.g., "Lakshmi", "Cow-001") |
| **Breed** | Breed of the animal (e.g., HF, Jersey, Murrah) |
| **Gender** | Male or Female |
| **Date of Birth** | Birth date for age tracking |
| **Growth Stage** | Current life stage |

---

### Breeding Cycle

Track reproductive status of female animals:

| Status | Description |
|--------|-------------|
| **Open** | Not bred, ready for breeding/insemination |
| **Bred** | Mated or inseminated, not yet confirmed pregnant |
| **Pregnant** | Pregnancy confirmed, expecting calf |

Update breeding status as the animal progresses through the reproductive cycle.

---

### Milking Status

| Status | Description |
|--------|-------------|
| **Dry** | Not producing milk (late pregnancy, rest period) |
| **Milking** | Actively producing milk |

Toggle between Dry and Milking as the animal's production status changes.

---

### Lactation Number

Tracks how many lactation cycles (calving + milk production periods) the animal has completed.

| Lactation | Meaning |
|-----------|---------|
| 1 | First-time mother, first lactation |
| 2 | Second calving, second lactation |
| 3+ | Experienced producer |

Lactation number helps evaluate an animal's productivity over time.

---

### Parentage

| Field | Description |
|-------|-------------|
| **Sire** | Father of the animal |
| **Dam** | Mother of the animal |

Recording parentage helps:
- Track genetic lineage
- Make informed breeding decisions
- Avoid inbreeding
- Identify traits from parent lines

---

### Animal Status

| Status | Description |
|--------|-------------|
| **Active** | Currently in the herd, part of daily operations |
| **Sold** | Animal has been sold, records preserved |
| **Deceased** | Animal has died, records preserved |

Changing status to Sold or Deceased preserves historical records while removing the animal from active counts.

---

## Per-Animal Yield Tracking

With individual tracking enabled, you can record milk yields for each animal:

1. Go to the livestock entry
2. Open Yields action
3. Select the specific animal
4. Record the yield amount (in Liters)

This allows you to:
- Identify high producers vs low producers
- Track production trends per animal
- Make informed culling decisions
- Calculate feed efficiency per animal

---

## Tips

- Give each animal a unique, memorable identifier
- Record parentage to track lineage and make breeding decisions
- Update breeding cycle status promptly after each event
- Record milk yields consistently (same time each day)
- Update growth stages as animals mature
- Use Notes to record health observations per animal

---

## Best Practices

- **At birth/purchase** - Create animal record immediately with all known details
- **Daily** - Record milk yields during milking sessions
- **As events occur** - Update breeding status, health notes
- **Monthly** - Review animal records for completeness
- **At sale/death** - Update status to preserve records

---

## Frequently Asked Questions

<details>
<summary><strong>Why can't I see the Animals action?</strong></summary>

Animals action requires: Cattle + Dairy + "Track Individually" ON. Check your livestock entry settings. This feature is specifically designed for dairy cattle where individual production tracking is valuable.
</details>

<details>
<summary><strong>Can I track individual animals for poultry or goats?</strong></summary>

Currently, individual tracking is only available for dairy cattle. For other livestock types, animals are managed as a group/flock.
</details>

<details>
<summary><strong>How do I record milk yield per cow?</strong></summary>

Go to Yields action within the livestock entry. When individual tracking is enabled, you can select the specific animal before recording the yield.
</details>

<details>
<summary><strong>What happens when I mark an animal as Sold?</strong></summary>

The animal is removed from active herd counts but all historical records (yields, health notes, etc.) are preserved for reference.
</details>

<details>
<summary><strong>How do I track breeding events?</strong></summary>

Update the Breeding Cycle field as events occur: Open → Bred (after insemination) → Pregnant (after confirmation). Use Notes to record specific dates and details.
</details>

<details>
<summary><strong>What is lactation number used for?</strong></summary>

Lactation number indicates how many times the animal has calved and completed a milk production cycle. Higher lactation numbers indicate experienced producers. Productivity often peaks around lactation 3-5.
</details>

<details>
<summary><strong>How do I track health records per animal?</strong></summary>

Use Notes action to record health observations. Use Documents to attach veterinary prescriptions and vaccination records. Link each to the specific animal for organized records.
</details>
