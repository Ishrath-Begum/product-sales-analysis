# Product Sales Analysis

A Data Science project focused on exploring product sales, cleaning the dataset, and performing data visualization to uncover key business insights.

## Tools Used
* **Language**: Python
* **Libraries**: Pandas, NumPy, Matplotlib, Seaborn
* **Environment**: Google Colab / Jupyter Notebook

## Key Insights & Exploratory Data Analysis (EDA)

### 📈 Core Sales & Performance Drivers (Correlation Findings)
* **Weekly Growth Trends**: The number of products sold (`nb_sold`) increases steadily as the weeks progress, showing a strong positive correlation of **0.79**.
* **Volume vs. Value**: Product volume drives value—higher quantities sold map directly to increased total revenue (**0.55** correlation).
* **Traffic Impact**: Digital engagement metrics reveal that higher numbers of website visits (`nb_site_visits`) are linked to a lift in sales performance and revenue generation.
* **Customer Loyalty**: Statistical correlation checks show that client longevity (`years_as_customer`) does not exhibit a strong mathematical connection to any other transactional variables.

### 🗺️ Geographic Performance
* **Top Revenue Markets**: **Texas** leads the portfolio with the highest average revenue metrics, followed closely by robust sales baselines in **Florida** and **California**.
* **Stable Regional Benchmarks**: **New York** and **Illinois** demonstrate slightly lower revenue floors, but overall, all five states maintain very comparable revenue clusters with minimal variation.

## Visualizations
### Correlation Heatmap
<img width="634" height="554" alt="image" src="https://github.com/user-attachments/assets/47acd1fc-45ca-47a3-ad9e-b37b78f82a38" />


## How to Run This Project
1. Open the `Product_Sales_Project.ipynb` notebook directly in Google Colab or Jupyter Notebook.
2. Ensure you have the required libraries installed:
   ```bash
   pip install pandas numpy matplotlib seaborn
   ```
3. Run the cells sequentially to reproduce the exploratory data analysis and charts.

