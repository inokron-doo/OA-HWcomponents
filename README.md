# SFS LoRa Sensor Network Node

Open-source dual-role IoT hardware node for feed-level and microclimate
monitoring in livestock barns. A single PCB serves as either a **sensor node**
or a **LoRa concentrator** — the role is set by firmware only.

Developed by **Inokron d.o.o.** for the **SmartFeed Feed Monitoring System (SFS)**
under the OpenAgri EU project (SIP13).

- **Version:** v0.1
- **Release date:** 2026-06-17
- **Licence:** [CERN-OHL-S v2.0](LICENSE) (strongly reciprocal open hardware)
- **Status:** Initial public release — see *Release status* below.

## Repository structure

```
OA-HWcomponents/
├── README.md                  This file
├── LICENSE                    CERN-OHL-S v2.0
├── CHANGELOG.md               Version history
├── docs/                      Full hardware documentation (.docx)
├── electronics/
│   ├── schematic/             Schematic export (PDF)
│   ├── gerbers/               PCB fabrication outputs (Altium) + zip
│   └── bom/                   Bill of Materials (CSV)
└── mechanical/                Enclosure / mount STL files
```

## Release status — what is and isn't included in v0.1

This is a staged release made to meet the OpenAgri submission deadline. The
following materials are **planned for a later update**:

| Item | Status | Expected |
|------|--------|----------|
| Gerber fabrication files | ✅ Included | — |
| Schematic (PDF export) | ✅ Included | — |
| Bill of Materials | ✅ Included | — |
| Enclosure / mount STL files | 🟡 Pending | — |
| Schematic + PCB **source files** (Altium) | ⬜ Not yet | After June 2026 |
| Firmware | ↗ Separate repos | See below |

> Under CERN-OHL-S, full editable source (Altium project files) constitutes the
> "Complete Source" and will be added in a subsequent release once available.

## Firmware

The hardware is role-agnostic; two firmware variants run on the same PCB:

- **Sensor node firmware** — *(repository link TBD)*
- **Concentrator node firmware** — *(repository link TBD)*

Both are documented in the separate Open Software submissions.

## Documentation

Full hardware documentation (identification, architecture, electronics,
mechanical, BOM, assembly, testing, compliance, licensing) is in
[`docs/SFS_Node_Hardware_Documentation_v0.1.docx`](docs/).

## Citation

> Inokron d.o.o. (2026). *SFS LoRa Sensor Network Node v0.1.*
> OpenAgri EU project, SIP13. https://github.com/Inokron/OA-HWcomponents

## Contact

Inokron d.o.o., Kranj, Slovenia — info@inokron.com

---

*Funded by the European Union under the OpenAgri project (SIP13). Views and
opinions expressed are those of the authors only.*
