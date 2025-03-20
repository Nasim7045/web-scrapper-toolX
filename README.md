# Web Scraper Tool

## 🚀 Overview
This is a simple web scraper built using Python, Streamlit, Requests, and BeautifulSoup. It extracts useful information from a given website URL, including:

- **Emails** 📧
- **Phone Numbers** 📞
- **Addresses** 🏠
- **Website Title** 🌐
- **Links from the Page** 🔗
- **Names from Headers (h1, h2, h3)** 🔤

The extracted data can be viewed in the Streamlit app and downloaded as a CSV file.

---

## 🛠️ Technologies Used
- **Python** 🐍
- **Streamlit** (For UI)
- **Requests** (For fetching webpage content)
- **BeautifulSoup** (For parsing HTML)
- **Pandas** (For data handling & CSV export)
- **Regular Expressions (re)** (For extracting emails, phone numbers, and addresses)

---

## 📌 Installation & Setup
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-repo/web-scraper.git
cd web-scraper
```

### 2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Streamlit App
```bash
streamlit run app.py
```

---

## 🎯 How to Use
1. Enter a website URL in the input field.
2. Click on the **Scrape** button.
3. The tool will extract emails, phone numbers, addresses, and other information.
4. View the extracted data in the UI.
5. Click on **Download CSV** to save the data.

---

## 🏗️ Project Structure
```
📂 web-scraper
 ├── 📄 app.py               # Main Streamlit App
 ├── 📄 requirements.txt     # Dependencies
 ├── 📄 README.md            # Documentation
```

---

## 📝 Notes
- **Headers** are used in the request to avoid getting blocked.
- **Data Extraction** uses regex for improved accuracy.
- **CSV Export** allows easy data storage and analysis.

---

## 🛡️ Disclaimer
This tool is for educational purposes only. Ensure you comply with website scraping policies before using it.

---

## 📩 Contact
For any issues or suggestions, feel free to reach out!

Happy Scraping! 🚀

