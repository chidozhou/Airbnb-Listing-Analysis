# Airbnb Listing Analysis

## 📊 Project Overview
This project analyzes Airbnb listings data with a focus on Paris. Using Python for data analysis, the objective was to profile, clean, aggregate, and visualize the data to uncover insights into price trends, accommodations, and host behavior over time, especially in light of the 2015 regulations.

## 🔍 Objectives & Tasks

### **Objective 1: Profile & QA the Data**
- ✅ Imported the `Listings.csv` file.
- ✅ Cast date columns to datetime format.
- ✅ Filtered data to include only Paris listings.
- ✅ Retained relevant columns: `host_since`, `neighbourhood`, `city`, `accommodates`, and `price`.
- ✅ Performed data quality checks:
  - Identified missing values.
  - Calculated minimum, maximum, and average for numeric fields.

### **Objective 2: Prepare the Data for Visualization**
- ✅ Created `paris_listings_neighbourhood`: Grouped listings by neighborhood and calculated the mean price (sorted low to high).
- ✅ Created `paris_listings_accommodations`: Focused on the most expensive neighborhood, grouped by `accommodates`, and calculated the mean price.
- ✅ Created `paris_listings_over_time`: Grouped data by `host_since` year, calculating the average price and number of new hosts per year.

### **Objective 3: Visualize the Data and Summarize Findings**
- ✅ Horizontal bar chart: Average price by neighborhood in Paris.
- ✅ Horizontal bar chart: Average price by accommodations in the most expensive neighborhood.
- ✅ Line charts:
  - Number of new hosts over time.
  - Average price over time.
- ✅ BONUS: Dual-axis line chart showing both new hosts and average price over time.

## 📈 Key Insights
- The 2015 regulations significantly impacted the number of new hosts entering the market.
- Prices showed a steady trend with noticeable fluctuations following regulatory changes.
- Certain neighborhoods consistently maintained higher average prices.

## 🛠️ Technologies Used
- **Python**
- **Pandas** – Data manipulation and analysis
- **Matplotlib & Seaborn** – Data visualization
- **Jupyter Notebook** – Interactive coding and documentation

## 🚀 How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/airbnb-listing-analysis.git
   ```
2. Navigate to the project directory:
   ```bash
   cd airbnb-listing-analysis
   ```
3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
5. Open the notebook file and follow the cells for analysis and visualization.


---
Feel free to fork and contribute to this project! 🚀

