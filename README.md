
# 📚 BookMiner

**BookMiner** is a data pipeline project that scrapes book data from web pages, stores the raw HTML, processes and combines the data, and performs exploratory data analysis (EDA) to derive insights.

## 🚀 Project Workflow

1. **Web Scraping**  
   Scrapes book listings from online pages and stores the HTML files.

2. **Data Extraction & Storage**  
   Parses and combines data from multiple HTML pages into a single structured CSV file.

3. **Exploratory Data Analysis (EDA)**  
   Performs visual and statistical analysis to uncover patterns in book pricing, ratings, value scores, and more.

## 📁 Project Structure

```
├── 1_scraping.ipynb        # Scrapes book data and stores HTML files
├── 2_EDA.ipynb             # Performs EDA on the combined CSV data
├── DATA.csv                # Cleaned and structured dataset
├── README.md               # Project overview and instructions
├── htmls                   # All scraped pages from website
```

## 📊 Sample Insights
- Price distribution of books
- Correlation between rating and value score
- Most common price ranges for high-rated books

## 🛠️ Tools & Libraries
- Python (BeautifulSoup, Requests, Pandas)
- Jupyter Notebook
- Matplotlib, Seaborn for visualization

## 📌 Getting Started

1. Clone the repo:
```bash
git clone https://github.com/your-username/BookMiner.git
cd BookMiner
```

2. Run the notebooks in order:
   - `1_scraping.ipynb`
   - `2_EDA.ipynb`

## 📃 License
This project is for educational and non-commercial use.

---

*Made with ❤️ for data and books.*
