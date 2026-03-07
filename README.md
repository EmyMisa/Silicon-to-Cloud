# Silicon to Cloud

> From atom to cloud. A ground-up relearning of everything — hardware, OS, networking, cloud, and security — documented as it's mastered.

---

## Why This Exists

Most engineers start at the framework and work backwards.  
This repo starts at the atom.

This is a living record of deliberately rebuilding foundational knowledge from first principles — no shortcuts, no skipping layers. Every concept here has been studied, broken down, and written in my own words.

The goal is not just to know how things work, but to understand *why* they work that way.

---

## The Map

| Layer | Topic | Status |
|-------|-------|--------|
| 01 | Hardware — atom, electricity, logic gates, CPU, system unit | ✅ Complete |
| 02 | Operating Systems | 🔜 Up next |
| 03 | Networking | ⬜ Pending |
| 04 | Security | ⬜ Pending |
| 05 | Cloud | ⬜ Pending |

---

## Layer 01 — Hardware

**Completed:** Cisco Hardware Basics

What was covered:

- **Atom & Electron Flow** — atomic structure, valence electrons, free electron drift, conductors vs insulators
- **Voltage, Current & Resistance** — Ohm's Law (V = IR), series vs parallel circuits, how power distribution works inside a system unit
- **Logic Gates & Binary** — AND / OR / NOT / NAND / XOR, boolean algebra, binary arithmetic, the half adder
- **Computers** — History, types 
- **CPU Components** — Control Unit, ALU, registers (PC, IR, MAR, MDR), cache hierarchy (L1/L2/L3), the fetch-decode-execute cycle
- **System Unit Layout** — motherboard, chipset, RAM (volatile/DRAM), SSD vs HDD, PSU voltage rails, PCIe data flow

📂 Notes: [`layers/01-hardware/`](layers/01-hardware/)  
🗺️ Interactive map: [View on GitHub Pages](index.html)
📜 Cisco Hardware Basics [https://www.credly.com/badges/4138b774-9466-4de2-8f33-ecd402afcf26/public_url]
---

## The Visualiser — Atom to System Unit

> *Imagined during Layer 01. Built progressively as skills grow.*

A single page that tells the entire hardware story visually — starting at a single atom and zooming out through every layer of abstraction to a fully assembled system unit.

**The journey:**
```
Atom → Electron → Conductor → Transistor → Logic Gate → CPU Die → CPU → Motherboard → System Unit
```

Hover over any component to see its name and what it does.  
Assemble or disassemble the system unit interactively.

**Build plan — grows with the learning:**

| Skill learned | What gets added |
|---------------|-----------------|
| HTML | Static layout, component placeholders |
| CSS | Components styled and correctly positioned |
| JavaScript | Hover tooltips, assembly/disassembly animation |
| C | Atom → transistor → gate sequence, data-driven component info |

📂 [`visualiser/`](visualiser/) — placeholder committed, built layer by layer.

---

## How This Repo Is Built

- All notes written by hand as each topic is studied
- The interactive knowledge map (`index.html`) is built from scratch using only HTML, CSS, and JavaScript — skills also being learned on this journey
- Each layer is added only when its predecessor is genuinely understood
- No AI-generated summaries of textbooks. Every word here reflects direct study.

---

## Tooling & Stack

| Tool | Purpose |
|------|---------|
| HTML / CSS / JS | Interactive knowledge map (learning as I go) |
| Git / GitHub | Version control and documentation |
| GitHub Pages | Hosting the knowledge map |
| Markdown | Layer notes and documentation |

---

## Repo Structure

```
silicon-to-cloud/
├── README.md
├── index.html              ← interactive knowledge map
├── layers/
│   ├── 01-hardware/        ← notes, diagrams, labs, references
│   ├── 02-os/              ← (coming soon)
│   ├── 03-networking/      ← (coming soon)
│   ├── 04-security/        ← (coming soon)
│   └── 05-cloud/           ← (coming soon)
├── visualiser/             ← atom → system unit interactive visualiser
└── mind-maps/              ← raw mind maps per topic
```

---

## Progress Log

| Date | Milestone |
|------|-----------|
| 2026-03-07 | Repo created. Layer 01 (Hardware) complete. `index.html` v1 published. Visualiser concept documented. Layers separated — Hardware, OS, Networking, Security, Cloud. |

*This table grows with every layer completed.*

---

## License

MIT — open to anyone who wants to learn the same way.
