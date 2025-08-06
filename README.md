# Analysis on Used Car Prices 

A comprehensive Exploratory Data Analysis (EDA) project to uncover the key factors affecting the prices of used cars in India. Data was scraped from **Cars24**, cleaned, analyzed, and visualized to generate actionable insights for both buyers and sellers.

---

## Objective

To analyze historical used car data to understand how different factors like brand, mileage, fuel type, ownership, and manufacturing year impact resale prices. The goal is to assist:

- **Buyers** in choosing budget-friendly and value-retaining cars  
- **Sellers** in pricing vehicles competitively without undervaluing them  

---

## Data Collection

- **Source**: [Cars24 Website](https://www.cars24.com)  
- **Tools Used**: `requests`, `BeautifulSoup`  
- **Total Records**: 874 raw entries → 640 cleaned entries  
- **Key Features Extracted**:
  - Brand & Model  
  - Year of Manufacture  
  - Kms Driven  
  - Fuel Type  
  - Ownership Type  
  - Selling Price  

---

##  Data Cleaning

- Removed special characters from string columns  
- Converted Kms Driven to numeric values  
- Filled missing values using mode and group-based imputation  
- Extracted car age and separated brand/model  
- Converted data types and reset index  

---

## Technologies Used

- **Python**  
- **Libraries**: `Pandas`, `NumPy`, `Matplotlib`, `Seaborn`, `Plotly`  
- **Web Scraping**: `BeautifulSoup`, `Requests`  
- **Jupyter Notebook** for development and visualization

---

## Key Insights

- **Maruti, Hyundai, Tata** dominate the used car market  
- **Diesel cars** offer better mileage and often cost more than petrol cars  
- **First-owner** cars have higher resale value  
- **Car age** and **kilometers driven** negatively impact price  
- Luxury brands like **Mercedes, Audi, BMW** retain higher value  

---

## Visualizations Included

- Bar charts: Brand distribution, price by brand  
- Pie charts: Ownership type share  
- Box plots: Price vs Fuel type  
- Heatmap: Feature correlations  
- Histograms: Price and mileage distribution  
- Line charts: Price vs Manufacturing year  

---

## How to Run

1. Clone the repo or download the notebook  
2. Ensure you have Python 3.x and Jupyter installed  
3. Install required libraries:  
   ```bash
   pip install pandas numpy matplotlib seaborn plotly beautifulsoup4
Open the notebook and run cells step by step

📎 Files Structure
 used_car_analysis.ipynb     → Main Jupyter notebook  
 used_cars.csv               → Cleaned dataset  
 raw_data_scraper.py         → Optional scraper script  
 images/                     → Graphs and visualizations  

 ---  
 
 # Author
Saideepu Balaraju
