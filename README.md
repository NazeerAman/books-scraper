# 📚 Books to Scrape - Web Scraper

A Python web scraping project that extracts book information from [BooksToScrape.com](https://books.toscrape.com/), a sandbox site made for practicing scraping techniques.

This script scrapes multiple pages and collects useful data including **Title**, **Price**, **Star Rating**, and **Availability**, then organizes the data using `pandas`.

---

## 🚀 Features

- Scrapes 50 pages of books from the site
- Extracts:
  - 📖 Book Title
  - 💰 Price
  - ⭐ Star Rating (1 to 5)
  - 📦 Availability (In stock / Out of stock)
- Stores all the data in a structured format
- Outputs a clean dataset (CSV or DataFrame)

---

## 🛠️ Tech Stack

- Python 3
- `requests` – for sending HTTP requests
- `BeautifulSoup` – for parsing HTML content
- `pandas` – for organizing and exporting data

---

## 🧾 Output Sample

| Title                  | Price | Rating | Availability     |
|------------------------|-------|--------|------------------|
| A Light in the Attic  | 51.77 | Three  | In stock         |
| Tipping the Velvet     | 53.74 | One    | In stock         |
| ...                    | ...   | ...    | ...              |

---

## 📂 File Structure

