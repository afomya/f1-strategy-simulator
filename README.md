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
<pre><code>f1-strategy-simulator/ │ ├── data/ # Raw and processed datasets │ ├── raw/ # Unaltered data pulled from FastF1 or other sources │ └── processed/ # Cleaned and feature-enriched datasets │ ├── notebooks/ # Jupyter notebooks for EDA and prototyping │ ├── src/ # Core project code │ ├── ingest/ # Scripts for downloading and parsing data │ ├── features/ # Feature engineering utilities │ ├── modeling/ # Driver skill estimation, degradation modeling │ └── simulation/ # Race simulation and strategy optimization logic │ ├── dashboards/ # Streamlit apps and interactive tools │ ├── reports/ # Weekly progress reports, data schema documentation │ ├── tests/ # Unit tests for critical functions │ ├── environment.yml # Conda environment file for reproducibility └── README.md # Project overview and documentation </code></pre>


---

## 📦 Tech Stack

- `FastF1`, `pandas`, `scikit-learn`, `statsmodels`
- `matplotlib`, `seaborn`, `plotly`, `streamlit`
- Version control via `git`, with GitHub for collaboration and issue tracking

---

## 📅 Status

- ✅ Project initialized (Week 1)
- ⏳ Next: data schema design + simulator skeleton
