# 🚗 Used Cars24 Analytics (Big Data Analytics Project)

This project analyzes used cars dataset from **Cars24** using **PySpark**, **Pandas**, and **Matplotlib**.  
The goal is to explore car resale trends, fuel/transmission preferences, price variations, and extract insights for buyers and sellers.

---

## 📊 Project Overview
- **Dataset**: Cars24 Used Cars Data  
- **File Used**: Cars24.csv  
- **Records**: ~X rows (replace with count from dataset)  
- **Columns**: Year, Car Model, Car Variant, KM Driven, Fuel Type, Transmission, Owner, Location, Price, etc.  
- **Objective**: Perform data analytics on used car sales, visualize insights, and apply big data operations with PySpark.  

---

## ⚙️ Technologies & Tools
- **Python** (Core language)  
- **PySpark** (Big data processing & feature extraction)  
- **Pandas** (Data manipulation & validation)  
- **Matplotlib** (Visualization of trends)  
- **Jupyter Notebook** (Interactive analysis & reporting)  

---

## 🧹 Data Cleaning & Preprocessing
- Loaded dataset using PySpark DataFrame API.  
- Converted schema to correct datatypes (e.g., Price as numeric, Year as int).  
- Handled null values where present.  
- Standardized categorical values like Fuel Type and Transmission.  

---

## 📈 Key Analyses & Visualizations
1. **Total Cars in Dataset**  
   - Counted total number of records.  

2. **Fuel Type Distribution**  
   - Number of cars by fuel type.  
   - Visualized using **bar charts**.  

3. **Transmission Analysis**  
   - Cars by transmission type.  
   - Visualized with a **pie chart**.  

4. **Ownership vs Fuel Type**  
   - Grouped cars by ownership and fuel type.  
   - Visualized using a **stacked bar chart**.  

5. **Price Analysis**  
   - Minimum & maximum prices for each fuel type.  
   - Sorted prices ascending.  

6. **Location-Based Filtering**  
   - Cars in **Agartala** with price greater than the city’s average.  

7. **Car Age & Price Adjustment**  
   - Increased price by ₹0.50L for cars older than 2015.  
   - Created a new DataFrame and saved results to file.  

---

## 📑 Reports & Presentations
- 📄 [Cars24 Analytics Report](https://github.com/sanyupaulreddy/Big_Data_Analytics_Mini_Project/blob/13f02675d7f8d3de9685f9d88999cf0fafcdede9/7.%20Used_Cars_Project/Cars24_UsedCars_Report.pdf)  
- 📊 [Cars24 Analytics Presentation PPTX](https://github.com/sanyupaulreddy/Big_Data_Analytics_Mini_Project/blob/13f02675d7f8d3de9685f9d88999cf0fafcdede9/7.%20Used_Cars_Project/Cars24_Project_Presentation.pptx) 
- 📓 Jupyter Notebook (`BDA_Mini_Project_UsedCars.ipynb`)  

---

## 🚀 How to Run
Clone the repository:
```bash
git clone https://github.com/<sanyupaulreddy>/Big_Data_Analytics_Mini_Project.git
cd Big_Data_Analytics_Mini_Project
```

Install dependencies:
```bash
pip install -r requirements.txt
```

Place dataset in working directory:
```
Cars24.csv
```

Run Jupyter Notebook:
```bash
jupyter notebook
```

---

## 📬 Author
**Sanyu Paul Reddy Singareddy**  
📧 sanyu.p.singareddy@gmail.com  
🔗 [LinkedIn](linkedin.com/in/sanyu-paul-reddy-singareddy-4a5aab2b7)  

---

## ✅ Conclusion
This project demonstrates how **PySpark** and **Pandas** can be applied for **scalable analytics on used car datasets**.  
Insights can help buyers and sellers understand market trends, resale value, and demand by fuel type, ownership, and transmission.
