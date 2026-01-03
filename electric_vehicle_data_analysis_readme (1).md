# ⚡ Electric Vehicle Data Analysis Project

**End-to-end electric vehicle data analysis using Python, covering budget-based filtering, efficiency outlier detection, battery–range analysis, statistical hypothesis testing, and a user-centric EV recommendation system.**

## 📌 Project Overview
The rapid growth of electric vehicles (EVs) has created a need for **data-driven insights** to help customers, manufacturers, and decision-makers balance **price, range, performance, and efficiency**.  

This project performs an **end-to-end analysis of electric vehicle data** to uncover meaningful insights, detect anomalies, validate assumptions using statistics, and build a **practical EV recommendation system**.

The analysis is implemented entirely in **Python**, following clean, structured, and explainable data science practices.

---

## 🎯 Objectives
- Analyze EV specifications such as **price, battery capacity, range, power, and energy consumption**
- Identify **efficient and inefficient EVs** using statistical outlier detection
- Understand the **relationship between battery capacity and driving range**
- Build a **user-driven EV recommendation system**
- Perform **hypothesis testing** to compare manufacturer performance
- Deliver **actionable, business-relevant insights**

---

## 🗂 Dataset Information
**File:** `FEV-data-Excel.xlsx`

The dataset contains detailed technical and performance attributes of electric vehicles, including:
- Vehicle identification (Make, Model)
- Pricing (Minimal price in PLN)
- Performance metrics (Engine power, torque, acceleration, top speed)
- Battery & efficiency metrics (Battery capacity, WLTP range, energy consumption)
- Physical characteristics (Dimensions, weight, seating, boot capacity)
- Charging capability (Maximum DC charging power)

---

## 🛠 Tools & Technologies
- **Programming Language:** Python
- **Libraries Used:**
  - Pandas – data manipulation & analysis
  - NumPy – numerical operations
  - Matplotlib – data visualization
  - SciPy – statistical testing
- **Environment:** Jupyter Notebook

---

## 📊 Project Tasks & Methodology

### ✅ Task 1: Budget-Based EV Filtering & Manufacturer Analysis
**Problem:** Identify EVs affordable to a customer with a budget of **350,000 PLN** and a minimum range of **400 km**.

**Approach:**
- Filtered EVs meeting price and range criteria
- Grouped qualifying vehicles by manufacturer
- Calculated **average battery capacity per manufacturer**

**Insight:**
Only a limited number of manufacturers meet both affordability and long-range requirements, and battery strategies vary significantly across brands.

---

### ✅ Task 2: Energy Consumption Outlier Detection
**Problem:** Some EVs may consume unusually high or low energy.

**Approach:**
- Applied statistical outlier detection techniques (IQR / Z-score)
- Identified extreme values in **mean energy consumption (kWh/100 km)**

**Insight:**
Outliers highlight EVs with exceptional efficiency or inefficiency, often influenced by vehicle weight, performance focus, or drivetrain design.

---

### ✅ Task 3: Battery Capacity vs Driving Range Analysis
**Problem:** Determine whether battery capacity strongly impacts driving range.

**Approach:**
- Visualized the relationship using a **scatter plot**
- Analyzed correlation trends

**Insight:**
While battery capacity and range show a positive correlation, the relationship is not perfectly linear—**efficiency and design play a crucial role**.

---

### ✅ Task 4: EV Recommendation System (OOP)
**Problem:** Help users select suitable EVs based on personal preferences.

**Approach:**
- Built a **Python class-based recommendation system**
- User inputs:
  - Budget
  - Desired range
  - Battery capacity
- Output:
  - **Top 3 matching EVs**

**Value:**
Transforms analysis into a **practical decision-support tool**, simulating a real-world EV advisor.

---

### ✅ Task 5: Hypothesis Testing – Tesla vs Audi
**Problem:** Are Tesla and Audi significantly different in terms of engine power?

**Approach:**
- Conducted a **two-sample t-test** using `scipy.stats.ttest_ind`
- Compared average engine power of Tesla and Audi EVs

**Insight:**
Statistical testing validated whether observed differences are **significant or due to random variation**, strengthening analytical credibility.

---

## 📈 Key Insights & Findings
- Battery size alone does not guarantee higher range—**energy efficiency is equally critical**
- Some EVs achieve long range through better engineering rather than larger batteries
- Statistical analysis provides stronger evidence than descriptive comparisons
- Recommendation systems significantly enhance the practical value of analytics

---

## 🧠 Conclusion
This project demonstrates a **complete data science workflow**, combining:
- Data wrangling
- Exploratory analysis
- Statistical reasoning
- Visualization
- Object-oriented programming

By converting raw EV data into **clear insights and actionable recommendations**, the project reflects real-world problem-solving expected from industry-level data scientists.

---

## 📌 Future Enhancements
- Add machine learning models for range or price prediction
- Incorporate clustering for EV segmentation
- Deploy the recommendation system as a web application
- Extend analysis with real-world charging cost data

---

## 👤 Author
**Harsh Pandey**  
Aspiring Data Scientist | Python | Statistics | Analytics

---

⭐ *If you find this project useful, feel free to star the repository!*

