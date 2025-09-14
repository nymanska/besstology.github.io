---
title: "⚡️ What Is a Grid-Forming Inverter?"
date: 2025-07-27 21:00:00 +0100
categories: [Knowledge Base, Grid-Forming Inverters]
tags: [grid-forming, black-start, grid-following, IBR, GFM, GFI]
image:
  path: https://www.besstology.com/assets/img/2025/july/banner-grid-forming-inverter.png
  lqtip:
author: gustav
---

### 📌 TL;DR

- Grid-forming inverters (GFM) operate as voltage sources  
- They set local voltage and frequency references
- Enable islanded operation and often black start capability

---

## Introduction

As power systems transition to high density of inverter-based resources (IBRs), maintaining stability without synchronous machines becomes a core challenge.  
Grid-forming inverters (GFMs) are emerging as a key technology to meet this need. This article explains what they are, how they differ from grid-following inverters, and their role in the evolving grid.

---

## What Is a Grid-Forming Inverter?

A grid-forming inverter is a power electronic device that establishes and regulates local voltage and frequency—similar to the behavior of a synchronous generator.  
Unlike traditional inverters, it does not rely on an external voltage reference. Instead, it defines grid conditions at its connection point.

GFM inverters are capable of:

- Self-establishing voltage and frequency
- Stabilizing weak or islanded grids
- Enabling black start (when designed accordingly)
- Supporting system restoration after faults
- Operating independently of synchronous generation

> “GFM IBR controls maintain an internal voltage phasor that is constant or nearly constant in the sub-transient to transient time frame.” — UNIFI/NERC definition, as cited by NREL (2024)
{: .prompt-info }

---

## Grid-Forming vs. Grid-Following

| Characteristic            | Grid-Forming (GFM)           | Grid-Following (GFL)     |
| ------------------------- | ---------------------------- | ------------------------ |
| Control mode              | Voltage source               | Current source           |
| Synchronization           | Self-synchronizing           | PLL-based (follows grid) |
| Operation in weak grids   | ✅ Stable                     | ❌ Typically unstable     |
| Islanded operation        | ✅ Supported                  | ❌ Not possible           |
| Response to disturbances  | Fast (voltage control-based) | Slower (PLL tracking)    |
| Black start capability    | ✅ If designed for it         | ❌ Not supported          |
| Synthetic Inertia capability | ✅ Yes                        | ❌ No                     |

> “GFM inverters emulate voltage source behavior and can support fault current, inertia, and frequency stabilization, even in the absence of synchronous machines" — ENTSO-E, 2020 Technical Report
{: .prompt-info }

---

## Why Grid-Forming Matters

High penetration of IBRs introduces new system-level challenges:

- Low inertia
- Limited fault current
- Reduced voltage stability

Grid-forming inverters help mitigate these by:

- Providing synthetic inertia
- Acting as reference sources in low-inertia systems  
- Enabling islanding, black start, and system restoration  
- Supporting fault ride-through and reactive power services

> “Without grid-forming capabilities, achieving system stability with very high shares of inverter-based resources is not possible.” — ENTSO-E  
{: .prompt-info }

---

## Real-World Adoption

- **Kauai, Hawaii** operates with up to 90% inverter-based generation, stabilized using grid-forming battery systems  
- **National Grid ESO (GB)** has implemented GFM specifications (GC0137) and a Best Practice Guide for new connecting assets  
- **Nordic TSOs** are jointly developing GFM requirements to address declining inertia and cross-border system strength

> “GFM inverters allow converters to operate synchronously and instantaneously respond to disturbances, supporting the system like traditional synchronous machines.” — National Grid ESO & IEEE Power & Energy Magazine, 2025.
{: .prompt-info }

---

##  Summary for BESS Professionals

- Grid-following inverters inject current in response to an external voltage signal
- Grid-forming inverters generate their own voltage and frequency references
- For BESS applications, GFM is essential to enable black start, energization, and operation in weak or islanded networks

GFM is more than a control mode. It is a prerequisite for BESS to operate as active grid participants in high-IBR systems.

---

### References

- [ENTSO-E. (2020). High Penetration of Power Electronic Interfaced Power Sources and the Potential Contribution of Grid Forming Converters](https://www.entsoe.eu/network_codes/cnc/technical-groups/)  
- [National Grid ESO. (2023). Great Britain Grid Forming Best Practice Guide](https://www.neso.energy/document/278491/download)
- [NREL. (2024). Introduction to Grid Forming Inverters: A Key to Transforming our Power Grid](https://research-hub.nrel.gov/en/publications/introduction-to-grid-forming-inverters-a-key-to-transforming-our-)
- [IEEE Power & Energy Magazine. (2025). Best Practice: Grid-Forming Converter Technological Development in GB](https://ieee-pes.org/wp-content/uploads/2025/03/March-April-2025-open-Best_Practice_Grid-Forming_Converter_Technological_Development_in_Great_Britain.pdf)
- [Nordic TSOs. (2025). *Nordic Grid Development Perspective](https://www.svk.se/49e775/contentassets/cf866a8ab9dc42fa81e618ef69541a4e/nordic-grid-development---final.pdf)
