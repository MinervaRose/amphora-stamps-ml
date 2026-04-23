# 🏺 Amphora Stamps — A CRISP-DM Analysis of Roman Trade

This project uses machine learning to analyze a dataset of Roman amphora stamps, following the **CRISP-DM** process. By predicting the provincial origin of stamped amphorae using only geographic coordinates, the project explores the role of data science in archaeology and historical reconstruction.

---

## 📁 Project Structure

- `Amphora stamps.ipynb` — Jupyter Notebook with full CRISP-DM workflow: EDA, modeling, testing, and conclusions.
- `stamps.csv` — The original dataset from [Rubio et al. 2018](https://github.com/xrubio/ecologyStamps).
- `README.md` — This file.

---

## 🔍 Dataset Description

The dataset includes **24,085 amphora stamps** found at archaeological sites across the Roman Empire. Each record contains:
- Coordinates (`lat`, `long`)
- Stamp type
- Site of discovery
- Maker’s code
- Roman province (`name`)

Source: CEIPAC database, via [Rubio et al. (2018)](https://doi.org/10.1016/j.jas.2018.02.010)

---

## 🔍 Questions Explored in This Project

1. What are the most common amphora stamp types in the dataset?
2. Which Roman provinces have the highest number of stamped amphorae?
3. Can we accurately predict a stamp’s province using only its geographic location?
4. How does the model perform when tested on known historical locations?
5. What can we learn from incorrect or surprising predictions?

Each of these questions is addressed using data visualization, machine learning, and critical interpretation.

---

## 🧠 What I Did

- Performed exploratory data analysis (EDA) using reusable, well-documented functions
- Visualized amphora stamp frequency and mapped geographic distribution
- Trained a modular, reusable Random Forest model to predict province from coordinates
- Applied the DRY (Don't Repeat Yourself) principle using functions with clear docstrings
- Explored and interpreted **unexpected model behavior**, using domain knowledge and critical thinking

---

## ✅ Key Results

- Model achieved **99.75% accuracy**
- Most predictions aligned well with historical geography
- Some test cases gave **surprising results** (e.g., multiple regions predicted as *Arabia*) — which turned out to be the **most interesting part** of the project, raising questions about data distribution and historical interpretation

---

## 🧰 Code Quality & Best Practices

- Code is modular and DRY-compliant
- All functions are reusable and documented with docstrings
- Clear separation between EDA, modeling, and evaluation steps

---

## 🗺️ How to Run

This project uses:
- Python 3.x
- Jupyter Notebook
- pandas, scikit-learn, seaborn, matplotlib

To run locally:
1. Download `stamps.csv` from [this repository](https://github.com/xrubio/ecologyStamps/blob/master/data/stamps.csv)
2. Open the notebook `Amphora stamps.ipynb`
3. Run each cell in order

---

## 🙏 Acknowledgments

- Dataset by [Rubio et al. (2018)](https://doi.org/10.1016/j.jas.2018.02.010)
- Hosted by the CEIPAC project


