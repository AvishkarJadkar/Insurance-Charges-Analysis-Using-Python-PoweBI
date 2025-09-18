# 📊 Insurance-Charges-Analysis-Using-Python-PoweBI
 

This insurance charges analysis project focuses on identifying the average insurance charge for particular feature using Python, Excel, and Power BI.

🛠️ **Tools Used:** Python (Pandas, Sklearn), Excel, Power BI  
📁 **Dataset:** insurance dataset consisting around 1338 values ( all filtered further)

---

## 🧠 Project Goal

To identify **the average insurance charge per feature** using data-driven techniques and present insights through a dynamic, professional Power BI dashboard.

---

## 🐍 Python-Based Fund Analysis

I started by importing and exploring a dataset of over 1338 rows of information about insurance charges.  
🔗 [insurance dataset](insurance.csv)

### 1. Data Cleaning
- Removed unnecessary columns
- Handled missing values
- Standardized numeric formats

### 2. Data Description & Understanding
- Statistical summaries using Pandas: mean, median, mode, min, max, std deviation
- Analyzed insurance charges distribution between age,sex,bmi,smoker,children,region 

### 3. Data Normalization
- Used `MinMaxScaler` from `sklearn.preprocessing` to normalize numeric fields
- Compared returns and expense ratios on a common scale

### 4. Ranking features based on charges
Custom scoring formula based on:
- Tow much high the r2 score is  
- The mean absolute error 
- The mean squared error  
  

### 5. Final Output – Organised and cleaned insurance dataset
Extracted the **Cleaned insurance dataset** 
🔗 [Final insurance dataset (Excel)](https://github.com/AvishkarJadkar/Insurance-Charges-Analysis-Using-Python-PoweBI/blob/main/insurance1.xlsx)

---

## 📈 Power BI Dashboard – Insurace charges insight

After processing the data using Python and Excel, I built a **line graph** in Power BI.  
🔗 [Power BI Dashboard File (.pbix)](https://github.com/AvishkarJadkar/Insurance-Charges-Analysis-Using-Python-PoweBI/blob/main/insurance%20visualization.pbit)  
🔗 [Dashboard Preview Image](https://github.com/AvishkarJadkar/Insurance-Charges-Analysis-Using-Python-PoweBI/blob/main/insurance%20visualization.png)

### 📌 Key Features

#### 📅 Dynamic Filters
- Filter by AGE, SEX, CHILDREN, SMOKER AND REGION 

#### 📊 Key Visual
 
- 📈 **Average insurance charge vs feature (Line graph):** Easy to visualize how data is distributed  

---


## 🖼️ Dashboard Preview

![Insurance charges distribution Preview](https://github.com/AvishkarJadkar/Insurance-Charges-Analysis-Using-Python-PoweBI/blob/main/insurance%20visualization.png)

---

### 🧠 Final Conclusion – See the distribution of Insurance Charges

Through this project and dashboard, you can clearly see the **Distribution of insurance charges** when guided by data-driven insights.


## 🔧 Tool Summary

| Tool   | Purpose |
|--------|---------|
| Python | Data cleaning, scoring, filtering top 30 funds |
| Excel  | Formatting, validation, supporting data |
| Power BI | Interactive dashboard and visual storytelling |

---

## 📁 Files in This Repository

| File | Description |
|------|-------------|
| [insurance1.xlsx](https://github.com/AvishkarJadkar/Insurance-Charges-Analysis-Using-Python-PoweBI/blob/main/insurance1.xlsx) | Filtered insurance charges |
| [insurance visualization.pbit](https://github.com/AvishkarJadkar/Insurance-Charges-Analysis-Using-Python-PoweBI/blob/main/insurance%20visualization.pbit) | Power BI dashboard |
| [insurance visualization.png](https://github.com/AvishkarJadkar/Insurance-Charges-Analysis-Using-Python-PoweBI/blob/main/insurance%20visualization.png) | Dashboard image preview |

---

✅ **Feel free to fork, explore, and contribute!**

### 🙌 Feedback Welcome

Thank you for exploring my Mutual Fund Analysis project!  
I’m always open to suggestions, improvements, or collaboration ideas.

📩 Feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/avishkar-jadkar-452b0328b/)  
📧 Or drop an email: **avishkarjadkar1709@gmail.com**

Your feedback helps me grow and build better data-driven solutions. Let’s connect and discuss ideas!

