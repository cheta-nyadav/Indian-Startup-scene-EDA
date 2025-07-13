# 📊 Indian Startup Funding EDA

This project explores funding trends in Indian startups using real-world data.  
We analyze sectors, cities, top investors, and funding types to uncover key patterns from 2015 to 2023.

📁 Dataset: `startup_funding.csv`  
🧼 Key Steps: Data Cleaning, Exploratory Data Analysis, Visualization  

---
### 🔧 Data Cleaning

- Standardized city and industry names (e.g., "Bangalore" → "Bengaluru")
- Removed unwanted white spaces and missing/null values
- Fixed inconsistent formatting in investor names
- Converted funding dates to a proper datetime format for analysis

---
# 🚀 EDA

This project explores trends and patterns in Indian startup funding using Python (Pandas, Seaborn, Altair, Matplotlib). The dataset includes startup details, founding years, sectors, funding rounds, and more. Our goal is to uncover actionable insights for entrepreneurs, investors, and policymakers.


## 📁 Dataset Columns

- `company_name`
- `founded_year`
- `company_hq_state`, `company_hq_location`
- `sector`
- `amount_usd`
- `funding_round`, `funding_month`, `funding_year`
- `investor`, `founders`, `company_description`


## ✅ Key Questions Explored

### Q1. *Where should I move if I'm starting a business in a certain sector?*

> Created an interactive **sector-wise choropleth map** to show the **top-funded sector in each state**. This helps founders choose the best ecosystem for their domain (e.g., Fintech in Maharashtra, Food & Beverage in Tamil Nadu).

### Q2. *Which sectors are getting the most deals and money?*

> Bar charts show **total number of deals vs. total funding received** across sectors.  
We identified that **a few large deals contribute disproportionately to funding volumes**, especially in sectors like Financial Services.

### Q3. *What are the best months to seek funding?*

> Monthly analysis revealed that:
- **April has a funding spike** 
- **Deal count is highest in Jan–Mar**, but not always with large ticket sizes.
- **Some sectors get consistent funding later in the year**

### Q4. *Which sectors get funded across multiple rounds?*

> Sectors with **high average funding over multiple months** are attractive for investors and may indicate better exit opportunities.  


## 📈 Visualizations Used

- 📊 Bar plots (Seaborn, Matplotlib)
- 🌍 Choropleth maps (Altair + GeoPandas)
- 📅 Time series line plots
- 🧠 Sector-wise interactivity using Altair dropdowns

