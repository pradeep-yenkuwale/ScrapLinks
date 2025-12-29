# ScrapLinks

ScrapLinks is a Python-based web scraping tool designed to extract links and data from websites, process the content using **BeautifulSoup**, and store results in **MySQL** and Excel files. It uses **Selenium WebDriver** to handle dynamic content rendered by JavaScript.

---

## Features

- Load a list of target URLs from an Excel file (`URLs.xlsx`)
- Scrape website content using **Selenium** for dynamic pages
- Parse and extract data with **BeautifulSoup**
- Save results into **Excel files** (`results.xlsx`) for quick analysis
- Store scraped data in a **MySQL database** using **PyMySQL**
- Modular code structure for easy customization

---

## Tech Stack

- **Python 3.x**
- **Selenium WebDriver** (ChromeDriver)
- **BeautifulSoup4**
- **PyMySQL**
- **pandas / openpyxl** (for Excel operations)

---

## Installation

1. **Clone the repository**

```bash
git clone https://github.com/pradeep-yenkuwale/ScrapLinks.git
cd ScrapLinks
