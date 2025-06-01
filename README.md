# 🏎️ Race Architect: F1 Strategy Simulator & Driver Performance Model

A data science project simulating and optimizing Formula 1 race strategies under uncertainty.  
The goal is to build a modular, reproducible engine for:

- 🛠 Tire degradation modeling
- 🧠 Race strategy optimization under stochastic conditions
- 👨‍✈️ Driver skill estimation controlling for car/team/circuit
- 📊 Dashboards to visualize simulation outcomes and performance metrics

---

## 🚀 Project Goals

- Learn data science deeply by building a complex, end-to-end system
- Practice production-grade workflows: version control, reporting, testing
- Showcase skills in simulation, modeling, visualization, and MLOps

---

## 📁 Project Structure

f1-strategy-simulator/
│
├── data/               # Raw and processed datasets
│   ├── raw/            # Unaltered data from FastF1 or other sources
│   └── processed/      # Cleaned, structured data for modeling
│
├── notebooks/          # Jupyter notebooks for EDA and experiments
│
├── src/                # Core project codebase
│   ├── ingest/         # Scripts for data collection
│   ├── features/       # Feature generation and transformation
│   ├── modeling/       # Degradation models, driver skill modeling
│   └── simulation/     # Race strategy engine and simulations
│
├── dashboards/         # Streamlit or Plotly Dash interfaces
│
├── reports/            # Weekly progress reports and data documentation
│
├── tests/              # Unit tests for modules
│
├── environment.yml     # Reproducible conda environment
└── README.md           # Project overview and usage instructions




---

## 📦 Tech Stack

- `FastF1`, `pandas`, `scikit-learn`, `statsmodels`
- `matplotlib`, `seaborn`, `plotly`, `streamlit`
- Version control via `git`, with GitHub for collaboration and issue tracking

---

## 📅 Status

- ✅ Project initialized (Week 1)
- ⏳ Next: data schema design + simulator skeleton
