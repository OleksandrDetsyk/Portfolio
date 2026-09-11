# Data Engineer's Portfolio, Oleksandr Detsyk
## About me
Greetings! 
Greetings! I am Oleksandr, an analytics engineer with a background in fintech, data analysis, and financial modeling. I believe in building an interconnected lattice of knowledge, which is why this portfolio features projects spanning Data Engineering, Data Analysis, and Quantitative Analysis.

## 🛠️ Technical skills
- PostgreSQL
- Python
- Substreams
- Grafana
- Git
- Docker
- Various AI tools (Claude, Copilot)
- Excel

## Portfolio projects
It showcases my proficiency in data cleaning, predictive modeling, and financial forecasting, demonstrating my ability to transform raw data into usable insights. Each project reflects my skills in tracking KPIs, creating impactful visualizations, and developing simulations that improve business efficiency.

### 📕 Book Recommender

  **Description:** The Book Recommender is a Python-based application that generated a list of recommended books by analyzing statistical correlations between user preferences and an extensive database of book ratings. By processing parameters like title and author's name, the system identifies and retrieves title with the highest similarity coefficients to the user's input. The system handles errors for invalid inputs, incomplete book titles and typos.
   
  **Goal:** To create a robust, highly-tunable, user-friendly command-line tool that delivers personalized book recommendations based on a user's favorite book. 
   
  **Challenge:** The primary obstacle was data inconsistency within the large dataset. Multiple variations of the same book title (e.g., "The Lord of the Rings Part I" vs. "The Lord of the Rings: The Fellowship of the Ring") threatened the accuracy of the correlation matrix.

   - [`Python Code`](https://github.com/SashaD826/Portfolio/blob/main/book_recommender2.ipynb)
   
  **Results:** I implemented a string matching algorithm (fuzzy wuzzy library) to resolve title differences and handle user input errors effectively. The final application successfully normalizes the dataset and delivers a list of recommended books, ensuring a seamless user experience even with ambiguous inputs.
   
  **Data Source:** [Link to Kaggle](https://www.kaggle.com/datasets/arashnic/book-recommendation-dataset?select=Ratings.csv)
  
### 🚲 Bike Sales Breakdown

  **Description:** This project involves a granular analysis of a bike store's order data over a one-month period. The dataset encompasses critical financial and operational metrics, including revenue, cost of goods sold, gross margin, customer demographics, providing a detailed description of store operations.
  
  **Goal:** To conduct an Exploratory Data Analysis (EDA) that describes store performance over time. The objective is to visualize crucial KPIs and identify opportunities to increase efficiency and revenue.
  
  **Challenge:** The raw data presented certain data quality issues, including duplicates, missing values, inconsistent product descriptions, missing and incorrect numeric values.
  
  - [`SQL Code`](https://github.com/SashaD826/Portfolio/blob/main/bike_sales_mysql.sql)
  
  - [`Python Code`](https://github.com/SashaD826/Portfolio/blob/main/bike_sales.ipynb)
  
  - [`Excel Spreadsheet`](https://github.com/SashaD826/Portfolio/blob/main/bike_sales_data.xlsx)
  
  - [`Power BI Dashboard`](https://github.com/SashaD826/Portfolio/blob/main/bike_sales_bi.pbix)

  **Results:** The final report shows crucial business intelligence insights, including revenue trends, a distribution analysis of order sizes (basket size), and revenue segmentation by weekday, region, and product category.

  **Data Source:** [Link to Kaggle](https://www.kaggle.com/datasets/ratnarohith/uncleaned-bike-sales-data/data)

  ### 💻🔮💰 Monte Carlo Simulation for a Stock Portfolio
  
  **Description:** This Python script executes a Monte Carlo simulation, a stochastic model that accounts for the historical performance of selected assets, but also introduces volatility to simulate market unpredictability. 30000 unique simulation paths are generated.
  
  **Goal:** To forecast the potential value of the portfolio over a 10-year period. To calculate the probability of incurring loss vs. the probability of assets doubling or tripling in value.
  
  **Challenge:** Prices of non-US assets have to be converted to USD. The model performs daily rebalancing to maintain constant asset weights over the ten-year period. While this simplifies the model, it provides a more consistent baseline for modeling than allowing asset allocation to drift.

  - [`Python Code`](https://github.com/SashaD826/Portfolio/blob/main/monte_carlo_sim.ipynb)

  **Result:** The mean (average) and median portfolio values are visualized using a line chart and a histogram, with the histogram illustrating the distribution of outcomes.
  
  **Future Improvements:** Planned updates include calculating the Sharpe ratio and adding an algorithm to determine optimal asset allocation.
      
# Contacts
LinkedIn: https://www.linkedin.com/in/oleksandr-detsyk

