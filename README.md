## 📬 Author

**Name:** MUGABO EMMANUEL
**ID:** 26735
**Lecturer:** Eric Maniraguha  
**Institution:** AUCA – Faculty of Information Technology  
**Academic Year:** 2025

---

# 🛍️ Retail Sales Analytics & Customer Segmentation

This capstone project explores large-scale retail transaction data to identify patterns in store performance, customer purchases, and product popularity. Using Python for data processing and KMeans clustering, and Power BI for interactive visualization, this project reveals actionable business insights from structured sales data.

---

## 📊 Project Objective

> **Can we uncover meaningful patterns in customer purchases, product performance, and store activity using transaction data to support better business decisions?**

---

## 🔍 Tools & Technologies

- **Python:** jupyter notebook
- **Power BI:** For dashboard creation and visualization
- **Machine Learning:** KMeans clustering
- **PCA:** Dimensionality reduction for cluster visualization

---

## ⚙️ Methodology

1. **Data Cleaning & Preprocessing**
   - Converted dates, checked for nulls, validated totals
   - Extracted hour and day for trend analysis

2. **Exploratory Data Analysis (EDA)**
   - Identified top products, best-performing stores, and popular payment methods
   - Analyzed sales volume over time

3. **Clustering**
   - Applied KMeans on `Quantity`, `UnitPrice`, and `Total`
   - Used Elbow Method to determine optimal clusters
   - Evaluated clusters using Silhouette Score and visualized using PCA

4. **Dashboard Creation**
   - Developed a Power BI dashboard with interactive visuals:
     - Column chart (sales by store)
     - Pie chart (payment method share)
     - Bar chart (top-selling products)
     - Scatter plot (clustered behavior)
     - KPI cards & slicers

---

## 📌 Key Insights

- Some products (like Wraps and Fries) dominate revenue
- Certain branches consistently outperform others
- Cluster analysis reveals spending behavior groups (e.g., bulk vs. small-basket customers)
- Peak purchasing hours align with midday and evenings

---

## POWER BI DASHBOARD SCREENSHOOT

<img width="511" height="294" alt="Capture" src="https://github.com/user-attachments/assets/eea8e0f7-e0f7-4f5e-9fbf-38bf07d72316" />

## PYTHON(JUPYTER NOTEBOOK SCREENSHOTS)
1. DESCRIPTIVE STATISTICS WITH TOTAL SALES PER STORE DIAGRAM
   
<img width="893" height="449" alt="image" src="https://github.com/user-attachments/assets/9c299e5c-6f14-469b-a3c4-285b9905a74f" />

2.TOP 10 PRODUCTS BY SALE

<img width="653" height="377" alt="image" src="https://github.com/user-attachments/assets/3ec936b9-4a6a-4647-824b-9f8b238e6c19" />

3.PAYMENT METHOD DIAGRAM

<img width="1050" height="605" alt="image" src="https://github.com/user-attachments/assets/4c4545b3-f19c-4d4b-b130-df7df9b6ea98" />

4.SALE TRENDS BY AN HOUR

<img width="1400" height="589" alt="image" src="https://github.com/user-attachments/assets/932447e0-1521-41c8-a755-d05bb5e00148" />

5.K-MEANS AND SILHOUTTES SCORE

<img width="907" height="478" alt="image" src="https://github.com/user-attachments/assets/2f062789-fa2e-40b5-a695-cc9857d647d0" />

## 📈 Conclusion

This project demonstrated the power of data analytics in retail environments. By combining Python-based preprocessing with unsupervised learning and Power BI dashboards, we translated raw transactions into meaningful, actionable insights. The approach can support more strategic planning in marketing, inventory, and customer engagement.

---

## 🔮 Recommendations & Future Work

- Incorporate more diverse data (seasons, demographics)
- Use advanced clustering (e.g., DBSCAN, hierarchical)
- Implement predictive models to forecast product demand
- Create real-time dashboards with streaming data
- Integrate with customer loyalty data for deeper segmentation

---

## 📂 Files Included

- `retail_analysis.ipynb` – Python notebook with code and analysis
- `large_retail_sales_dataset.csv` – Cleaned retail dataset
- `Retail_Sales_Dashboard.pbix` – Power BI dashboard
- `Retail_Sales_Presentation.pptx` – Final capstone presentation

---



> *All work was conducted in accordance with AUCA’s academic integrity guidelines. Tools such as ChatGPT were used responsibly and with full understanding.*
