# Complex Rotators: Time-Series Analysis of M-Dwarf Light Curves

This repository contains code and analysis for an applied astronomy research project investigating **complex rotator M-dwarf stars** using time-series photometric data from the **TESS** and **K2** space telescope missions.

The project focuses on how **phase-folded light curve morphology evolves over multi-year timescales** and what physical mechanisms may drive these changes.

This repository supports an **active, in-progress peer-reviewed manuscript**.

---

## Project Context

Since May 2025, I have worked with the Brown Dwarfs in New York City (BDNYC) collaboration on a research project studying M-dwarf stars exhibiting complex rotator variability. These objects display light curve morphologies that deviate from simple sinusoidal light curves due to known causes like starspots or exoplanets and evolve measurably across observing campaigns/sectors.

This work is supported by a selective, NSF-backed **AstroCom NYC undergraduate research fellowship**.

---

## My Role & Ownership

I had primary, end-to-end ownership of the **data acquisition, validation, analysis tooling, and exploratory analysis**, collaborating closely with a postdoctoral researcher at the American Museum of Natural History.

Key responsibilities included:

- **Data acquisition & validation**
  - Compiled and standardized a comprehensive dataset of all known complex rotators identified in the literature
  - Retrieved and validated corresponding light curves across multiple surveys (TESS, K2)
  - Designed workflows to reproducibly pull and preprocess large public datasets

- **Analysis tooling**
  - Designed custom Python-based visualization tools to support systematic analysis at scale
  - Built multi-panel plotting utilities to enable consistent manual inspection and comparison of hundreds of phase-folded light curves across epochs

- **Exploratory analysis & synthesis**
  - Manually reviewed the full dataset to catalog morphological features
  - Produced summary statistics and exploratory visualizations to surface trends and edge cases

- **Communication & collaboration**
  - Contributed analysis code, figures, and methodology text to an in-progress paper
  - Presented a 10-minute research talk at the **American Museum of Natural History Undergraduate Summer Research Symposium** (Summer 2025)
  - Owned execution-level technical decisions while contributing to scientific interpretation and project direction

---

## Problem → Approach → Outcome

### Problem
Complex rotator M-dwarfs exhibit evolving, unusual phase-folded light curve morphology that is difficult to explain with typical periodic variability causes. Prior work often focuses on single time periods or small samples, limiting insight into temporal evolution.

### Approach
- Aggregated a multi-survey, multi-time period dataset of known complex rotators
- Standardized phase-folding and visualization across time periods
- Developed tooling to enable side-by-side morphological comparison at scale
- Performed systematic manual classification supported by summary statistics and exploratory plots

### Outcome
- Created a unified, validated dataset suitable for longitudinal analysis
- Identified recurring morphological patterns and notable edge cases across timescales
- Generated figures and analysis supporting an active peer-reviewed manuscript
- Established a reusable analysis framework for future expansion of the sample

---

## Data Access

Due to size constraints, **light curve data files are not included directly in this repository**.

- All underlying data originate from **public survey data**
- Some datasets were further processed and standardized as part of this project
- This repository includes code and documentation to **reproduce data retrieval and preprocessing workflows**

