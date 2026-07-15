# 📊 Power BI Data Modelling
This project demonstrates an end-to-end Power BI business intelligence solution built from 23 raw and unstructured datasets. The objective was to transform messy operational data into a scalable semantic model and interactive dashboard that enables stakeholders to monitor sales performance, customer behavior, campaign effectiveness, inventory status, and operational efficiency.

The project focuses on applying data modelling best practices, dimensional modelling, DAX optimization, and Row-Level Security (RLS) to create a lightweight and efficient Power BI reporting solution.

## 🛠️ Tools

### Data Source :

Dataset composition :

- `dataset.csv` - consist of 23 messy tables

The datasets covered multiple business domains:

- Customer information
- Product catalog
- Sales transactions
- Marketing campaigns
- Promotions
- Inventory management
- Sales planning
- Order processing
- Geographic performance

### Tools :
**Tableau** : Data visualization and business intelligence dahsboard

## 📒 Rules & Standardization
### Mindset Rules
- Build a star schema
- Understand the data before any changes
- Drop any unnesscary columns
- Protect the numbers, to recheck after changes

###  Standardization Specification
- Ensure column name using snake_case
- Name the table with following format --> fact_ or dim_
- Keys must stated from the source or created --> _key or _id
- Friendly table name and in english

## Data Modelling

To create a scalable and optimized Power BI semantic model, the raw datasets were transformed into a **Star Schema dimensional model**.

The final model consists of:

### Dimension Tables (5)

| Dimension Table | Description |
|---|---|
| Customer | Contains customer attributes and segmentation information |
| Campaign | Stores marketing campaign details |
| Product | Provides product hierarchy and attributes |
| Order Flags | Contains order status classifications |
| Geography | Supports regional and location-based analysis |

### Fact Tables (6)

| Fact Table | Description |
|---|---|
| Sales | Stores transactional sales performance data |
| Inventory | Tracks stock availability and inventory movement |
| Promotion Coverage | Measures promotion availability and effectiveness |
| Sales Target | Compares actual performance against business targets |
| Order Process | Analyzes order lifecycle and operational efficiency |
| Campaign Spend | Tracks marketing investment and campaign expenditure |

# 🔄 Data Transformation Process
<img width="1074" height="786" alt="initial power bi" src="https://github.com/user-attachments/assets/819cc7e6-35c4-4544-9283-12bf26ae1e62" />
The raw datasets underwent several transformation steps:

### Data Cleaning
- Removed duplicate records
- Standardized inconsistent values
- Handled missing data
- Corrected data types
- Created consistent business keys

### Data Modelling
- Converted flat datasets into dimension and fact tables
- Established relationships using business keys
- Applied star schema principles
- Reduced data redundancy

### Model Optimization
- Reduced unnecessary columns
- Improved model efficiency
- Created optimized DAX measures
- Designed a lightweight reporting model

# Data Modelling Outcome : 
<img width="1634" height="759" alt="final_power_bi" src="https://github.com/user-attachments/assets/ffe6d14f-7cd9-42fb-b23f-745bb7e3da76" />


# 🔐 Row-Level Security (RLS)
<img width="1069" height="625" alt="RLS" src="https://github.com/user-attachments/assets/751ee2d5-d73e-4564-b8a0-c9db0d55e586" />
Row-Level Security was implemented to ensure controlled data access for different business users.

- Regional managers can only view their assigned geography

This demonstrates practical implementation of Power BI security and governance practices.
