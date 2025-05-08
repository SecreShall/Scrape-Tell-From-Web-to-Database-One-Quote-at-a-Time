# 📝 Quotes Web Scraping Project  

🚀 **Extract Quotes & Author Insights with PostgreSQL Integration**  

Welcome to the **Quotes Web Scraping Project**, an automated tool designed to collect, analyze, and store inspiring quotes and detailed author biographies from [Quotes to Scrape](https://quotes.toscrape.com/). This project leverages Python for efficient web scraping, PostgreSQL for structured data storage, and beautiful data parsing techniques to ensure seamless handling of extracted information.

## 🏆 Key Features  
✅ **Scrape Quotes & Tags** – Extract all available quotes along with associated tags for better categorization.  
✅ **Author Insights** – Gather detailed information about authors, including birth date, place, and personal descriptions.  
✅ **Database Integration** – Store scraped data in PostgreSQL, ensuring efficient query performance and structured storage.  
✅ **Optimized Web Scraping** – Uses `requests` and `BeautifulSoup` for reliable data extraction with minimal overhead.  
✅ **Scalable Architecture** – Easily extendable to support more websites and integrate additional metadata.  

## 🏛 Project Architecture  
This project follows a modular and structured approach to ensure maintainability and efficiency.  

### 📜 Quotes Table  
**id** (SERIAL, PRIMARY KEY)  
**text** (TEXT)  
*author_id* (INT, FOREIGN KEY)  
*tags* (TEXT[])  

### 👤 Authors Table  
**id** (SERIAL, PRIMARY KEY)  
**name** (TEXT)  
*birth_date* (TEXT)  
*birth_place* (TEXT)  
*description* (TEXT)  

## 🛠 Technologies Used  
🔹 **Python** – Core programming language used for scripting the scraper.  
🔹 **PostgreSQL** – Robust relational database system for storing extracted quotes and authors.  
🔹 **Requests & BeautifulSoup** – Libraries used for fetching and parsing webpage data.  
🔹 **psycopg2** – PostgreSQL connector for Python ensuring smooth database interactions.  

---

## 👤 Author
Developed by **Cley**  
📧 Contact: 02clintaudrey@gmail.com 
🌐 GitHub: SecreShall
