# Complete Electrical Wiring Design of a Multistoried Residential Building

**Course:** EEE-3205 — Electrical Services Design and Drafting
**Department of Electrical and Electronic Engineering, University of Dhaka**

Complete electrical wiring design of a **10-storied (GF + 9 typical floors)** multiple-unit residential building, with **2 units per typical floor** (each unit > 1301 sq. ft.), including layouts, circuit design, substation sizing, earthing, and lightning protection.

---

## 📋 Project Scope

| Item | Detail |
|---|---|
| Building type | Residential, multi-unit |
| Floors | Ground Floor (parking) + 9 typical floors |
| Units per typical floor | 2 |
| Unit area | > 1301 sq. ft. |
| Supply | 11 kV / 0.415 kV, 3-phase |
| Substation | 300 kVA transformer |

## 📁 Repository Structure

```
├── README.md
├── PDF
├── drawings/
│   ├── civil-layouts/           # Ground & typical floor civil plans
│   ├── fittings-fixtures/       # Fixture placement layouts
│   ├── conduit-layouts/         # Lighting & power conduit routing
│   ├── circuit-diagrams/        # Switch connections, SDB, MDB
│   ├── substation/              # SLD of 11/0.415 kV substation
│   ├── earthing/                # System earthing detail
│   └── lightning-protection/    # LPS layout & sizing
└── calculations/
    ├── load-and-breaker-sizing.md
    ├── substation-sizing.md
    └── lightning-risk-index.md
```

## 📑 Design Contents

1. **Civil Layouts** — Ground floor (parking, electrical room, guard room) and typical floor (2 units: bedrooms, living, dining, kitchen, toilets, balconies)
2. **Fittings & Fixture Layouts** — Fans, ceiling/wall/mirror lights, tube lights, sockets, switchboards, door bells, exhaust fans, SDBs
3. **Conduit Layouts** — Separate lighting and power-socket conduit schedules (BYM wiring with BYA ECC)
4. **Circuit Diagrams** — Switch connections (CKT G-1/G-2 for GF; CKT-1/2/3 per unit), Sub-Distribution Boards, Main Distribution Board
5. **SLD of Substation** — 11/0.415 kV, 300 kVA with HT/LT protection
6. **System Earthing** — GI pipe electrode with salt/coal layers
7. **Lightning Protection System** — Air terminals, roof conductor, down conductors, earth terminals

## ⚡ Key Design Figures

- **SDBs:** 19 total (SDB1 for GF, SDB2–SDB19 for typical floors), 70 A incomer each (30 A for GF)
- **Total current per phase:** 455 A → 70% demand → **318.5 A** → 300 A TP main breaker
- **Transformer:** 300 kVA, 11/0.415 kV
- **Power factor correction:** 180 kVAR
- **LT breaker:** 500 A | **HT breaker:** 20 A
- **Lightning risk index:** 52 → LPS required (8 air terminals, 4 down conductors)

## 🛠 Wiring Schedule (Typical)

| Purpose | Cable |
|---|---|
| Light/fan sub-circuits | 2×1.5 sq. mm BYM (+1.5 sq. mm BYA ECC) |
| Circuit feeders (CKT) | 2×2.5 sq. mm BYM + 2.5 sq. mm BYA ECC |
| Power sockets | 2×4 sq. mm BYM + 4 sq. mm BYA ECC |
| SDB feeder (typical floor) | 2×50 sq. mm BYM + 25 sq. mm BYA ECC |
| Main incomer | 2×240 sq. mm NYY + 120 sq. mm BYA ECC |

## 📄 License

Academic project — for educational reference only.
