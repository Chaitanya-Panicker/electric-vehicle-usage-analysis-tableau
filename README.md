# Electric Vehicle Distribution & Trends Dashboard

![Electric Vehicle Dashboard](dashboard_screenshot.png)  
*Interactive Tableau dashboard visualizing EV trends across the US. (Screenshot from the project visualization)*

[![Tableau](https://img.shields.io/badge/Tableau-Public-blue.svg)](https://public.tableau.com/app/profile/yourusername) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) [![GitHub stars](https://img.shields.io/github/stars/yourusername/ev-trends-dashboard.svg?style=social&label=Star&maxAge=2592000)](https://GitHub.com/yourusername/ev-trends-dashboard/stargazers/)

## 🚀 Project Overview
This project showcases an in-depth analysis of Electric Vehicle (EV) distribution and trends in the United States, leveraging data on Battery Electric Vehicles (BEVs) and Plug-in Hybrid Electric Vehicles (PHEVs). Built using **Tableau Desktop Public Edition**, the dashboard provides interactive visualizations to explore key metrics like total vehicles by state, model year trends, top manufacturers, and Clean Alternative Fuel Vehicle (CAFV) eligibility.

Key highlights:
- **Total Vehicles Analyzed**: 5,220 (2011–2024)
- **Average Electric Range**: 26.88 km
- **BEVs**: 186 | **PHEVs**: 5,034
- Dominated by states like California (5,183 vehicles)
- Top Manufacturer: Toyota (16.4% market share)

This repository demonstrates my skills in **data visualization**, **exploratory data analysis (EDA)**, and **storytelling with data**—perfect for roles in data analysis, business intelligence, or data science.

## 📊 Key Visualizations
- **Geospatial Map**: Distribution of EVs by state, highlighting hotspots like California.
- **Trend Line Chart**: Vehicle counts by model year, showing growth peaks and dips.
- **Bar Chart**: Top 10 vehicle makers (e.g., Toyota, Chevrolet, Ford).
- **Pie Chart**: CAFV eligibility breakdown (66% eligible, 2% unknown, 32% not eligible).
- **Model Breakdown**: Popular models like Prius Prime (48%), RAV4 Prime (13%).

Embed this dashboard in your portfolio or explore it live on [Tableau Public](https://public.tableau.com/app/profile/yourusername/viz/ElectricVehicleDistributionTrends/Dashboard).

## 🔍 Insights & Analysis
From the data:
- **Growth Trends**: EV adoption surged post-2015, with a peak around 2020–2022, likely driven by incentives and tech advancements.
- **Manufacturer Dominance**: Toyota leads with hybrid-focused models, while emerging players like Tesla (implied in BEVs) are gaining ground.
- **Regional Focus**: Over 99% of vehicles are in California—indicating policy impacts like CAFV rebates.
- **Range & Eligibility**: Low average range suggests early-model data; 66% qualify for CAFV, boosting eco-friendly adoption.

These insights were derived through filtering, aggregation, and calculated fields in Tableau, revealing opportunities for policy recommendations and market forecasts.

## 🛠 Technologies Used
- **Tableau Desktop/Public**: For dashboard creation and interactivity.
- **Data Sources**: Clean Alternative Fuel Vehicle (CAFV) dataset (sourced from public APIs or CSV files—see `data/` folder).
- **Other Tools**: Excel for initial cleaning, Python (Pandas) for preprocessing (scripts in `scripts/`).

## 📥 Installation & Setup
1. Clone the repository:
   ```
   git clone https://github.com/yourusername/ev-trends-dashboard.git
   ```
2. Install Tableau Public (free) from [tableau.com](https://www.tableau.com/products/public/download).
3. Open `ev_dashboard.twbx` in Tableau to explore/edit the dashboard.
4. (Optional) For data preprocessing:
   - Install Python dependencies: `pip install -r requirements.txt`
   - Run: `python scripts/clean_data.py`

## ▶️ How to Use
- **View Dashboard**: Open in Tableau or embed via Tableau Public.
- **Interact**: Filter by state, model year, or vehicle type for custom views.
- **Export**: Generate PDFs/images or publish to web for sharing.
- **Extend**: Add your own data sources via Tableau's connectors (e.g., SQL, Google Sheets).

## 🤝 Contributing
Contributions welcome! Fork the repo, create a branch, and submit a PR. Focus on:
- Adding new datasets (e.g., global EV trends).
- Enhancing visualizations (e.g., forecasts with Tableau Prep).
- Bug fixes or performance optimizations.

## 📬 Contact
- LinkedIn: [your-linkedin-profile](https://www.linkedin.com/in/yourusername)
- Email: your.email@example.com
- Portfolio: [your-portfolio-site](https://yourusername.github.io)

## 📄 License
This project is licensed under the MIT License—see [LICENSE](LICENSE) for details.

*Built to showcase data viz expertise—let's connect if you're hiring! 🚀*
