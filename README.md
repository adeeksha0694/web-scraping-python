# Web Scraping Project

This is a beginner-level Python web scraping project.

In this project, I used Python to get product information from a website. I extracted the product **title and price**, cleaned the data, and saved it into a CSV file.

## What I Used

* Python
* Requests
* BeautifulSoup
* Pandas
* CSV

## What This Project Does

The project follows these steps:

1. Connects to a website using Python.
2. Gets the webpage content.
3. Uses BeautifulSoup to read the HTML.
4. Extracts the product title and price.
5. Cleans the extracted data.
6. Saves the data into a CSV file.
7. Reads the CSV file using Pandas.

## Project Files

```text
Web-Scraping-Project/
│
├── Product_Price_Web_Scraper_using_Python.ipynb
├── ProductWebScrapperDataset.csv
└── README.md
```

### Web Scraper Project.ipynb

This Jupyter Notebook contains the Python code used for web scraping and data processing.

### WebScrapperDataset.csv

This file contains the product information collected by the scraper.

The CSV contains:

* Title
* Price
* Date

## Libraries Used

Install the required libraries:

```bash
pip install requests beautifulsoup4 pandas
```

## Example

The scraper extracts information such as:

```text
Product Title: ...
Price: ...
Date: ...
```

The data is then saved into the CSV file.

## What I Learned

Through this project, I learned:

* How web scraping works
* How to use Requests
* How to use BeautifulSoup
* How to extract data from HTML
* How to clean simple data
* How to save data into a CSV file
* How to read CSV files using Pandas

## How to Run

1. Download or clone this repository.
2. Open `Product_Price_Web_Scraper_using_Python.ipynb` in Jupyter Notebook or JupyterLab.
3. Install the required libraries.
4. Run the notebook cells in order.
5. The scraped data will be saved in `ProductWebScrapperDataset.csv`.

