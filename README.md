# Amphora Stamps — Computational Analysis of Roman Trade Networks

![Python](https://img.shields.io/badge/Python-Data_Analysis-blue?style=for-the-badge&logo=python&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-Machine_Learning-orange?style=for-the-badge&logo=scikitlearn&logoColor=white)
![Archaeology](https://img.shields.io/badge/Domain-Computational_Archaeology-8e44ad?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

Computational analysis of Roman amphora stamp distributions using machine learning and spatial inference techniques.

The project explores how geographic coordinates alone can be used to reconstruct patterns of provincial association across archaeological records from the Roman Empire.

---

## Overview

This repository contains a machine learning analysis of amphora stamp data derived from the CEIPAC database and the work of Rubio et al. (2018).

Using spatial coordinates as predictive features, the project investigates whether provincial origin can be inferred from archaeological distribution patterns, while also examining anomalous or unexpected classifications as historically meaningful signals rather than simple model errors.

The project combines:

- exploratory spatial data analysis
- supervised machine learning
- geographic visualization
- interpretive analysis of prediction uncertainty
- computational approaches to historical reconstruction

---

## Repository Structure

```text
.
├── Amphora stamps.ipynb
├── stamps.csv
└── README.md
```

| File | Description |
|---|---|
| `Amphora stamps.ipynb` | Full computational workflow including EDA, preprocessing, modeling, evaluation, and interpretation |
| `stamps.csv` | Archaeological amphora stamp dataset |
| `README.md` | Project documentation |

---

## Dataset

The dataset contains approximately **24,000 amphora stamp records** collected from archaeological contexts across the Roman Empire.

Features include:

- latitude and longitude coordinates
- stamp classifications
- site identifiers
- maker codes
- Roman provincial attribution

### Source

Rubio-Campillo, X. et al. (2018)

> Simulating archaeological data and processes: A case study of Roman amphora stamps.

DOI:
https://doi.org/10.1016/j.jas.2018.02.010

Original repository:
https://github.com/xrubio/ecologyStamps

---

## Methodological Approach

The workflow includes:

- spatial exploratory data analysis
- geographic frequency visualization
- preprocessing and feature selection
- Random Forest classification
- predictive evaluation on archaeological locations
- interpretive analysis of anomalous predictions

Particular attention was given to separating:

- descriptive analysis
- predictive modeling
- interpretive historical reasoning

rather than treating model output as automatically authoritative.

---

## Key Findings

- Geographic coordinates alone produced strong predictive performance for provincial attribution.
- Spatial clustering patterns aligned closely with known historical geography.
- Several unexpected classifications emerged in specific regions, suggesting:
  - uneven data density
  - overlapping trade influence
  - historical ambiguity
  - or latent structure within the dataset itself.

Rather than discarding anomalous outputs, the project treats them as exploratory signals worthy of further historical investigation.

---

## Technical Stack

- Python
- pandas
- scikit-learn
- matplotlib
- seaborn
- Jupyter Notebook

---

## Running the Project

### Requirements

- Python 3.x
- Jupyter Notebook

### Installation

```bash
pip install pandas scikit-learn matplotlib seaborn notebook
```

### Launch

```bash
jupyter notebook
```

Then open:

```text
Amphora stamps.ipynb

```

---

## Research Perspective

This repository is part of a broader interest in computational humanities and AI-assisted exploratory analysis for historical datasets.

The goal is not simply predictive accuracy, but the use of machine learning systems as tools for structured historical inquiry and interpretive exploration.

---

## Acknowledgments

Dataset and original archaeological framework:

Rubio-Campillo, X. et al. (2018)

CEIPAC — Centre for the Study of Provincial Interdependence in Classical Antiquity


