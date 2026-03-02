# 🔬 Endometrial Cancer Disparity Analysis

**Independent Research Project** | Andria Chen

---

## 📌 Overview

This repository contains the materials from my first independent clinical data analysis project, investigating **genetic and biological differences in endometrial cancer between African American (AA) and Caucasian (CS) patients**. Using publicly available TCGA data from cBioPortal representing **443 de-identified patient tumor profiles**, this study identified novel biomarkers that may help explain observed racial disparities in endometrial cancer outcomes.

African American women face a **90% higher 5-year mortality risk** compared to Caucasian women, yet the molecular basis for this disparity remains underexplored. This study aims to address that gap.

---

## 🎯 Research Aims

1. Assess genetic and biological differences between AA and CS patients across TCGA prognostic groups
2. Evaluate genetic mutations that enable diagnostic discernment among prognostic groups

---

## 📂 Repository Contents

| File | Description |
|------|-------------|
| `manuscript.docx` | Full 20-page research manuscript |
| `poster.pdf` | Research poster |
| `slides.pdf` | Presentation slide deck |

---

## 🧬 Key Findings

- **Protein overexpression** of RAD51, MRE11, and CCNE1 may explain mortality rate disparities between AA and CS patients
- **Novel biomarkers** identified: SOCS3, VST2B, and URI1 mutations were significantly more prevalent in African American patients, and may aid in diagnosis and targeted treatment
- Findings suggest a need for more specific molecular tumor profiling of African American patients to elucidate the molecular basis of genomic disparity in endometrial cancers

---

## 🗃️ Data

- **Source:** [cBioPortal](https://www.cbioportal.org/) — Uterine Corpus Endometrial Carcinoma TCGA PanCancer Atlas
- **Sample size:** 443 patients (101 African American, 342 Caucasian)
- **Prognostic groups:** CN High (n=144), CN Low (n=134), MSI (n=131), POLE (n=34)

---

## 🛠️ Methods & Tools

- **Language:** R
- **Statistical tests:** Log-rank, Kruskal-Wallis, and Wilcoxon tests for survival and group comparisons
- **Visualizations:** Mutational frequency bar charts, jitter box plots, log ratio plots
- **Analysis areas:** Protein expression, tumor mutation burden, microbiome signatures, mutational frequency comparisons across racial and prognostic groups

---

## 📎 References

- Levine, D.A. et al. (2013). TCGA Comprehensive molecular characterization of endometrial carcinoma. *Nature.*
- Doll, K.M. et al. (2020). Racial disparities in endometrial cancer outcomes.
- Full reference list available in the manuscript.

---

*This project was completed independently as a high school research project at William A. Shine Great Neck South High School.*
