# 🌞 Solar Challenge – Week 1

Welcome to the **Solar Challenge: Week 1**!  
This repository contains code, notebooks, scripts, and a dashboard for analyzing solar radiation data from various countries.

---

## 📂 Project Structure

```
solar-challenge-week1/
├── .vscode/                  # VS Code settings
├── .github/
│   └── workflows/            # GitHub Actions CI workflows
├── src/                      # Core source code (Python modules)
├── notebooks/                # Jupyter notebooks for exploration and analysis
├── tests/                    # Unit and integration tests
├── scripts/                  # Helper and automation scripts
├── data/                     # Local-only data (not committed to git)
├── .gitignore                # Git ignore rules
├── requirements.txt          # Python dependency list
├── README.md                 # Project documentation
```

---

## ⚙️ Getting Started

Follow these steps to get your local development environment set up:

### 1. Clone the Repository

```bash
git clone https://github.com/<your-username>/solar-challenge-week1.git
cd solar-challenge-week1
```

### 2. Set Up a Virtual Environment

Using Python’s `venv`:

```bash
python -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate
```

### 3. Install Required Packages

```bash
pip install -r requirements.txt
```

---

## 📊 Interactive Dashboard (Streamlit)

An interactive Streamlit dashboard is included for visual analysis and comparison of solar radiation data across different countries.

### 🔧 To Launch the Dashboard:

1. **Place cleaned data files** in the `data/` directory (e.g., `benin_clean.csv`, `sierraleone_clean.csv`, `togo_clean.csv`).  
   > ⚠️ The `data/` folder is excluded from version control—be sure to add your files locally.

2. **Run the Streamlit app:**

```bash
streamlit run app/main.py
```

3. **Visit the local URL** shown in the terminal (usually [http://localhost:8501](http://localhost:8501)).

### 🚀 Dashboard Highlights:
- **Country Selector** – Choose countries to compare.
- **Metric Selector** – Analyze variables like GHI, DNI, DHI, WS, etc.
- **Plot Types** – Visualize data as boxplots, histograms, line charts, or scatter plots.
- **Summary Stats** – Auto-generated tables showing mean, median, and standard deviation.
- **Insights Panel** – Dynamic text insights based on user selections.
- **Responsive UI** – Update plots and summaries instantly from the sidebar.

---

## 🧼 Best Practices

- **Data files** should **never** be committed. The `data/` folder is listed in `.gitignore`.
- All analysis code, notebooks, and dashboard files are versioned and tracked in this repository.

---

## 🔁 Sample Workflow

1. Clean your country-specific data and save as `<country>_clean.csv` in the `data/` folder.
2. Run the dashboard using `streamlit run app/main.py`.
3. Use the interactive sidebar to explore and analyze the data.

---

## 🤝 Contributions

We welcome contributions!  
To get involved:
1. Fork this repository.
2. Create a new branch.
3. Submit a pull request for review.

Happy hacking! ☀️
