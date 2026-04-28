# Remote Operations Pressure Analysis

## 📊 Project Overview
This project analyzes well performance by comparing **actual vs planned pressure** across multiple wells. The goal is to identify anomalies, detect instability, and highlight wells that may require operational attention.

---

## 🎯 Objectives
- Evaluate pressure deviations across wells
- Identify high-risk or unstable wells
- Compare actual performance against planned targets
- Provide data-driven insights for operational decision-making

---

## 🧰 Tools & Technologies
- Python (Pandas, NumPy)
- Jupyter Notebook
- Data Cleaning & Aggregation
- Statistical Analysis

---

## 📁 Dataset
The dataset includes:
- `well_info.csv` – well metadata
- `treatment_data.csv` – pressure readings
- `job_plan.csv` – planned pressure targets
- `equipment_data.csv`, `materials.csv` – supporting operational data

---

## 🔍 Key Analysis Steps
1. Data loading and validation
2. Cleaning zero-pressure (non-operational) intervals
3. Calculating pressure error:
   - Mean
   - Min / Max
   - Standard deviation
4. Aggregating results by well

---

## 📈 Key Findings
- **W-102** shows the highest average pressure deviation (+32.56 psi) → potential over-pressure risk
- **W-105** and **W-103** are the most stable wells
- Initial results were skewed by zero-pressure downtime, which was corrected during cleaning

---

## 🧠 Conclusion
W-102 requires closer monitoring due to high variability.  
W-105 can serve as a performance benchmark for stable operations.

---

## 🚀 Future Improvements
- Add visualization dashboard (Plotly / Power BI)
- Implement anomaly detection models
- Automate monitoring pipeline

---

## 👤 Author
**Chester Dees**  
Aspiring Data Scientist | Logistics & Operations Analytics
