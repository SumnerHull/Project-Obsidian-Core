# 🖨️ Obsidian Core

**Obsidian Core** is a high-speed, open-source 3D printer platform designed for makers, prosumers, and tinkerers. Featuring a rigid CoreXY frame, Klipper firmware, and a large 350mm³ build volume — all wrapped in a sleek black & purple theme — this printer is built for performance, precision, and customization.

![Obsidian Core Logo](./assets/logo.png)

---

## 🔧 Project Goals

- 🧩 Fully modular and hackable architecture
- ⚡ High-speed CoreXY motion system (250–500 mm/s)
- 📦 Kit or preassembled options
- 🛠️ Open-source hardware and software
- 💰 Target price: Under $700 for the base kit

---

## 📐 Core Specs

| Feature         | Description                              |
|----------------|------------------------------------------|
| Build Volume    | 350 x 350 x 350 mm                       |
| Frame Material  | 2020 Aluminum Extrusion (Cube Frame)     |
| Motion System   | CoreXY + Triple Z Lead Screw w/ Belt Sync |
| Linear Motion   | MGN12 Linear Rails on all axes           |
| Print Speed     | 250–500 mm/s (Klipper Input Shaping)     |
| Hotend          | All-Metal, 300–400°C                     |
| Extruder        | Direct Drive (BMG-style or Orbiter)      |
| Nozzle          | Hardened Steel, 0.4mm (default)          |
| Firmware        | Klipper + Mainsail or Fluidd             |
| Control Board   | 32-bit (e.g. BTT SKR series)             |
| SBC             | Raspberry Pi or equivalent               |
| Bed Leveling    | Automatic Mesh (BLTouch or similar)      |
| Build Surface   | PEI Spring Steel on Heated Magnetic Bed  |

---

## 🚀 Quick Start

> ⚠️ Work in progress — CAD and firmware files coming soon!

1. Clone this repo  
   ```bash
   git clone https://github.com/SumnerHull/Project-Obsidian-Core.git
   ```
2. Check the `/docs` and `/firmware` folders for wiring diagrams and Klipper configs
3. Follow setup instructions in `/scripts/setup_klipper.sh` to flash your board
4. Customize `printer.cfg` for your build

---

## 📂 Repository Structure

```
obsidian-core/
├── assets/              # Logos, renders, screenshots
├── cad/                 # STEP files, Fusion files (soon)
├── firmware/            # Klipper configs, macros
├── scripts/             # Setup scripts for Klipper, Input Shaper, etc.
├── docs/                # Wiring diagrams, build guide
└── README.md
```

---

## 🧠 Philosophy

Obsidian Core is built on a few core ideas:

- **Modularity First**: Easy to upgrade and iterate
- **Speed with Stability**: CoreXY + linear rails tuned via Klipper
- **Hackable, Not Locked Down**: You own the hardware and the firmware
- **Accessible Performance**: Competes with commercial printers for a fraction of the price

---

## 📈 Roadmap

- [x] Frame design and BOM
- [x] Logo and branding
- [ ] CAD model release
- [ ] Full assembly guide (PDF & web)
- [ ] Pre-configured firmware + setup scripts
- [ ] Community contributions (add-ons, mods)

---

## ❤️ Contributing

Pull requests, mods, feedback, and ideas are all welcome.  
Check the [issues](https://github.com/sumnerhull/obsidian-core/issues) page or start a new discussion.

---

## 📝 License

This project is licensed under the MIT License.  
See [`LICENSE`](./LICENSE) for details.

---

## 💬 Join the Community

- Discord: _Coming Soon_
- Reddit: _Coming Soon_
- Docs site: _Coming Soon_

---

> Built with love, aluminum, and purple LEDs by Sumner Hull and Luis Gomez  
> _“Precision forged in obsidian.”_
