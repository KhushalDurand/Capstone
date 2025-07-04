# Dynamic Pricing for Urban Parking Lots

Open In Colab: (https://colab.research.google.com/drive/1hYfhvYSIPVm3z35eJRJjUr1LJLIHLG-u)

**Capstone Project – Summer Analytics 2025**  
**Hosted by:** Consulting & Analytics Club × Pathway, IIT Guwahati  

---

## Overview

Urban parking is a high-demand, limited resource. Static pricing causes overcrowding or underutilization.  
This project simulates a **real-time dynamic pricing system** using occupancy, queue length, traffic, vehicle type, and competitor pricing.

---

## Tech Stack

- **Python 3.10+**
- **Pandas, NumPy** — for data processing
- **Pathway** — for real-time simulation
- **Bokeh** — for visualizations
- **Google Colab** — as the development environment

---

## Architecture Diagram

```mermaid
flowchart TD
    A[CSV Dataset Upload] --> B[Pathway Stream Ingestion]
    B --> C[Preprocessed DataFrame]
    C --> D[PriceUpdate Engine]
    D --> E1[Baseline Model]
    D --> E2[Demand-Based Model]
    D --> E3[Competitive Model]
    E1 --> F[Final Price]
    E2 --> F
    E3 --> F
    F --> G[Price History DataFrame]
    G --> H[Bokeh Visualizations]

--

## Documantation
1.- ** source code file = capstone.ipynb **
2.- ** output (CSV file) = dataset_price.csv **


-----------------------------------------------------------------------------
-----------------------------------------------------------------------------
