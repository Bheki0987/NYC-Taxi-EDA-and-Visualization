# NYC-Taxi-EDA-and-Visualization

## 📌 Overview
This project analyzes NYC Taxi and Limousine Commission (TLC) trip data to uncover trends, correlations, and business insights. It includes:
- Exploratory Data Analysis (EDA) of trip distances, fares, and time patterns.
- Data Cleaning to handle missing values and outliers.
- Interactive Visualizations using Tableau and Python (Matplotlib/Seaborn).

Key Questions Answered:
- How does trip distance relate to fare amount?
- Are there peak hours/days for taxi demand?
- What anomalies exist in pricing or trip patterns?

## 🔍 Key Findings
1. Trip Distance vs. Fare Amount
Weak correlation: Long trips don’t always mean higher fares (potential flat-rate trips).
2. Outliers: Some trips show $0 fare despite distance traveled.

3. Time-Based Trends
Peak Hours: 4–6 PM (evening rush hour).
Weekend Demand: Higher late-night trips (Fri/Sat).

4. Geographic Hotspots
Most pickups in Manhattan (Midtown/JFK Airport).

## 🚀 How to Use This Project
1. Clone the Repo
```bash
git clone https://github.com/Bheki0987/NYC-Taxi-EDA-and-Visualization.git   
2. Install Dependencies
```
```bash
pip install -r requirements.txt
```
3. Run Jupyter Notebooks
```bash
jupyter notebook  
Start with 1_Data_Cleaning.ipynb → 2_EDA.ipynb → 3_Visualizations.ipynb.
```
4. Explore Tableau Worksheet
Open Tableau:[Tableau](https://public.tableau.com/views/TLCVisualization/TotalDistanceTotalAmountTLC2017?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

## 📊 Deliverables
- ✅ Cleaned Dataset: ready for analysis.
- ✅ Tableau Worksheet: Worksheet Visualization of trip trends.
- ✅ Python Visualizations: Code to reproduce charts.
- ✅ Executive Summary: PPT for non-technical stakeholders.

💡 Why This Matters
- For Drivers: Optimize shift times based on demand.
- For TLC: Identify pricing anomalies or fraud patterns.
- For Data Analysts: Template for EDA with real-world data.
