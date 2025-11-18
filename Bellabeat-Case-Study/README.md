# 📊 Bellabeat Case Study — Google Data Analytics Capstone
## By: Roopkiran Kaur

### 🔍 Project Overview
This project analyzes smart device usage data to understand consumer behavior and provide actionable recommendations for **Bellabeat**, a wellness-focused smart device company. Using real-world Fitbit data, the goal is to uncover trends in activity, sleep, steps, and calorie burn to guide Bellabeat’s marketing strategy.

This project follows the **Google Data Analytics framework: Ask → Prepare → Process → Analyze → Share → Act**.

---

## 🛠️ Tools & Technologies
- **Python:** Pandas, NumPy, Matplotlib, Seaborn  
- **Excel:** Data cleaning & quick summaries  
- **Jupyter Notebook:** Analysis & visualizations  
- **GitHub:** Version control & documentation

---

# 🔄 1. Ask Phase
**Business Task:**  
Analyze smart device usage data to identify trends in how consumers use health-tracking devices and suggest opportunities for Bellabeat’s growth.

**Key Questions:**
- How do activity levels vary throughout the day/week?
- What is the relationship between steps, calories, and active minutes?
- How do sleep patterns affect overall wellness?
- What insights can help Bellabeat refine its marketing strategy?

---

# 📥 2. Prepare Phase
**Dataset Used:** Fitbit Fitness Tracker Data (CC0: Public Domain)

Contains:
- Daily steps
- Intensities
- Sleep data
- Calories
- Heart rate metrics
- Activity minutes

**Data Limitations:**
- Only 30 users  
- Self-reported data  
- Not fully representative of all demographics  

---

# 🧹 3. Process Phase
Performed using **Python**:

### ✔️ Data Cleaning
- Removed duplicates  
- Standardized date/time formats  
- Handled missing values  
- Merged datasets using user IDs & date  
- Converted data types  

### ✔️ Feature Engineering
- Added total activity levels  
- Created time-based metrics (weekday/weekend)  
- Classified users by activity type  

---

# 📊 4. Analyze Phase

### Key Insights Identified:
#### **1. More steps = more calories burned**
Strong positive correlation between **daily steps** and **calories**.

#### **2. Users are most active between 5 PM – 7 PM**
Evening hours show the highest step count.

#### **3. Weekdays have higher activity levels than weekends**

#### **4. Sleep duration averages ~6 hours**
Many users fall short of recommended 7–8 hours.

#### **5. Sedentary minutes dominate daily time**
Most users spend over **12 hours/day sedentary**.

---

# 📈 5. Share Phase — Visualizations

Visuals included in the `visualizations/` folder:
- Daily steps vs calories scatter plot  
- Activity intensity distribution  
- Sleep patterns chart  
- Hourly activity peaks  
- Weekday vs weekend activity comparison  

You can embed preview images here once uploaded.

---

# 💡 6. Act Phase — Recommendations for Bellabeat

### **1. Promote evening workout reminders**
Most users are active in the evening → schedule push notifications 5–7 PM.

### **2. Launch “7-Day Step Boost” challenge**
Gamify walking challenges; reward badges for consistency.

### **3. Target users with low sleep hours**
Promote Bellabeat’s **sleep coaching features**.

### **4. Promote stress-reduction guides**
High sedentary minutes suggest need for wellness content.

### **5. Introduce personalized health insights**
Daily activity + sleep dashboards can increase engagement.


---

# ✔️ Conclusion
This analysis provides data-driven insights into consumer wellness behavior, helping Bellabeat improve its marketing, product strategy, and user engagement. The project demonstrates skills in **data cleaning, EDA, visualization, insight reporting**, and **Python-based analysis**.

