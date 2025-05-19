
# 🕸️ Basic Web Scraping Practice

This project is a beginner-friendly web scraping exercise that demonstrates how to extract and display headlines from the **BBC News** website using Python.

## 📌 Project Objective

The main goal of this notebook is to:
- Understand the basics of web scraping
- Learn how to fetch and parse HTML content
- Extract and display top headlines from a news site
- Practice using libraries like `requests` and `BeautifulSoup`

---

## 🛠️ Tools & Libraries Used

- **Python 3**
- `requests`: to send HTTP requests to the website
- `BeautifulSoup`: to parse and extract elements from the HTML content

---

## 🔍 How It Works

1. **Send an HTTP request** to `https://www.bbc.com/news` using the `requests` library with appropriate headers.
2. **Parse the HTML response** using `BeautifulSoup`.
3. **Locate news headlines** by identifying specific tags and CSS selectors (e.g., `h3` tags and `.gs-c-promo-heading` links).
4. **Extract and print** the top 10 headlines along with their associated links.

---

## 📥 Setup Instructions

1. Clone the repository or download the `.ipynb` file.
2. Install required packages:
   ```bash
   pip install requests beautifulsoup4
   ```
3. Run the notebook using Jupyter or VS Code.

---

## ✅ Output Example

```
1. World leaders react to global event
   🔗 https://www.bbc.com/news/xyz

2. Scientists discover new breakthrough
   🔗 https://www.bbc.com/news/abc
```

(Note: Headlines vary as they are pulled live from the BBC website.)

---

## 📚 What I Learned

- How to inspect web pages using browser developer tools
- How to build simple web scraping scripts
- Importance of using proper headers to avoid getting blocked
- Handling dynamic HTML content using CSS selectors

---

## 🚀 Future Enhancements

- Scrape articles from multiple sections (e.g., tech, business)
- Store results in a CSV or database
- Schedule scraping with a Python scheduler (e.g., `schedule` or `cron`)
- Add error handling for failed requests

---

## 🧠 Disclaimer

This project is for educational purposes only. Please ensure you comply with website terms of service when scraping.
