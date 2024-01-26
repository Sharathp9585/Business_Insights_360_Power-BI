# Business Insights 360 in PowerBI

## Project Overview
AtliQ Hardware, experiencing rapid growth, plans to deploy Power BI for data analytics, aiming to outpace competitors and drive data-driven decisions. The project targets stakeholder queries in finance, sales, marketing, and supply chain aspects.
### Access Live Interactive Dashboard [Business Insights 360 Dashboard](https://app.powerbi.com/view?r=eyJrIjoiMWQ3YjFkMWMtMzAyYS00ODgxLWFiNTgtMjhiZmM4MmYxNTljIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)

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
   - 4 regions: APAC, EU, NA, LATAM

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

## Power BI Developmental Pipeline

Visualizing the development process using Power BI is essential for tracking progress. Below is an illustrative representation of the Power BI developmental pipeline:

![Power BI Developmental Pipeline](https://github.com/Sharathp9585/Business_Insights_360_Power-BI/assets/155342101/0ea42097-399d-4e33-967a-3fb15f765be5)
## Data Modelling
<img width="838" alt="Data_model" src="https://github.com/Sharathp9585/Business_Insights_360_Power-BI/assets/155342101/2b5b8f04-2e43-48ba-88ea-c57b4d20bafe">

## Dashboard [Access here](https://app.powerbi.com/view?r=eyJrIjoiMWQ3YjFkMWMtMzAyYS00ODgxLWFiNTgtMjhiZmM4MmYxNTljIiwidCI6ImM2ZTU0OWIzLTVmNDUtNDAzMi1hYWU5LWQ0MjQ0ZGM1YjJjNCJ9)


In response to the mock-ups received as requirements, the team initiates the process of designing visuals and creating measures as needed.

### Home View

The Home view serves as the central hub, presenting users with convenient access to various specific views through dedicated buttons. Users can seamlessly navigate to their desired sections by clicking on the respective buttons.

![home](https://github.com/Sharathp9585/Business_Insights_360_Power-BI/assets/155342101/7d17cc07-7294-441e-b93a-c850f480efe6)

### Finance View

Get comprehensive Profit and Loss (P&L) statements effortlessly, tailoring analyses for specific customers, products, or countries, and aggregating data over flexible time periods.
![finance](https://github.com/Sharathp9585/Business_Insights_360_Power-BI/assets/155342101/3c47cb34-9a54-4dea-843c-ded078b14acb)

### Sales View
Examine your product(s) performance by scrutinizing critical metrics such as Net Sales and Gross Margin.
![sales](https://github.com/Sharathp9585/Business_Insights_360_Power-BI/assets/155342101/21703268-95cc-463c-863d-d3cc3c362c5b)

### Market View
Analyze the performance of the customer(s) over key metrics like Net Sales, Gross Margin and view the same in profitability / Growth matrix.
![market](https://github.com/Sharathp9585/Business_Insights_360_Power-BI/assets/155342101/af8ee9bd-fe43-4faa-8646-6f4b11f1420c)

### Supply Chain View
Evaluate Forecast Accuracy, Net Error, and risk profiles for various entities such as products, segments, categorie
s, and customers. Gain a comprehensive understanding of forecasting precision and associated risks for informed decision-making.
![supply_chain](https://github.com/Sharathp9585/Business_Insights_360_Power-BI/assets/155342101/9ddc4fbf-e117-4ae0-848a-1de3d0c1a12b)

### Executive View
A high-level executive dashboard that consolidates key insights from all dimensions of the business. Provide a centralized view to executives, offering comprehensive and strategic overviews across various facets of the organization.
![exec](https://github.com/Sharathp9585/Business_Insights_360_Power-BI/assets/155342101/5dc5f37a-b129-41ba-8104-d9653a5b4a98)
## Project Outcomes

The implementation of Power BI dashboards addressed several challenges and yielded significant outcomes for Atliq Hardware:

### Overcoming Regional Challenges:

The project successfully navigated and mitigated substantial challenges faced by Atliq Hardware, particularly in Latin America. The Power BI dashboards provided a comprehensive understanding of regional dynamics, aiding strategic decision-making and contributing to the mitigation of significant losses.

### Efficient Data Analysis Beyond Excel:

By transitioning from relying solely on Excel to implementing Power BI, the company overcame limitations related to its size and extensive data. The project empowered Atliq Hardware with advanced analytics capabilities, enabling more efficient and insightful data analysis, thereby enhancing overall operational efficiency.

### Enhanced Transparency and Decision-Making:

The Power BI dashboards fulfilled stakeholders' need for increased transparency in data. The project delivered clear and accessible visualizations, facilitating data-driven decision-making across diverse markets and functions. This enhanced transparency not only improved decision-making processes but also fostered a more collaborative and informed organizational culture.

## 📊 Learned Technical Skills

### Languages:
- 📊 SQL
- 💡 DAX language
- 🗄️ M language (for creating date tables)

### Tools:
- 📊 PowerBi Desktop
- 📈 Excel
- 🛠️ DAX studio (utilized for optimizing reports)
- 📂 Project charter file (for comprehensive project management)

### PowerBI Technical Proficiency:
- 📊 Creating calculated columns
- 📏 Crafting measures using DAX language
- 🛠️ Mastering data modeling for effective visualization
- 🔄 Leveraging Bookmarks for seamless visual switching
- 🚀 Page navigation with buttons for user-friendly reports
- 📅 Creating date tables using M language
- 🔄 Dynamic titles based on applied filters
- 📊 Incorporating KPI indicators for strategic insights
- 🎨 Conditional formatting of visual values
- 🛠️ Implementing data validation techniques

### PowerBI Services and Deployment:
- 📈 Navigating PowerBi services for cloud-based capabilities
- 🚀 Efficiently publishing reports to PowerBi services
- ⚙️ Configuring personal gateways for data auto-refresh setup

### Business Related Terms Acquired:
- 💰 Gross Price
- 📉 Pre-Invoice Deductions
- 📈 Post-Invoice Deductions
- 💵 Net Invoice Sale
- 📈 Gross Margin
- 💰 Net Sales
- 💼 Net Profit
- 📉 COGC (Cost of Goods Sold)
- 📅 YTD (Year to Date)
- 📆 YTG (Year to Go)




