---
title: "🌡️ EU F-gas Regulation 2024/573: Implications for BESS Cooling Systems"
date: 2025-09-22 07:30:00 0100
categories: [Knowledge Base, Compliance]
tags: [f-gas, regulation, r410a, bess-cooling, refrigerants]
image:
  path: https://www.besstology.com/assets/img/2025/september/eu-f-gas-regulation-for-bess-cooling.png
  lqtip:
author: gustav
published: false
---

### 📌 TL;DR

- **R410A (GWP ~2088)** is the dominant refrigerant in BESS DC-block chillers today.  
- **From 1 Jan 2027**, new chillers >12 kW using R410A can no longer be placed on the EU market.  
- Leak-check and detection requirements scale with refrigerant charge (measured in tCO₂e).  
- Splitting cooling capacity across multiple smaller units reduces leak-check burden but not the phase-out ban.  
- Next-generation BESS cooling must adopt **low-GWP refrigerants** (e.g., R290, R1234ze(E), CO₂).  

---

## Introduction

Thermal management is critical for DC Blocks in large-scale BESS plants. Most high energy density systems rely on **liquid cooling HVAC** integrated into the DC Blocks. The refrigerant of choice has been **R410A**, a hydrofluorocarbon (HFC) blend valued for efficiency and availability.  

However, under the **EU F-gas Regulation (EU) 2024/573**, R410A is now classed as a high-GWP refrigerant. It's use in new cooling equipment is subject to strict phase-down and eventual bans. This article explains the regulation’s impact on BESS design choices, operations, and compliance obligations.  

---

## R410A and Its GWP

- **Composition:** Blend of HFC-32 (GWP 675) and HFC-125 (GWP 3500).  
- **Weighted GWP:** ~2088 (50/50 mix).  
- **Implication:** Above all key GWP thresholds in the regulation (150 and 750).  

R410A is therefore **non-compliant in new medium-to-large chillers beyond 2027**.

---

## Regulation 2024/573: Key Provisions for BESS Cooling

### Placing on the Market
- **Chillers >12 kW:** Ban on GWP ≥750 refrigerants from **1 Jan 2027**.  
- **Chillers ≤12 kW:** Ban on GWP ≥150 from **1 Jan 2027**; all F-gases banned from **1 Jan 2032**.  
- **Self-contained refrigeration (non-chillers):** Ban on GWP ≥150 from **1 Jan 2025**.  

### Leak Checks and Detection
Obligations apply per piece of equipment, based on refrigerant charge expressed in **tCO₂e**:

| Threshold (R410A) | Charge | Obligation |
|-------------------|--------|------------|
| 5 tCO₂e | ~2.4 kg | Leak checks at least annually |
| 50 tCO₂e | ~24 kg | Leak checks every 6 months |
| 500 tCO₂e | ~240 kg | Leak detection system mandatory; quarterly checks |

### Servicing
- No immediate servicing ban for R410A in chillers.  
- Reclaimed/recycled R410A may be permitted after 2030s, but long-term availability will tighten.  

---

## Design Considerations: One Large vs. Several Small Units

- **Single large chiller:** Likely exceeds 5 tCO₂e → triggers frequent leak checks, possible detection system if very large.  
- **Multiple smaller chillers:** Each under 2.4 kg charge can avoid leak-check thresholds.  
- **Trade-off:** More units = more piping and complexity, but lower compliance overhead.  
- **Limit:** Regardless of configuration, R410A chillers >12 kW will be banned in 2027.  

---

## Alternatives to R410A

Low-GWP refrigerants entering the BESS cooling market:

| Refrigerant | GWP | ASHRAE Class | Notes |
|-------------|-----|--------------|-------|
| **R290 (propane)** | ~3 | A3 (flammable) | High efficiency; strict charge limits indoors |
| **R1234ze(E)** | <7 | A2L (mildly flammable) | Popular HFO for chillers; efficiency trade-offs |
| **R32** | 675 | A2L (mildly flammable) | Pure HFC; allowed in **>12 kW chillers after 2027**, but banned in **≤12 kW** (GWP >150). Efficiency better than R410A; widely available. |
| **R513A** | ~631 | A1 (non-flammable) | Drop-in for R134a; lower efficiency vs. R410A |
| **CO₂ (R744)** | 1 | A1 (non-flammable, high pressure) | Robust, but less efficient in high ambient temps |

Each alternative has **safety and performance implications** requiring redesign of chillers and container layouts.  

---

## Summary for BESS Professionals

- **R410A phase-out is imminent.** From 2027, new BESS chillers >12 kW must use refrigerants with GWP <750.  
- **Leak-check compliance** depends on per-unit charge — smaller units ease obligations but complicate plant BoP.  
- **Procurement timelines matter.** Systems contracted today for delivery after 2027 risk non-compliance if R410A is specified.  
- **Technology shift is unavoidable.** Expect rapid adoption of R290, HFOs, and CO₂-based chillers, each requiring new safety engineering and standards compliance.  

R410A has been the workhorse refrigerant for BESS cooling, but under EU law its days are numbered. Future-ready thermal management must combine **low-GWP refrigerants** with compliant designs to ensure both safety and regulatory alignment.  

---

**Source:** [REGULATION (EU) 2024/573 – European Parliament and Council on Fluorinated Greenhouse Gases (March 2024)](/mnt/data/REGULATION%20(EU)%202024-573.pdf)
