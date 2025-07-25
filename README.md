# Crime-Analysis-Demo
# 🕵️‍♂️ Nagpur Crime Data Analysis

A Python-based project for 📊 **data cleaning**, 🔍 **exploration**, and 📈 **visualization** of crime records in Nagpur.

---

## 📂 Dataset

- 📥 Input: `Nagpur_Crimes.csv`
- 📤 Output: `Nagpur_Crimes_CLEANED.csv`

---

## 🧰 Requirements

```bash
pip install pandas matplotlib seaborn
```

---

## 🧹 Data Cleaning

✅ Remove rows with missing `Crime_Type`, `Time`, or `Date`  
🕒 Convert `Time` to datetime, extract `Hour`  
📅 Convert `Date` to datetime, extract `Month`  
♻️ Drop duplicate rows  
💾 Save cleaned data as `Nagpur_Crimes_CLEANED.csv`

---

## 📊 Data Analysis

- ⏰ Crime count by hour  
- 🔝 Top 3 most frequent crime types  
- 📍 Top 10 areas with highest crime  
- 🗺️ Most common crime per zone  
- 📌 Case status counts (e.g., Solved, Pending)  
- 📆 Monthly crime trend analysis

---

## 📉 Visualizations

- 🪧 Bar chart: Top 10 crime-prone areas  
- 📈 Line chart: Monthly crime trends over time

---

## 📁 Output

- Cleaned dataset: `Nagpur_Crimes_CLEANED.csv`  
- Summary stats via `print()`  
- Visuals via `matplotlib` & `seaborn`

---

## 📝 Notes

- 🧪 Originally developed in Google Colab  
- 🕒 Time format expected: `%H:%M`  
- 🔄 Final cleaned DataFrame: `df`
