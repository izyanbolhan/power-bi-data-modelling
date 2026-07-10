# 📊 Power BI Data Modelling


## 🎯 Objective
To rebuild data model using star schema from 23 messy datasets for optimised data storage and faster refresh rate for reporting.

## 🛠️ Tools

### Data Source :

Dataset composition :

- `dataset.csv` - consist of 23 messy tables

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

## 📂 Methodology
### Phase 1 : Prepare & Explore
- Open the messy, understand the data and business needs
- Spot potential dimensions and facts

<img width="1074" height="786" alt="initial power bi" src="https://github.com/user-attachments/assets/819cc7e6-35c4-4544-9283-12bf26ae1e62" />


### Phase 2 : Building the dimensions table
- Group the table into one entity
- Reshape into one clean dimension
- Cleaning & standardization
<img width="213" height="147" alt="dim table" src="https://github.com/user-attachments/assets/ccb28b02-45e4-46a8-9e73-889f8fa0995e" />


### Phase 3 : Building the facts table
- Check for event and its grain
- Build the fact from the details
- Connect every dimension
- Test so the numbers never change
<img width="209" height="167" alt="facts table" src="https://github.com/user-attachments/assets/34e5b10c-a074-42cf-b244-bc8c2331f1c4" />

### Phase 4 : Polishing
- Recheck the standards
- Add the date table
- Build the measures
- Row level security added
- Final validation

<img width="1634" height="759" alt="final_power_bi" src="https://github.com/user-attachments/assets/ffe6d14f-7cd9-42fb-b23f-745bb7e3da76" />

<img width="1069" height="625" alt="RLS" src="https://github.com/user-attachments/assets/751ee2d5-d73e-4564-b8a0-c9db0d55e586" />

