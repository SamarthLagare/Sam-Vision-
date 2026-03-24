# SAM VISION 🏢🤖
**Bharat Estate Intelligence | Advanced Property Valuation Engine**

[Live demo](https://samarthlagare.github.io/Sam-Vision-/)
## 📌 Overview
**SAM VISION** is an AI-driven, highly localized property valuation and real estate intelligence dashboard built for the Indian market. It bridges the gap between raw, fragmented real estate data and retail financial literacy. 

By analyzing over 300 localities across 65+ Indian cities, the engine dynamically adjusts base property rates using over 15 micro and macro variables to generate an institutional-grade investment report, complete with predictive forecasting, affordability metrics, and market cycle positioning.

## ✨ Key Features
* **Dynamic Valuation Engine:** Calculates accurate "All-In" property costs (including Stamp Duty and GST) based on exact user requirements (carpet area, floor rise, Vastu facing, amenity grade, etc.).
* **Investment Verdicts:** Automated Buy/Hold/Avoid classification backed by a logic checklist analyzing EMI burden, projected CAGR, and rental yields.
* **Comprehensive Financial Breakdown:** Calculates monthly EMI, down payment, total interest paid, income affordability ratio, and rental break-even years.
* **5-Year Predictive Forecast:** Visualizes projected capital gains over the user's selected holding period.
* **Interactive Geospatial Mapping:** Real-time map rendering and "fly-to" animations for selected localities.
* **One-Click PDF Export:** Generates a beautifully formatted, print-ready intelligence report.

## 🧠 Data Science Methodology
This project utilizes a multi-layered approach to property valuation, moving beyond simple median averages:

1.  **Hedonic Pricing Model:** The core algorithm applies weighted multipliers to baseline rates, adjusting for subjective lifestyle and utility factors (e.g., View Premium, Property Age, Configuration).
2.  **Quant-7 Consensus Engine:** An ensemble simulation that synthesizes multiple valuation approaches to output a highly accurate, market-adjusted price. The models include:
    * Hedonic Regression
    * XGBoost ML Model
    * Neural Net (Ensemble)
    * Gradient Boosting (GBM)
    * Random Forest
    * Comparable Sales Approach
    * DCF (Discounted Cash Flow) Income Approach
3.  **Market Cycle Variance:** Integrates macro-economic phases (Early, Growth, Peak, Correction) to adjust the final Investment Score and timing recommendations.

## 📊 Data Sources (Q1 2026 Estimates)
The baseline parameters (₹/sqft, historical/forward CAGR, rental yields) are triangulated from authoritative industry sources:
* **Primary Pricing:** MagicBricks & 99acres Insight Reports, NoBroker Market Pulse.
* **Institutional Research:** Knight Frank India Real Estate Report, Anarock Research.
* **Regulatory & Macro:** RBI Housing Price Index (HPI), State RERA portals, IGR Maharashtra.

## 💻 Tech Stack
* **Frontend:** HTML5, CSS3 (Glassmorphism UI, CSS Grid/Flexbox), Vanilla JavaScript (ES6+).
* **Data Visualization:** [Chart.js](https://www.chartjs.org/) for predictive line charts.
* **Geospatial Mapping:** [Leaflet.js](https://leafletjs.com/) with Google Maps tile layers.
* **Architecture:** Single Page Application (SPA) / Client-side processing.

