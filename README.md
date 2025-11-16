# Can Countries Grow Rich Without Destroying the Planet?

AM10 Group 5 — Final Poster Presentation

This repository contains our group project for the **LBS AM10** course.
We examine how **economic growth** relates to **CO2 emissions** across countries and over time, using descriptive statistics and a series of visualisations.

---

## 1. Project Overview

This project investigates several core questions:

1. **What is the current global landscape of carbon emissions and economic growth?**
2. **How have GDP and CO₂ emissions evolved over time for the world’s largest emitters?**
3. **Which countries are coupling or decoupling economic growth from carbon emissions?**
4. **Which countries are the strongest performers in reducing carbon intensity?**
5. **To what extent have major global climate agreements encouraged more sustainable growth?**

All analysis is implemented in **Python (Jupyter Notebook)**.

---

## 2. Repository Structure

```
.
├── groupproject_finalversion.ipynb        # Main analysis and visualisation notebook
├── data/                                  # Raw datasets
│   ├── gdpdata.csv
│   ├── gdppercapita.csv
│   ├── co2emissions.csv
│   ├── emissions_percapita.csv
│   └── GlobalTemperatures.csv
└── README.md                      # Project documentation
```

---

## 3. Data Sources

The project uses widely recognised, publicly available datasets from NASA, Berkeley Earth, and the World Bank:

* **NASA GISTEMP v4:**
  Global mean temperature anomalies, based on the Land–Ocean Temperature Index (L-OTI).
(File: globalmeananomalies.csv)

* **Berkeley Earth – Global Land Temperatures:**
  Monthly land-surface temperatures by country and global temperature series.
(Files: GlobalLandTemperaturesByCountry.csv, GlobalTemperatures.csv)

* **World Bank – World Development Indicators (WDI):**
  GDP (current US$), GDP per capita, CO₂ emissions (total and per capita, excluding LULUCF).
(Files: gdpdata.csv, gdppercapita.csv, co2emissions_total.csv, emissions_percapita.csv)

All datasets are stored in the `data/` folder.

---

## 4. Methodology

The analysis follows a structured workflow:

### Data Preparation

* Loaded temperature, GDP, GDP per capita, and CO₂ datasets from NASA, Berkeley Earth, and the World Bank.
* Cleaned data by removing metadata rows, standardising country names, reshaping year columns, and handling missing values.
* Created additional indicators such as carbon intensity (CO₂ per unit of GDP).

### Data integration

* Merged all datasets into a consistent country–year panel.
* Filtered for countries and years with reliable, overlapping data coverage.

### Analysis and visualisation
* Produced time-series comparisons for GDP, CO₂ emissions, and carbon intensity.
* Identified major emitters and tracked long-run trends.
* Assessed coupling/decoupling by comparing GDP growth with emissions trajectories.
* Used cross-sectional charts (bubble plots, bar-line charts) to highlight differences in carbon intensity and income levels.
* Examined changes in per-capita emissions around major climate agreements.

---

## 5. Key Insights

* Only 47 of 179 countries (26%) achieved GDP growth with falling emissions
* Advanced economies emit 20x less CO2 per dollar of GDP than resource-dependent nations
* 132 countries still linking growth to carbon account for 70% of emissions (26 Gt) and growing

* Use green bonds and carbon markets to make clean growth economically attractive for developing nations
* Help emerging economies leapfrog to clean production methods

---

## 6. How to Run the Notebook

### Option A: View on GitHub

The notebook (`finalgroup_aleV2.ipynb`) can be viewed directly on GitHub with no setup required.

### Option B: Run Locally

---

## 7. Contributors

* Jacopo Cometti
* Alessandro Condorelli
* Avery Dong
* Gizem Ergin
* Flora Fang
* Joseph Lyons
* Anushriya Roy

---

## 8. License

This repository is intended for academic use as part of the LBS AM10 course.
Please contact the authors before reusing the materials.

---
