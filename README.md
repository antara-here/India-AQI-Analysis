# India-AQI-Analysis(1987-2015)

## 📌 Project Overview
This project analyses 28 years of real air quality data across 
Indian states to find pollution trends, identify most polluted 
regions and predict AQI category using Machine Learning.

---

## 📊 Dataset
**Source:** India Air Quality Data-Kaggle
🔗https://www.kaggle.com/datasets/shrutibhargava94/india-air-quality-data

-Total Records: 435,000+
- States Covered: 16+ Indian states
- Time Period: 1987 to 2015
- Pollutants: SO2, NO2, RSPM, SPM
> After downloading, place `data.csv` inside the `/data` folder 
> before running the notebook

---

## 🛠️ Tools and Technologies
| Tool | Purpose |
|---|---|
| Python | Core programming |
| Pandas | Data cleaning and manipulation |
| NumPy | Numerical operations |
| Matplotlib & Seaborn | Data visualization |
| SQLite | SQL queries and analysis |
| Scikit-learn | Machine Learning model |
| Power BI | Interactive dashboard |
| Google Colab | Development environment |

---

## 📁 Project Structure
india-aqi-analysis/
├── aqi_analysis.ipynb       ← Complete Python notebook
├── powerbi_dashboard.png    ← Power BI dashboard screenshot
└── README.md                ← Project documentation

---

## 🔄 Project Steps

### Step 1 — Data Cleaning
- Parsed date column and extracted year and month
- Filled missing pollutant values using state-wise median
- Standardised city and state names
- Created AQI composite score from pollutants
- Classified AQI into Good / Moderate / Poor / Hazardous

### Step 2 — SQL Analysis
- Most polluted states by average AQI
- Year-wise AQI trend across India
- Monthly seasonal pollution pattern
- State-wise pollutant breakdown

### Step 3 — EDA and Visualizations
- AQI distribution across India
- Year-wise AQI trend (1987–2015)
- Top 10 most polluted states
- Seasonal AQI pattern by month
- Pollutant correlation heatmap
- AQI category breakdown

### Step 4 — Machine Learning Model
- Target: Predict AQI category (Good/Moderate/Poor/Hazardous)
- Algorithm: Random Forest Classifier
- Train/Test Split: 80/20
- Result: **91% accuracy**

### Step 5 — Power BI Dashboard
- KPI cards: Average AQI, Total Records
- Line chart: AQI trend over years
- Bar chart: Most polluted states
- Donut chart: AQI category breakdown
- Seasonal pattern chart
- Interactive state slicer and year slicer

---

## 📈 Key Findings
- **Uttar Pradesh** is the most polluted state in India
- Pollution **steadily increased** from 1990 to 2010 then slightly declined
- **Winter months (October to January)** are significantly more polluted than summer
- **RSPM** is the strongest predictor of AQI category
- 70%+ of all records fall in the **Poor** AQI category

---

## 🤖 Model Performance
| Model | Accuracy |
|---|---|
| Random Forest Classifier | 91% |
| Logistic Regression | ~78% |

---

## 👩‍💻 About Me
**Antara Bangal**
BCA Graduate — Institute of Engineering and Management, Kolkata

🔗 [LinkedIn](https://linkedin.com/in/antara-bangal-iem23)
🐙 [GitHub](https://github.com/antara-here)
📧 bangalantara@gmail.com
