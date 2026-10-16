# Superstore Sales Analysis

An end-to-end data analysis project using Python, Pandas, MySQL and Seaborn to uncover sales patterns in the Superstore dataset.

## Tools Used
Python, Pandas, MySQL, SQLAlchemy, Matplotlib, Seaborn, Jupyter Notebook

## Project Workflow
1. Data cleaning: handled missing values and converted date columns
2. Feature engineering: created Year, Month and Ship Days columns
3. Stored the cleaned data in a MySQL database
4. Ran SQL queries for category, region and product analysis
5. Built visualizations and summarized insights

## Key Insights
- Top-selling category: Technology
- Top-performing region: West
- Sales trend: sales have grown year over year
- Peak sales month: December
- Best-selling product: Canon imageCLASS 2200 Advanced Copier

## Project Structure
- data/: raw and cleaned datasets
- notebooks/analysis.ipynb: cleaning, analysis and charts
- README.md: project overview

## How to Run
1. Install the required libraries: pandas, numpy, matplotlib, seaborn, sqlalchemy, mysql-connector-python
2. Place the dataset in the data/ folder
3. Create a MySQL database named superstore_db
4. Update the MySQL password in the connection cell of the notebook
5. Run the notebook cells in order