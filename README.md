# Amazon Web Scraping using Python (BeautifulSoup)

## Project Overview
This project demonstrates how to perform **Web Scraping on Amazon Website** using Python libraries such as **Requests** and **BeautifulSoup**.

The main objective of this project is to automatically extract product-related information such as:

- Product Name
- Price
- Ratings
- Reviews
- Customer Details

Instead of manually collecting data from Amazon, this automation script collects data directly from the HTML structure of the webpage.


## Technologies Used

- Python
- Requests
- BeautifulSoup (bs4)
- LXML Parser
- CSV (for data storage)
- Jupyter Notebook


## Project Workflow

1. Send request to Amazon webpage using Requests Library  
2. Use User-Agent to avoid bot detection  
3. Get HTML content of webpage  
4. Parse HTML using BeautifulSoup  
5. Extract product information  
6. Store extracted data into CSV file  

```
## Project Structure

Amazon-Web-Scraping/
│
├── Amazon_Web_Scraping.ipynb
├── README.md
└── output.csv
```
