# Power BI Data Modelling
Rebuilding one clean star schema from 23 messy datasets

Mindset Rules
1. Build a star schema
2. Understand the data before any changes
3. Drop any unnesscary columns
4. Protect the numbers, to recheck after changes

Standardization Specification
1. Ensure column name using snake_case
2. Name the table with following format --> fact_ or dim_
3. Keys must stated from the source or created --> _key or _id
4. Friendly table name and in english

Phase 1 : Prepare & Explore
- Open the messy, understand the data and business needs
- Spot potential dimensions and facts

Phase 2 : Building the dimensions table
- Group the table into one entity
- Reshape into one clean dimension
- Cleaning & standardization

Phase 3 : Building the facts table
- Check for event and its grain
- Build the fact from the details
- Connect every dimension
- Test so the numbers never change

Phase 4 : Polishing
- Recheck the standards
- Add the date table
- Build the measures
- Row level security added
- Final validation
