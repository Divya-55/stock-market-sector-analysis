# Stock Market Sector Analysis

### Objective

This project aims to identify which sectors and specific stocks are **most suitable for beginner investors**, with a focus on:

- **Safety** – lower risk and volatility
- **Stability** – consistent returns and solid fundamentals
- **Long-Term Growth** – potential for steady value increase over time

The analysis is performed using a structured dataset of publicly listed companies across sectors, and visualized using Power BI.

---

### Project Structure

| File | Description |
|------|-------------|
| `project.ipynb` | Python notebook for data analysis |
| `final.csv` | Cleaned dataset containing 50+ stocks |
| `stock_market_sector_analysis.pbix` | Power BI dashboard |
| `README.md` | Project documentation |

---

### Tools & Libraries Used

- `pandas`, `matplotlib` – for data analysis and visualization
- `requests`, `BeautifulSoup (bs4)`, `re`, `time` – for scraping data from the web
- `Power BI` – for dashboard visualization

---

### Dataset Overview

The dataset includes ~50 stocks from multiple sectors, with the following attributes:

- **CMP (Current Market Price)**
- **Promoter Holding %**
- **Debt (in Crores)**
- **Returns** – 6 Months, 1 Year, 3 Years
- **P/E Ratio, EPS**
- **All-time high & low prices**
- **Sector classification**
- **Market Cap & Volume**

---

### Key Insights

#### 1. Top Performing Sector: **Aerospace & Defence**

- Multiple stocks in this sector (e.g., *Hindustan Aeronautics*, *Mazagon Dock*, *Solar Industries*) showed **80–180% return** over 3 years.
- These companies also had **high promoter holdings** (above 70%) and **low debt levels**, making them ideal for safe investing.

#### 2. Importance of Promoter Holding %

- Stocks with promoter holding above 70% were often more stable and had better long-term performance.
- Indicates trust and vested interest from company founders/owners.

#### 3. Returns Over Time

- Some companies gave high **short-term** returns but had inconsistent long-term patterns.
- This analysis helps separate **hype stocks** from **genuinely strong stocks**.

#### 4. Debt & P/E Ratio as Risk Indicators

- Companies with very high debt or extreme P/E ratios were flagged as potentially risky.
- Beginners are advised to avoid such stocks unless thoroughly researched.

---

### Relevance for Beginner Investors

This analysis guides beginners on:

- **Which sectors to explore first**
- **How to compare stocks using basic financial indicators**
- **Avoiding traps like high returns with high risk**
- **Using promoter holding and past performance as filters**

---

### Dashboard

An interactive Power BI dashboard lets users:

- Filter stocks by sector
- Compare multi-year returns
- Visualize financial ratios for better decision-making

---


### About Me

This project was created as part of my data analytics learning journey and interview preparation.  
It showcases my skills in:
- Data wrangling
- Financial analysis
- Storytelling with data
- Dashboard creation (Power BI)

