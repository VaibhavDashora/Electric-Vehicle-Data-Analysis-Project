# Electric-Vehicle-Data-Analysis-Project
This project analyzes a dataset of electric vehicles (EVs), exploring features like range, energy consumption, and price. Through data cleaning, visualization, and hypothesis testing, we uncover insights, craft a compelling narrative, and deliver actionable recommendations.

# 🔋 Electric Vehicle Data Analysis Project
This project explores a curated dataset of electric vehicles (EVs), analyzing key attributes such as electric range, energy consumption, price, battery capacity, and performance metrics. The goal is to uncover meaningful insights, validate hypotheses, and deliver actionable recommendations for stakeholders across the EV ecosystem.

# 📌 Objectives
Analyze EV specifications to identify performance and value trends.

Conduct hypothesis testing to validate assumptions about range, battery capacity, and brand performance.

Build a recommendation engine for EV selection based on user preferences.

Translate technical findings into business-ready insights and visualizations.

# 📊 Dataset Overview
The dataset includes 53 EV models with 25 features, such as:

Performance: Battery capacity, range (WLTP), engine power, acceleration

Design: Dimensions, boot capacity, tire size

Efficiency: Energy consumption (kWh/100 km)

Pricing: Minimal price (gross) in PLN

Branding: Make, model, drive type, brake type

Missing values were imputed using median/mode strategies to ensure clean analysis.

# 🔍 Key Analyses
1. Budget-Conscious EV Selection
Filtered EVs under 350,000 PLN with ≥400 km range. Audi leads in battery capacity, followed by BMW and Mercedes-Benz—highlighting premium engineering.

2. Energy Consumption Outliers
Identified high-consumption models (e.g., Audi e-tron S, Mercedes EQV) using Z-score analysis. These reflect performance or utility-focused designs.

3. Battery vs Range Correlation
Strong positive correlation (r = 0.81, p < 0.0001) confirms that larger batteries generally yield longer ranges. Some models achieve high efficiency with smaller batteries.

4. EV Recommendation Engine
Custom class filters top 3 EVs based on user input (budget, range, battery capacity). Example output includes Volkswagen ID.3, Kia e-Niro, and Kia e-Soul.

5. Hypothesis Testing: Tesla vs Audi
T-test shows no statistically significant difference in engine power between Tesla and Audi EVs (p = 0.1068), challenging assumptions about brand dominance.

# 💡 Business Insights
Audi matches Tesla in engine power—marketers can leverage this parity.

Efficiency-focused models offer competitive range with smaller batteries.

