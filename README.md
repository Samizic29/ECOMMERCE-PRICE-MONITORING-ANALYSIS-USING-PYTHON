# ECOMMERCE-PRICE-MONITORING-ANALYSIS-USING-PYTHON
**By Samuel Oyedele**

## INTRODUCTION

> This project scraped data from the eBay website about the laptop prices of three of the most popular brands: Apple, Dell and HP.

## OBJECTIVE

> To monitor and analyze the prices of laptop products from three brands (Apple, Dell and HP) on eBay website.

**Tools Used:** Python, Pandas (data manipulation), BeautiSoup(Web scraping), Matplotlib / Seaborn (data visualization)

**Skill Highlighted:** Web scraping, data cleaning, data analysis, data visualization

## DATA WRANGLING

> In this section, the datasets are gathered (web scraping), assessed for quality and tidiness issues and cleaned for analysis and visualization.

### Gathering Data
> In this section, web scraping is performed using BeautifulSoup to scrape the data from the eBay website for data collection.

#### Web Scraping: 
> In this section, the data are collected through scraping of data from the website using Request and BeautifulSoup. The data scraping from the eBay website focused on three laptop brands: Apple, Dell and HP.

### Assessing Data
> In this section, the scraped data will be assessed for quality and tidiness issues.

#### Quality Issues
> They are issues with the data content like missing data, Inaccurate data, Inconsistent data etc. It is also known as dirty data.

- Price Column: The data type is in string instead of float and extracts the dollar($) from the price.
- Timestamp Column: Data Type issue

### Data Cleaning
> In the section, the dataset is cleaned for better analysis and visualizations. The data cleaning is done following the steps: Define, Code and Test.

## EXPLORATORY ANALYSIS
> In this section, I was able to analyze the scrape cleaned data to identify the trends and pattern of prices for each brand of laptop products.

### Key Metrics
- Price Distribution Analysis
- Average Price for Each Brand
- Top 5 Highest Priced Laptops product for each Brand

## DATA INSIGHTS
- Most laptop prices fall within the range of **$0 - $1000**.
- **"Apple"** Brand has the highest average price for a laptop indicating high cost compared to other brands.
- **Apple Macbook Pro 16 (512GB SSD, APPLE M3 PRO, 36GB RAM)** is currently sold at **$2249.99** (with free shipping) on **eBay** which makes it the highest among other Apple laptops.
- **Dell Latitude e5440 14" (512GB SSD, Intel Core i7 13th Gen, 16GB)** is currently sold at **$5600.00** (with +70.00 shipping) on **eBay** which makes it the highest among other Dell laptops.
- **HP 840 G6 Laptops 1.60GHz CORE i5 8365U 8GB 256GB SSD W11PRO Webcam** is currently sold at **$5100.00** on **eBay** which makes it the highest among other HP laptops.
-  For each brand of laptop, the price increases as the laptop version increases.

## CONCLUSIONS
> From the project, I was able to scrape the data based on three laptop brands(Apple, Dell and HP) on eBay by web scraping (BeautifulSoup), perform data wrangling(gather, assess and cleaning) and exploratory analysis to identify trends and patterns in prices across different laptop brands.

> Further analysis can be done on this project; price trends over time, comparing the prices across different specifications (RAM, Storage etc.) and price correlation analysis.

## LIMITATIONS
- Number of scrape pages: The project is limited to a certain number of pages from the eBay website which may be insufficient for further analysis or statistical analysis.
- Product release date/year: It will be difficult to analyze the price trends over time without the released date to get full insights on the price changes.

> You can check out the full documentation here: <a href='https://medium.com/@samueloyedele/ecommerce-price-monitoring-analysis-using-python-laptop-7ddca1fa8fdf'>here</a>


