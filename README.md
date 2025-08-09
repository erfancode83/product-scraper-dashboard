# 🛒 Product Scraper Dashboard

This is a simple yet effective web scraping project that extracts product data (titles and prices) from [scrapeme.live](https://scrapeme.live/shop/) and visualizes it using a clean and interactive dashboard built with Streamlit.

The idea behind this project was to practice end-to-end data scraping and presentation — from raw HTML to a user-friendly interface. Perfect for learning, showcasing skills, or using in real-world data collection pipelines.

---

## 🚀 Features

- Scrapes product **title** and **price**
- Saves results to `.csv`
- Automatically downloads product images
- Interactive dashboard with search & visualization
- Clean UI using Streamlit

---

## 🛠️ Technologies Used

- Python 3.x  
- `requests` + `BeautifulSoup4` for scraping  
- `pandas` for data manipulation  
- `streamlit` for dashboard  
- `matplotlib` for optional charting  

---

## 📂 Project Structure

```bash
.
├── app.py                  # Streamlit dashboard
├── scraper.py              # Scraper script
├── scrapeme_products.csv   # Extracted product data
├── images/                 # Downloaded product images
├── requirements.txt        # Project dependencies
└── README.md               # Project overview (you're here!)
