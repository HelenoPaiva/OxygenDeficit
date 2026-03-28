# Oxygen Deficit Calculator

A lightweight web-based teaching tool for evaluating gas exchange using **oxygen deficit** and **A–a gradient**.

🔗 **Live app:** https://helenopaiva.github.io/OxygenDeficit/

---

## Overview

This app estimates arterial oxygenation and compares:

- **Oxygen Deficit** (derived from expired O₂)
- **A–a Gradient** (classical alveolar gas equation)

It is designed for use with anesthesia machines (e.g., Mindray A7) that display **inspired and expired O₂ as vol%**, rather than partial pressure.

---

## Key Features

- SpO₂ → PaO₂ estimation (Hill-type model)
- Conversion of **expired O₂ (vol%) → PO₂**
- Real-time calculation of:
  - Oxygen Deficit
  - A–a Gradient
- Side-by-side comparison
- Minimal, fast, no dependencies

---

## Inputs

- SpO₂ (%)
- Inspired O₂ (vol%)
- Expired O₂ (vol%)
- End-tidal CO₂ (mmHg)
- Barometric pressure (mmHg)
- Respiratory quotient (R)

---

## Equations
Expired PO₂ ≈ (expired O₂ / 100) × (PB − 47)

PAO₂ = FiO₂ × (PB − 47) − PETCO₂ / R

Oxygen Deficit = expired PO₂ − estimated PaO₂

A–a Gradient = PAO₂ − estimated PaO₂

## Purpose

This tool highlights a practical teaching concept:

> Oxygen deficit provides a noninvasive approximation of gas exchange impairment using readily available monitor data.

---

## Disclaimer

This is a **teaching tool only**.

- Uses simplified physiological assumptions  
- PETCO₂ is used as a surrogate for PaCO₂  
- SpO₂-derived PaO₂ is an approximation  

**Not intended for clinical decision-making.**

---

## Author

Developed and maintained by
**Heleno de Paiva Oliveira, MD, PhD**
Professor of Anesthesiology
Universidade Federal do Rio Grande do Norte (UFRN)
