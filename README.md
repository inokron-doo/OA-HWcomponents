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


## Firmware

The hardware is role-agnostic; two firmware variants run on the same PCB:

- **Sensor node firmware:** https://github.com/inokron-doo/OA-Sensor
- **Concentrator node firmware** — https://github.com/inokron-doo/OA-Concentrator

Both are documented in the separate Open Software submissions.

## Documentation

OS component documentation (identification, architecture, electronics,
mechanical, BOM, assembly, testing, compliance, licensing) is in
[`docs/SFS_Node_Hardware_Documentation_v0.1.docx`](docs/).


## Contact

Inokron d.o.o., Kranj, Slovenia — info@inokron.com

---

*Funded by the European Union under the OpenAgri project (SIP13). Views and
opinions expressed are those of the authors only.*
