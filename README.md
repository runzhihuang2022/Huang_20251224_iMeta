# Huang_20251224_iMeta
Code and data for Huang et al., iMeta, 2025

This repository contains the source code and data to reproduce the figures for the following manuscript:

**Title:** BIOME cohort: multi-system microbiome dynamics and clinical outcomes in massive burn injury patients
**Journal:** *iMeta*
**Date:** December 24, 2025
**Project ID:** Huang_20251224_iMeta

## Repository Organization

The code is organized by main figures. Each folder corresponds to a figure in the manuscript and contains:
1. **Source Data:** Processed data files used for plotting (e.g., `.csv`, `.rds`).
2. **R Markdown Script:** `.Rmd` files containing the code to generate the plots.

* **Figure1/** (Generate by Biorender): Study design and data collection framework of the BIOME cohort. (A) Cohort map. The BIOME cohort is a multicenter, prospective, longitudinal study conducted across 50 hospitals spanning 28 provinces, autonomous regions, and municipalities in China (red panels). (B) Unified Timeline and Sampling Strategy. A total of 150 patients with MBIs will be enrolled into a single unified cohort. For all participants, multi-site biological sampling (skin, oral, and intestinal) is conducted longitudinally at standardized time points ranging from 1-2 ±   1 days post-burn (dpb) through 12 months post-burn (mpb). This comprehensive schedule covers the entire clinical trajectory, from the acute phase through wound re-epithelialization to long-term scar formation. Additionally, intensified daily sampling (1-3 days) is triggered immediately upon any clinical diagnosis of sepsis (blue panels). (C) Biological sample collection. Six categories of samples were obtained: (1) ICU environmental samples, (2) skin samples (swabs), (3) intestinal samples (stool, anal swab), (4) oral samples (oral swabs), (5) respiratory tract samples (sputum, alveolar lavage fluid, or bronchial aspiration fluid; optional), and (6) venous blood samples (optional) (left orange panels). Patient information. Collected metadata include: (1) personal information (prior health status, sex, age, height, weight); (2) injury information (cause, total body surface area, anatomical sites, concomitant injuries, admission photographs); (3) treatment information (pre-hospital emergency care, resuscitation and fluid therapy, wound management, infection prevention, nutritional support, complication prevention); (4) examination information (laboratory and imaging assessments); and (5) outcomes (new-onset sepsis, sepsis-related mortality, all-cause mortality, wound-healing time at sampling sites, and scar quality assessed by the Vancouver Scar Scale (VSS)) (right orange panels).
* **Figure2/** (Generate by R): Sample Collection of the BIOME Cohort (as of September 21, 2025). (A) Enrollment map showing the geographic distribution of patients across provinces in China. Provinces with enrollment are shaded, with circle sizes proportional to the number of enrolled patients. (B) Recruitment hospitals and corresponding patient counts are shown in a horizontal bar plot. The inset donut chart summarizes the causes of burn injury, with fire being the predominant cause. (C) Distribution of continuous variables including age, weight, height, BMI, hours from injury to hospital admission, TBSA, and burn depth area (superficial second-degree, deep second-degree, third-degree, fourth-degree). Density curves are overlaid with summary statistics (mean, SD, median, IQR, and range). (D) Donut charts illustrating categorical characteristics of the cohort, including gender, availability of burn ICU in the admitting hospital, marital status, work-related injury, scalp integrity, time to cryotherapy after injury, presence of inhalation injury, airway interventions (intubation or tracheotomy), incidence of sepsis during hospitalization, and survival outcome. (E) Progress of biological sampling overview. Bar plots display the number of samples collected across time points.

## Requirements

* R version 4.4.1
* Key libraries: `dplyr`, `ggplot2`, `readr`, `showtext` , `scales` , `RColorBrewer` , `sf` , `rnaturalearth` , `rnaturalearthdata` , `cowplot` , `tibble` , `purrr` , `grid` 

## How to Run

1. Clone or download this repository: `Huang_20251224_iMeta`.
2. Open the `.Rmd` file in RStudio.
3. Ensure the working directory is set to the source file location.
4. Run all chunks.

## Citation

If you use this code or data, please cite:
Huang, et al. (2026). BIOME cohort: Multi-system microbiome dynamics and clinical outcomes in massive burn injury patients, a multicenter, longitudinal, and prospective study. *iMeta*. Accepted.
