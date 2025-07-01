# 🕸️ Web Scraping Projects

This repository showcases my hands-on projects in web scraping using **BeautifulSoup** and **requests** in Python. Each notebook demonstrates best practices in ethical scraping, code structure, and robust data handling.

---

## 📁 Project Overview

### 1. Scraping Quotes from [quotes.toscrape.com](http://quotes.toscrape.com)

**File:** `Scraping_Quotes.ipynb`  
**Goal:** Extract inspirational quotes, authors, and associated tags  
**Scale:** 100 quotes across 10 pages  

**Highlights:**
- Dual implementation: **Class-based** and **function-based** approaches
- Automatic pagination handling
- Clean extraction of quote content, author names, and topical tags
- Built-in 1-second polite delay between requests

**Technical Features:**
- Two programming paradigms
- Graceful error handling

---

### 2. ⚽ Scraping Football Player Market Values (Transfermarkt)

**File:** `Scraping_TransferMarkt_Player_Values.ipynb`  
**Goal:** Gather market valuation data for professional footballers  
**Scale:** 500+ players across 20 pages  

_As a football fan, this was my favorite project._

**Highlights:**
- Respectful scraping with **60-second delays** per request
- Extracts player name, age, club, market value, and profile URL
- Strong data validation and error management
- Exports to **CSV** and **JSON** formats

**Technical Features:**
- User-agent spoofing
- Age validation (15–45 years)
- URL standardization

---

### 3. Scraping World Population by Country

**File:** `Scraping_World_Population_by_Country.ipynb`  
**Goal:** Scrape country-wise population data from [Worldometers](https://www.worldometers.info/world-population/population-by-country/)

**Highlights:**
- Multi-strategy DOM selection (ID → class → generic selectors)
- Adaptive handling for dynamic web structures
- Defensive coding for resilience against layout changes
- Informative error reporting and fallback logic

**Technical Features:**
- Tailwind CSS class detection
- Pretty-printed output for debugging
- Modular scraping logic

---

## 🛠️ Technical Stack

- `requests` – HTTP client for sending web requests  
- `BeautifulSoup` – HTML parsing and DOM navigation  
- `pandas` – Data analysis and manipulation  
- `json` – Structured data export  

---

## Best Practices Demonstrated

### Ethical Scraping
- Polite delays (1–60 seconds)
- Respectful server load usage
- Timeout settings and graceful failure handling
- Custom user-agent headers

### Code Quality
- OOP and functional paradigms
- Robust error handling
- Flexible scraping logic with fallbacks
- Clean and validated data pipelines

### Data Management
- Multi-format exports: **CSV**, **JSON**
- Preserved URLs for traceability
- Handling of missing/incomplete fields

---

## Use Cases

- **Market Research:** Analyze trends in football player valuations  
- **Content Analysis:** Explore patterns in quotes and authorship  
- **Web Development:** Parse dynamic HTML tables reliably  
- **Education:** Learn practical and ethical web scraping techniques

---

Each project offers a unique approach to common web scraping challenges — combining clean architecture, strong error handling, and thoughtful data practices.
