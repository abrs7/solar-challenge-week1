# 🌞 Solar Data Analysis: Benin, Sierra Leone & Togo

This project explores solar energy potential across **Benin**, **Sierra Leone**, and **Togo** through data profiling, cleaning, and cross-country comparison. The goal is to identify key insights and visualize differences in solar metrics to guide potential energy decisions.

---

## 📁 Project Structure

```
├── app/                  # Streamlit dashboard code
│   ├── main.py
│   └── utils.py
├── data/                 # Local cleaned CSVs (not tracked in Git)
├── notebooks/            # Jupyter notebooks for EDA and comparison
│   ├── eda_benin.ipynb
│   ├── eda_sierra_leone.ipynb
│   └── compare_countries.ipynb
├── scripts/              # Helper scripts and README
├── requirements.txt      # Python dependencies
├── .gitignore
└── README.md             # You're here!
```

---

## ✅ Tasks Completed

### Task 1: Setup
- GitHub repo setup with branches and CI
- Virtual environment and `requirements.txt` configured

### Task 2: EDA & Cleaning
- Explored solar datasets per country
- Detected and removed outliers
- Imputed missing values
- Visualized time series, distributions, and correlations

### Task 3: Cross-Country Comparison
- Boxplots for GHI, DNI, DHI
- Summary table (mean, median, std)
- ANOVA test for statistical significance
- Bar chart ranking countries by average GHI

---



## 📦 How to Run

1. **Clone the repo**  
   ```bash
   git clone https://github.com/abrs7/solar-challenge-week1
   cd solar-challenge-week1
   ```

2. **Create & activate virtual environment**  
   ```bash
   python -m venv venv
   source venv/bin/activate  # or venv\Scripts\activate on Windows
   ```

3. **Install dependencies**  
   ```bash
   pip install -r requirements.txt
   ```

4. **Run notebooks via Jupyter or VS Code**



---

## 📌 Notes

- Datasets are stored locally under `data/` and excluded from version control.
- For dashboard deployment, you'll need to upload data manually to Streamlit Cloud.

---

