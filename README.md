<img src="products/Spiketon%20M1/images/Green%20Spiketon%20M1.png" alt="Spiketon M1 Actuator" width="300">
<img src="products/Guided%20Spiketon%20T1/images/Spiketon%20T1.png" alt="Spiketon T1 Actuator" width="300">


# SpikeTon Actuators Open-Source Piezo Linear Motion (CERN OHL-P v2)

[![License: CERN OHL-P v2](https://img.shields.io/badge/License-CERN%20OHL--P%20v2-blue.svg)](./LICENSE)
[![Discussions](https://img.shields.io/badge/Community-Discussions-black?logo=github)](../../discussions)
[![Docs](https://img.shields.io/badge/docs-index-informational.svg)](./docs/README.md)

> Ultra-compact, high-force **piezo** actuators for robotics, precision automation, and embedded systems.  
> Hardware, electronics, firmware, CAD, and docs are **fully open** under **CERN OHL-P v2**.

---

## 🎬 Project video (1 min) & what this does

> _Replace with your real links once ready._

- ▶️ **Watch:** [SpikeTon overview video](examples/)  
  

- **What this project does**
  - Provides **tiny, high-force linear actuators** driven by piezo stacks.
  - Enables **clean, precise motion** without magnets, gearboxes, oil, or belts.
  - Operates in **tight spaces** and harsh environments (vacuum, radiation, non-magnetic).
  - Includes **CAD, electronics, firmware, and assembly docs** so anyone can build, adapt, and commercialize.

---

## 🔎 At a glance

| Property                | Spec / Notes                                 |
|---                      |---                                                                        |
| Typical drive           | 100–150 V piezo drive (sine wave)                                   |
| Nominal force           | single stack ~300 N                            |
| Stroke / step           | _TBD_ mm / sub-mm stepping                                                |
| Frequency range         | Up to 20000HZ                              |
| Key features            | Non-magnetic, radiation-tolerant, vacuum-compatible, low profile          |
| Materials               | Spring steel / titanium alloys / ceramics (variant-dependent)             |
| License                 | CERN OHL-P v2 (permissive open hardware)                                  |


---

## 🧭 Repo layout

/cad → 3D models (.STEP, .STL, etc.)

/patents  → list of patents

/products  → list of products with /cad, /docs, /examples subfolders

/electronics → Schematics, PCB layouts

/firmware → Control libraries, drivers

/docs → Assembly instructions, performance data

/examples → Sample integrations, demos

LICENSE → CERN OHL-P v2 license text

README.md → This overview

CONTRIBUTING.md → Guidelines for contributors

---

## 🧪 Quick start (10 minutes)

1. **Power & driver**  
   Bench PSU up to **0–150 V** + piezo driver (see `/electronics/`).

2. **Wire it**  
   Follow the wiring diagram in the product’s folder (`/products/<variant>/`).

3. **Signal**  
   Start with a low-amplitude sine at a few hundred Hz, then sweep to find a stable operating region.

4. **Observe motion**  
   Expect sub-mm stepping or amplified stroke (variant dependent).

> ⚠️ **High-voltage safety**: Piezo drivers can be lethal. Use insulated connectors, one-hand rule, ESD protection, and follow creepage/clearance best practices.

---

## 🧭 Products (jump straight in)

- **Spike AA1 — Amplified actuator v1** → [`/products/spike-aa1/`](products/spike-aa1/)  
- **Spike AA2 — Amplified actuator v2** → [`/products/spike-aa2/`](products/spike-aa2/)  
- **Spike Rotary Motor R1 — Rotary piezo concept** → [`/products/spike-rotary-r1/`](products/spike-rotary-r1/)  
- **Guided SpikeTon T1 — Guided rail variant** → [`/products/guided-spiketon-t1/`](products/guided-spiketon-t1/)  
- **Guided SpikeTon T2 — Updated guided design** → [`/products/guided-spiketon-t2/`](products/guided-spiketon-t2/)  
- **SpikeTon M2 — Minimal-BOM linear** → [`/products/spiketon-m2/`](products/spiketon-m2/)  
- **SpikeTon Muscle SM1 — Wire/rod rider** → [`/products/spiketon-muscle-sm1/`](products/spiketon-muscle-sm1/)


---

## 🔌 Applications

- Precision motion (XY stages, dispensers, 3D printers, laser positioning)  
- Embedded automation where **motors don’t fit** (flat, non-magnetic, clean)  
- Medical / lab tools (low EMI, compact, no lubrication)

---

## 🤝 Contributing

We welcome contributions (hardware, firmware, docs). Please:

1. Read **CONTRIBUTING.md**  
2. Open a **Discussion** for larger proposals  
3. File **Issues** with clear steps / photos / scope  
4. Submit a **PR** with description, images, and validation notes

---

## 💝 Donate / Sponsor

If this project helps your work, consider supporting ongoing development:

- **GitHub Sponsors:
- **OpenCollective: 
- **One-time:

Your support funds test hardware, documentation, and community help.

---

## 🧾 Licensing

This project is licensed under **CERN OHL-P v2** (Permissive).

- SPDX: `CERN-OHL-P-2.0`  
- See `LICENSE` for full terms and attribution requirements.  
- You may use, modify, and commercialize derivatives credit appreciated.

---

## 🙋 Support & questions

- Have questions or want to contribute ideas? Visit our [GitHub Discussions](https://github.com/SpikeDynamics/Spiketon-Actuators/discussions) and share your thoughts!  
- Open an **Issue** for bugs or missing artifacts  
- For collaboration or sponsorship: open a Discussion titled **“Partnering”**
