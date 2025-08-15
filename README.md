<img src="products/Spiketon%20M1/images/Green%20Spiketon%20M1.png" alt="Spiketon M1 Actuator" width="300">
<img src="products/Guided%20Spiketon%20T1/images/Spiketon%20T1.png" alt="Spiketon T1 Actuator" width="300">

# Spiketon-Actuators

# SpikeTon Actuators — Open-Source Piezo Linear Motion (CERN OHL-P v2)

[![License: CERN OHL-P v2](https://img.shields.io/badge/License-CERN%20OHL--P%20v2-blue.svg)](./LICENSE)
[![Discussions](https://img.shields.io/badge/Community-Discussions-black?logo=github)](../../discussions)
[![Docs](https://img.shields.io/badge/docs-index-informational.svg)](./docs/README.md)

> Ultra-compact, high-force **piezo** actuators for robotics, precision automation, and embedded systems.  
> Hardware, electronics, firmware, CAD, and docs are **fully open** under **CERN OHL-P v2**.

---

## 🎬 Project video (1 min) & what this does

> _Replace with your real links once ready._

- ▶️ **Watch:** [SpikeTon overview video](https://youtu.be/XXXXXXXXXXX)  
  (or add a local MP4 at `docs/media/demo.mp4`)

- **What this project does**
  - Provides **tiny, high-force linear actuators** driven by piezo stacks.
  - Enables **clean, precise motion** without magnets, gearboxes, oil, or belts.
  - Operates in **tight spaces** and harsh environments (vacuum, radiation, non-magnetic).
  - Includes **CAD, electronics, firmware, and assembly docs** so anyone can build, adapt, and commercialize.

---

## 🔎 At a glance

| Property                | Spec / Notes *(fill in as you validate)*                                 |
|---                      |---                                                                        |
| Typical drive           | 100–150 V piezo drive (sine or stepped)                                   |
| Nominal force           | _TBD_ N (single stack ~100–300 N design range)                            |
| Stroke / step           | _TBD_ mm / sub-mm stepping                                                |
| Frequency range         | Up to ultrasonic regimes (variant-dependent)                              |
| Key features            | Non-magnetic, radiation-tolerant, vacuum-compatible, low profile          |
| Materials               | Spring steel / titanium alloys / ceramics (variant-dependent)             |
| License                 | CERN OHL-P v2 (permissive open hardware)                                  |

> Add measured plots in `docs/performance/` and link them here when available.

---

## 🧭 Repo layout


---

## 🧪 Quick start (10 minutes)

1. **Power & driver**  
   Bench PSU up to **0–150 V** (per variant limits) + piezo driver (see `/electronics/`).

2. **Wire it**  
   Follow the wiring diagram in the product’s folder (`/products/<variant>/`).

3. **Signal**  
   Start with a low-amplitude sine at a few hundred Hz, then sweep to find a stable operating region.

4. **Observe motion**  
   Expect sub-mm stepping or amplified stroke (variant dependent).

> ⚠️ **High-voltage safety**: Piezo drivers can be lethal. Use insulated connectors, one-hand rule, ESD protection, and follow creepage/clearance best practices. See `docs/safety.md`.

---

## 🧩 Build: CAD → electronics → firmware

- **CAD** (`/cad/`): export **STEP/STL** + annotated **2D drawings** (dims/tolerances/materials).  
- **Electronics** (`/electronics/`): KiCad sources + **PDF schematics**, **Gerbers**, **BOM.csv**, driver limits (Vmax/Imax).  
- **Firmware** (`/firmware/`): minimal driver examples (Arduino / PlatformIO / STM32), timing diagrams, recommended waveforms.  
- **Docs** (`/docs/`): assembly guides, test procedures, performance plots (force vs. voltage/frequency, displacement).

---

## 🧭 Products (jump straight in)

> Each link should point to a product folder with: **images**, **CAD ZIP**, **docs**, and **examples**.

- **Spike AA1 — Amplified actuator v1** → [`/products/spike-aa1/`](products/spike-aa1/)  
- **Spike AA2 — Amplified actuator v2** → [`/products/spike-aa2/`](products/spike-aa2/)  
- **Spike Rotary Motor R1 — Rotary piezo concept** → [`/products/spike-rotary-r1/`](products/spike-rotary-r1/)  
- **Guided SpikeTon T1 — Guided rail variant** → [`/products/guided-spiketon-t1/`](products/guided-spiketon-t1/)  
- **Guided SpikeTon T2 — Updated guided design** → [`/products/guided-spiketon-t2/`](products/guided-spiketon-t2/)  
- **SpikeTon M2 — Minimal-BOM linear** → [`/products/spiketon-m2/`](products/spiketon-m2/)  
- **SpikeTon Muscle SM1 — Wire/rod rider** → [`/products/spiketon-muscle-sm1/`](products/spiketon-muscle-sm1/)

> If a link 404s, create the folder and add a minimal `README.md` + assets checklist.

---

## 🔌 Applications

- Precision motion (XY stages, dispensers, 3D printers, laser positioning)  
- Embedded automation where **motors don’t fit** (flat, non-magnetic, clean)  
- Medical / lab tools (low EMI, compact, no lubrication)

Add your integrations under `/examples/` with photos/GIFs and wiring notes.

---

## 🤝 Contributing

We welcome contributions (hardware, firmware, docs). Please:

1. Read **CONTRIBUTING.md**  
2. Open a **Discussion** for larger proposals  
3. File **Issues** with clear steps / photos / scope  
4. Submit a **PR** with description, images, and validation notes

Add issue/PR templates under `.github/` if you’d like structured reports.

---

## 💝 Donate / Sponsor

If this project helps your work, consider supporting ongoing development:

- **GitHub Sponsors:** _add your link here (e.g., `https://github.com/sponsors/SpikeDynamics`)_  
- **OpenCollective:** _add collective link here_  
- **One-time:** _PayPal or other link here_

Your support funds test hardware, documentation, and community help.

---

## 🧾 Licensing

This project is licensed under **CERN OHL-P v2** (Permissive).

- SPDX: `CERN-OHL-P-2.0`  
- See `LICENSE` for full terms and attribution requirements.  
- You may use, modify, and commercialize derivatives—credit appreciated.

---

## 🙋 Support & questions

- Start a thread in **Discussions**  
- Open an **Issue** for bugs or missing artifacts  
- For collaboration or sponsorship: open a Discussion titled **“Partnering”**
