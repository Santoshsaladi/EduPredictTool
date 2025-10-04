# 🎓 EDU Predict Tool

**Forecasting International Student Enrollment Trends using SARIMAX, Power BI, and Python**

EduPredictTool is a data-driven forecasting solution developed to help universities, policymakers, and research institutions predict international student enrollment patterns. By combining machine learning models with interactive visual dashboards, the project enables **scenario-based planning**, **geo-visualization**, and **funding-source insights** to support strategic academic decisions.

---

## 🚀 Key Highlights

- **Forecast Modeling:** Implemented SARIMAX models to predict enrollment trends under *baseline, optimistic, and pessimistic* scenarios.  
- **Interactive Dashboards:** Designed a Power BI dashboard to visualize trends across geography, funding types, and academic years.  
- **Automated Workflows:** Built Python pipelines for data cleaning, transformation, and visualization using Pandas and Plotly.  
- **Institutional Insights:** Empowered decision-makers to simulate future enrollment shifts and plan budgets more effectively.  

---

## 🧠 Project Motivation

International student enrollment is a key indicator for universities’ financial and academic planning.  
The EDU Predict Tool aims to answer:
- How will future enrollment fluctuate under varying scenarios?  
- Which regions and funding sources are most influential?  
- How can universities use data to make proactive policy decisions?  

---

## 🏗️ Architecture Overview

📦 EduPredictTool/
│
├── 📂 Datasets/ → Cleaned and processed datasets
├── 📂 OriginalDataset/ → Raw datasets before preprocessing
├── 📂 Images/ → Charts and figures used in documentation
├── 📜 EduPredict_EDA.ipynb → Exploratory Data Analysis notebook
├── 📜 ARIMA_FORECAST_*.ipynb → Forecasting notebooks using SARIMAX
├── 📜 TEAM_2_PROJECT_7_DASHBOARD.pbix → Power BI dashboard file
├── 📜 Project Presentation.pptx → Final presentation slides
└── 📜 README.md → Documentation

yaml

---

## 🛠️ Tech Stack

| Layer | Tools & Frameworks |
|-------|--------------------|
| **Data Processing** | Python, Pandas, NumPy |
| **Modeling & Forecasting** | statsmodels (SARIMAX, ARIMA) |
| **Visualization** | Plotly, Power BI, Matplotlib |
| **Dashboard Design** | Power BI, DAX |
| **Documentation & Deployment** | GitHub Pages, Tailwind CSS |

---

## ⚙️ Installation & Usage

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Santoshsaladi/EduPredictTool.git
   cd EduPredictTool
Create and Activate a Virtual Environment

bash
python3 -m venv venv
source venv/bin/activate      # macOS / Linux
venv\Scripts\activate         # Windows
Install Dependencies

bash

pip install -r requirements.txt
Run the Notebooks

Open EduPredict_EDA.ipynb for data exploration.

Run ARIMA_FORECAST_*.ipynb notebooks for forecasting.

Export forecast outputs to Datasets/ for dashboard integration.

Visualize in Power BI

Open TEAM_2_PROJECT_7_DASHBOARD.pbix in Power BI.

Use filters for year, region, and funding to interact with insights.

📊 Results & Insights
Achieved consistent forecasting accuracy with SARIMAX for year-over-year enrollment trends.

Visualized country-level and funding-based trends, enabling data-driven academic planning.

Enabled interactive scenario simulation for stakeholders to test “what-if” conditions.

<p align="center"> <img src="Images/dashboard_demo.png" alt="EDU Predict Tool Dashboard" width="700"/> </p>
🎯 Impact
The EDU Predict Tool provides universities and researchers with actionable analytics to:

Understand enrollment dependencies on geography and funding.

Anticipate shifts in international student numbers post-policy or global changes.

Align recruitment and scholarship strategies with predictive insights.

👥 Contributors
Team Lead: Santosh Kumar Saladi
Team Members: University of New Haven Capstone Team (6 members)
Duration: February 2025 – April 2025

📜 License
This project is licensed under the MIT License.

🌐 Live Assets
GitHub Repository: EduPredictTool

Presentation: Available in repo as Project Presentation.pptx

Dashboard File: TEAM_2_PROJECT_7_DASHBOARD.pbix

💡 “Turning educational data into actionable insights for smarter academic planning.”
yaml

---
