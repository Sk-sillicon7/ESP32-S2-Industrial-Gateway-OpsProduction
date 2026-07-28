# ⚙️ ESP32-S3 Industrial Gateway — Hardware Operations & Sourcing Package

[![JLCPCB Compatible](https://img.shields.io/badge/JLCPCB-SMT_Ready-blue?style=for-the-badge&logo=kicad)](https://jlcpcb.com/)
[![Lifecycle Status](https://img.shields.io/badge/Sourcing-Risk_Analyzed-brightgreen?style=for-the-badge)](#)
[![Documentation](https://img.shields.io/badge/Docs-Production_Grade-orange?style=for-the-badge)](#)

A high-availability, production-ready Hardware Operations package for an **ESP32-S3 Industrial Dual-Ethernet Gateway**. Structured specifically to eliminate supply-chain bottlenecks, zero-out CPL alignment errors, and streamline JLCPCB/LCSC automated assembly.

---

## 📌 Sourcing & Procurement Matrix

| Primary Component | LCSC Part # | Lifecycle | Alternate Part (DigiKey/Mouser) | Unit Price (1k Vol) |
| :--- | :--- | :--- | :--- | :--- |
| **ESP32-S3-WROOM-1-N16R8** | `C2913202` | **Active** | ESP32-S3-WROOM-1-N8R8 | **$2.65** |
| **W5500 Ethernet Controller** | `C31905` | **Active** | W5500-S2E | **$1.35** |
| **CP2102N UART Transceiver** | `C208138` | **Active** | CH340G | **$0.85** |
| **MP2307 Buck Regulator** | `C14256` | **Active** | LM2596S-5.0 | **$0.30** |

---

## 🚀 Assembly & Fabrication Readiness

1. **JLCPCB Automated SMT:** Complete `BOM.csv` configured with verified LCSC catalog IDs for zero manual mapping.
2. **Component Risk Mitigation:** Dual-sourced alternatives established for high-risk active ICs to prevent production halts during component shortages.
3. **Price-Break Optimization:** Quantity scaling analyzed across 1, 100, and 1000 unit manufacturing runs.

---

## 📁 Repository Directory

* `ESP32-S3-Gateway-JLCPCB-BOM - Sheet1.csv` — Primary production bill of materials formatted for direct JLCPCB auto-quote.
* `Sourcing_Risk_&_Pricing - Sheet1.csv` — Detailed pricing tiers, lifecycle status, and alternate part cross-references.

---
*Maintained by Hardware Ops Specialist*
