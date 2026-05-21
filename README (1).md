# Ultra-Sensitive Profiling of Clonal Haematopoiesis in an Apparently Healthy West African Cohort

> **Status: Manuscript under review — data and results embargoed pending publication.**

---

## Overview

This repository contains the analysis code for a study characterising clonal haematopoiesis (CH) in a West African adult cohort using ultra-sensitive duplex sequencing. The work profiles somatic mutations in CH driver genes (*DNMT3A*, *TET2*, and others) in peripheral blood from adults recruited in Lagos, Nigeria.

Full results, methods, and author details will be made available upon publication.

---

## Repository Structure

```
CHIP_Nigeria/
├── notebooks/
│   ├── CHIP_Nigeria_MainManuscript.ipynb    # Main figures (Fig 1–8, Tables 1–2)
│   └── CHIP_Nigeria_Supplementary.ipynb     # Supplementary (Fig S1–S11, Tables S1–S2)
├── data/                                    # Input data (not tracked; see Data Availability)
├── figures/                                 # Exported figures
├── requirements.txt                         # Python dependencies
├── .gitignore
└── README.md
```

## Requirements

Python 3.10+. Install dependencies:

```bash
pip install -r requirements.txt
```

Or in Google Colab:

```python
!pip install pandas numpy scipy matplotlib seaborn statsmodels openpyxl
```

## Data Availability

Data are not publicly available pending publication. Access requests will be considered following peer review.

## License

MIT — see [LICENSE](LICENSE) for details.
