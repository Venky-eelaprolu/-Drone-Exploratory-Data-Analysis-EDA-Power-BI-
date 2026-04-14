# Drone Data Analysis using Web Scraping, EDA & Power BI

### Overview

This project focuses on collecting drone-related data by performing web scraping from `Flipkart`, followed by Exploratory Data Analysis (EDA) and building interactive dashboards using Power BI.

The aim is to extract real-world product data and generate meaningful insights such as pricing trends, ratings, and product performance.

### Objectives

- Scrape drone product data from Flipkart
- Clean and preprocess raw data
- Perform exploratory data analysis (EDA)
- Build interactive Power BI dashboards
- Extract business insights

### Workflow

**1. Web Scraping**
    - Extract product details from Flipkart
    - Fields collected:
        - Product Name
        - Price
        - Ratings
        - Reviews
        - Specifications
**2. Data Cleaning**
    - Remove null values
    - Handle inconsistent formats
    - Convert price & ratings to numeric
**3. EDA**
    - Price distribution
    - Rating analysis
    - Correlation between price & ratings
**4. Visualization**
    - Built dashboards using Power BI
    - Interactive filters & slicers
### Tools & Technologies
- **Python**
    - BeautifulSoup / Requests (Web Scraping)
    - Pandas, NumPy (Data Processing)
    - Power BI (Visualization)
    - CSV / Excel (Data Storage)
### Project Structure
├── Scraper/

│   └── flipkart_scraper.py

├── Dataset/

│   └── drone_data.csv

├── PowerBI/

│   └── Drone_EDA.pbix

├── Images/

│   └── dashboard.png

└── README.md

### Dashboard Features
  - Price Analysis
  - Rating Distribution
  - Product Comparison
  - Trend Visualization
  - Interactive Filters
### Sample Dashboard
<img width="1325" height="735" alt="image" src="https://github.com/user-attachments/assets/434a491d-78d4-4be0-81e4-f29f507a8441" />

### Key Insights
  - Mid-range drones have higher ratings
  - Premium drones don’t always guarantee better reviews
  - Certain brands dominate the market
  - Price vs Rating shows weak correlation
### How to Use
1. Download the .pbix file
2. Open in Power BI Desktop
3. Load dataset if required
4. Explore interactive dashboards
