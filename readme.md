# Lauv Market

**Lauv Market** is the official, server-managed market system for the ATM10 To The Sky server.

It provides a **controlled and balanced economy**, allowing players to buy and sell **approved items only**, while protecting progression, server performance, and fairness.

This system is intentionally simple at this stage and will expand over time.

---

## Purpose

Lauv Market exists to:

- Support progression without replacing it
- Prevent economy abuse and inflation
- Protect server TPS and stability
- Provide a fair trading environment for all players

This is **not** a free-for-all economy.

---

## Core Principles

- **Server-controlled prices**  
  All prices and items are defined by the server.

- **Performance-first design**  
  Automation and high-frequency interactions are restricted.

- **Progression-aware**  
  Items are unlocked gradually as the server evolves.

- **Fair play enforced**  
  Exploits, dupes, and automation abuse are not tolerated.

---

## Current Features

- Server-defined buy and sell prices
- Manual player interaction only
- Centralised configuration for items
- Designed for ATM10 To The Sky progression

> ⚠️ Lauv Market is in **early development**.  
> Item availability and pricing are subject to change.

---

## Tradable Items

Only **explicitly approved items** may be bought or sold.

Typical categories (subject to change):
- Basic resources
- Select processed materials
- Limited automation outputs

The following are **restricted or heavily limited**:
- Cobblestone
- Dirt
- Logs
- Infinite or trivial generators

If an item is not listed, it is **not tradable**.

---

## Automation Policy

Lauv Market is **not designed for automation**.

The following are **not allowed**:
- Command automation (e.g. ComputerCraft, scripts, macros)
- AFK sell loops
- Any attempt to bypass sell limits or cooldowns

Market abuse may result in:
- Market access removal
- Item or currency rollback
- Further moderation action

---

## Configuration Overview

Market behaviour is controlled through server-side configuration.

Typical configuration includes:
- Item ID
- Buy price
- Sell price
- Quantity limits
- Enabled/disabled state

Example (illustrative only):

```json
{
  "minecraft:iron_ingot": {
    "buy": 50,
    "sell": 25,
    "enabled": true
  }
}
