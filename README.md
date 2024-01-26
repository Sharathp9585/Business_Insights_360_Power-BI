# Business_Insights_360_Power-BI

## Project Overview
AtliQ Hardware, experiencing rapid growth, plans to deploy Power BI for data analytics, aiming to outpace competitors and drive data-driven decisions. The project targets stakeholder queries in finance, sales, marketing, and supply chain aspects.

## Details of the Project

### Company and its Business Model
#### Atliq Hardware Overview

- **Specialization:**
  - Leading in computer and peripheral production, offering a diverse range including keyboards, mice, desktops, and more.

- **Customer Engagement:**
  - **Online Presence:**
    - Serving a diverse online clientele through established platforms like Flipkart and Amazon.
  - **Offline Reach:**
    - Extending offerings to physical stores with partnerships with Chroma, Best Buy, and Staples.

- **Global Footprint:**
  - Not confined to India, Atliq Hardware reaches a global audience, resonating with users who value quality and innovation.

- **Distribution Channels:**
  - **Retail Excellence:**
    - Strategic alliances with retail outlets ensure widespread accessibility in consumer electronics stores.
  - **Direct Engagement:**
    - Personalized customer experiences through direct sales channels.
  - **Strategic Alliances:**
    - Collaborating with large distributors for efficient product distribution on a broader scale.

## Project Significance

1. **Challenges Faced:**
   - While Atliq experienced substantial growth over the years, it encountered significant challenges, particularly in Latin America, leading to substantial losses.

2. **Excel Limitations:**
   - Relying solely on Excel for analysis proved inadequate, given the company's size and extensive data, necessitating a more robust solution for effective decision-making.

3. **Transparency and Data-Driven Decisions:**
   - Stakeholders expressed the need for increased transparency in data to facilitate data-driven decision-making across markets and functions.
  
## Dataset Understanding

Understanding the available data is crucial for effective analysis. Before delving into the analysis, gaining a clear understanding of the available datasets is essential.

### Dimension Tables:

1. **dim_customer:**
   - 27 distinct markets (e.g., India, USA, Spain)
   - 75 distinct customers across markets
   - 2 types of platforms: Brick & Mortar (Physical/offline store), E-commerce (Online Store - Amazon, Flipkart)
   - Three channels: Retailer, Direct, Distributors

2. **dim_market:**
   - 27 distinct markets (e.g., India, USA, Spain)
   - 7 sub-zones
   - 4 regions: APAC, EU, nan, LATAM

3. **dim_product:**
   - Divisions: P & A, Peripherals, Accessories, PC, Notebook, Desktop, N & S, Networking, Storage
   - 14 different categories (e.g., Internal HDD, keyboard)
   - Various variants available for the same product

### Fact Tables:

1. **fact_forecast_monthly:**
   - Used for forecasting customer needs in advance
   - Denormalized data warehouse for analytical work
   - Date of the month replaced by the start date
   - Columns include forecast quantity needed by the customer

2. **fact_sales_monthly:**
   - Similar to fact_forecast_monthly but with the last column containing the sold quantity instead of forecast value

### Additional Datasets (gdb056):

1. **freight_cost:**
   - Details of travel cost and other expenses for each market with fiscal year

2. **gross_price:**
   - Details of gross prices with product codes

3. **manufacturing_cost:**
   - Details of manufacturing costs with product codes and year

4. **Pre_invoice_deductions:**
   - Details of pre-invoice deductions percentage for each customer with year

5. **Post_invoice_deductions:**
   - Details of post-invoice deductions and other deductions

Understanding these datasets is foundational for meaningful analysis and will contribute to higher customer satisfaction, reduced warehousing costs, and informed decision-making.




