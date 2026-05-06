# Booking-Web-Scraping
# North Africa Hotel Market Analysis — Booking.com Web Scraping

## Project Overview
Automated data collection project analyzing hotel pricing, customer reviews, and competitive positioning across **5 North African markets** (Tunisia, Morocco, Algeria, Libya, Mauritania) to support hospitality market benchmarking and strategic decision-making.

## Business Objective
Conduct competitive market research across the North African hospitality sector by gathering and analyzing hotel pricing strategies, review sentiment, and seasonal demand patterns to inform market entry, pricing optimization, and regional positioning strategies.

## Technical Implementation

### Data Collection
- **Tool Stack:** Python (Selenium WebDriver, Pandas)
- **Data Source:** Booking.com hotel listings
- **Geographic Scope:** 5 countries (Tunisia, Morocco, Algeria, Libya, Mauritania)
- **Temporal Coverage:** 3 seasonal scenarios (Spring, Summer, Low Season)
- **Total Data Points:** ~75+ hotels per country × 3 seasons = **375+ records**

### Methodology
1. **Automated Web Scraping Pipeline:** Built a Selenium-based scraper with retry logic and error handling to ensure data completeness
2. **Multi-dimensional Data Collection:** Extracted hotel name, pricing, review scores, customer review counts, review sentiment labels, and location data
3. **Seasonal Benchmarking:** Analyzed pricing and demand patterns across different travel seasons
4. **Data Structuring:** Exported to structured CSV format for downstream analysis

### Key Data Fields Collected
- Hotel name & location
- Pricing (by season)
- Customer review score (0-10 scale)
- Review count & sentiment label
- Check-in/check-out dates

### Insights & Applications
This dataset supports:
- **Competitive pricing benchmarking** across North African markets
- **Seasonal demand pattern analysis** for revenue optimization
- **Customer sentiment analysis** via review scores and labels
- **Market positioning strategies** based on regional competitive landscapes

## Files in This Repository
- `booking_scraper.py` — Main scraping script
- `north_africa_hotels.csv` — Output dataset
- `Presentation.pdf`, `Web_Scraping_1st_Deliverable.pdf`, etc. — Project documentation and deliverables

## Tools & Libraries
- Python 3.x
- Selenium WebDriver
- Pandas
- ChromeDriver (via webdriver-manager)

## Project Context
Academic project completed as part of **Business Analytics** coursework at **Tunis Business School**, demonstrating practical application of data gathering, market research, and analytical methodologies used in consulting engagements.

---

**Author:** Sirine Othmene  
**Institution:** Tunis Business School, Business Analytics Major | IT Minor
