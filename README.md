# Moe’s Webscraper 🕸️

Moe’s Webscraper is an intuitive, Streamlit-powered application that streamlines the process of extracting structured information from any web page. Whether you’re gathering product details, monitoring news updates, or compiling research data, Moe’s Webscraper gives you the flexibility to define exactly what you need—and quickly download it in your preferred format.

---

## 🔑 Key Features

* 🎨 **User-friendly Interface**: Interact with a clean, sidebar-driven Streamlit UI—no coding required.
* 🛠️ **Custom Field Definition**: Specify any HTML elements or CSS selectors to target exactly the data you want.
* 📄 **Automatic Pagination**: Crawl through multi-page listings with a single click.
* ⚡ **Real-time Data Processing**: Extract and preview results instantly using Python’s powerful parsing libraries.
* 📥 **Flexible Export Options**: Download scraped data as **CSV**, **JSON**, or **Excel** files.
* 🤖 **Attended Mode**: Step through a guided scraping session when you need extra control.

---

## 🛠️ Prerequisites

Before installing, make sure you have:

* **Python** 3.6 or higher 🐍
* **pip** (Python package manager) 📦

---

## 🚀 Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/reda-marzouk608/scrape-master.git
   cd scrape-master
   ```
2. **Create and activate a virtual environment** (recommended)

   ```bash
   python -m venv venv
   # On Windows
   venv\Scripts\activate
   # On macOS/Linux
   source venv/bin/activate
   ```
3. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

---

## 🏁 Launching Moe’s Webscraper

Run the app from the project root:

```bash
streamlit run streamlit_app.py
```

Open your browser to **[http://localhost:8501](http://localhost:8501)** (or the URL shown in your terminal).

---

## 📖 Usage

1. **Open the sidebar** and enter the **URL** of the page you want to scrape.
2. **Add one or more field definitions**, such as CSS selectors or XPath expressions, to pinpoint the data elements you need.
3. **Enable pagination** if you want Moe’s Webscraper to navigate through multiple pages automatically.
4. Click **“Scrape”** to see your data populate in real time.
5. **Download** your results as **CSV**, **JSON**, or **Excel** by clicking the corresponding button.

---

✨ **Moe’s Webscraper** empowers you to turn any website into a structured dataset—fast, reliably, and without writing a single line of parsing code. Happy scraping! 🥳
