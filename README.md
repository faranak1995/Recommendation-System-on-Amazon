# Amazon Product Recommendation System

This project is a Python-based web scraping and recommendation system that extracts product data (e.g., title, price, and rating) from Amazon and recommends products based on specified criteria. The recommendation system filters and visualizes data to help users make informed decisions.

---

## Features

- Scrapes product information from Amazon using Selenium.
- Extracts data including product title, price, and rating.
- Recommends products based on specific criteria:
  - **Price**: Less than $30.
  - **Rating**: 4.5 or higher.
- Visualizes recommendations using bar charts.
- Outputs structured data in tabular form for further analysis.

---

## Installation

### Prerequisites

- Python 3.7+
- WebDriver for Selenium (e.g., ChromeDriver for Chrome)
- Required Python libraries:
  - `selenium`
  - `pandas`
  - `matplotlib`
  - `beautifulsoup4`

### Steps

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/amazon-recommendation-system.git
   cd amazon-recommendation-system

2. Install dependencies:
```pip install -r requirements.txt```

3. Download and set up the WebDriver (e.g., ChromeDriver):

Ensure the driver version matches your browser version.
Add the driver to your system PATH.
