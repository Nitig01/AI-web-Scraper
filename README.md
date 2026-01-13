# AI Web Scraper

## Project Objective
The objective of this project is to build a reliable web scraping system that can extract useful information from modern, dynamic websites where traditional scrapers often fail due to JavaScript rendering, IP blocking, or CAPTCHA.

---

## Project Description
This project scrapes website content using browser automation instead of simple HTTP requests.  
It loads the complete webpage, extracts visible content from the DOM, cleans unnecessary elements, and allows users to query specific information from the scraped data.

The project focuses on real-world scraping challenges such as dynamic content, IP bans, and large unstructured data.

---

## Technologies Used
- **Python** – Core language
- **Selenium** – For browser automation and JavaScript-rendered pages
- **Bright Data Scraping Browser** – To handle IP rotation and CAPTCHA
- **BeautifulSoup** – For HTML parsing and content cleaning
- **Streamlit** – For building a simple user interface
- **LangChain & Ollama LLM** – For intelligent content parsing (used internally)

---

## How It Works
1. User enters a website URL.
2. The website is opened in a remote browser environment.
3. CAPTCHA and IP restrictions are handled automatically.
4. Fully rendered HTML is fetched.
5. Script and style tags are removed.
6. Clean DOM text content is generated.
7. Large content is split into smaller chunks.
8. User can extract specific information by describing what they want.

---

## Why Browser Automation is Used
Many websites load content dynamically using JavaScript.  
Using Selenium ensures the page is fully loaded before extracting data.

---

## Challenges Addressed
- JavaScript-rendered content
- IP blocking and CAPTCHA
- Large and unstructured webpage data
- Avoiding dependency on fixed HTML structure

---

## Key Learnings
- Practical web scraping challenges
- Handling protected websites
- DOM content extraction and cleaning
- Efficient text processing for large pages
- Ethical scraping practices

---

## Ethical Note
This project is intended for scraping publicly available data only and respects w
