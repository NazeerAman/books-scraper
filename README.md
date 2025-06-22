# 📚 Books to Scrape - Web Scraper

A Python web scraping project that extracts book data from [BooksToScrape.com](https://books.toscrape.com). It collects book titles, prices, ratings, and availability using BeautifulSoup and organizes the results using pandas.

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

## 🛠️ Technologies Used

- Python 3
- BeautifulSoup (`bs4`)
- requests
- pandas

---

## 📦 Installation

1. Clone the repository:

```bash
git clone https://github.com/NazeerAman/books-scraper.git
cd books-scraper
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the scraper:

   use the Jupyter notebook:

```bash
jupyter notebook books_web_scraper.ipynb
```

---

## 🧾 Output Sample

| Title               | Price | Rating | Availability |
|---------------------|-------|--------|----------------|
| A Light in the Attic | 51.77 | Three  | In stock       |
| Tipping the Velvet  | 53.74 | One    | In stock       |
| ...                 | ...   | ...    | ...            |

---

## 📂 Project Structure

```
books-scraper/
├── books_web_scraper.ipynb    # Jupyter Notebook version of the scraper
├── books.csv                  # Scraped book data (CSV)
└── README.md                  # Project documentation
```

---

## 🔐 License

This project is open source and available under the [MIT License](LICENSE).

---

## 🙌 Acknowledgments

- Thanks to [BooksToScrape.com](https://books.toscrape.com) for providing a free practice website for web scraping.

---

## 💡 Author

**Nazeer Aman**  
GitHub: [@NazeerAman](https://github.com/NazeerAman)

---
