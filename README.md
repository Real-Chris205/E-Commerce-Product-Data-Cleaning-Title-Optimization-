
# E-Commerce Product Data Cleaning &amp; Title Optimization 
### Role : Data Analyst(Intern) 
### Task : Data Cleaning ,Preparation & Optimization 
### Tool : Microsoft Excel 

## Project Overview 
#### Transforming a chaotic 3,847-row e-commerce dataset into a highly structured, analysis-ready file. The engineering process involved standardizing inconsistent column names, handling thousands of missing data points, and programmatic truncation of bloated, unreadable product titles.The main objective was to improve data quality and create a  short title column that makes product titles more suitable for analysis and SEO purpose.

#### The short title feature was created to provide a readable version of the title while retaining essential information.   Product titles were analyzed to identify key components such as product type, attributes, and important keywords. Repetitive and unnecessary words were removed using a combination of Find and Replace and Excel formulas. Excel functions such as Trim, Substitute, Left, and Proper were combined into a single formula to clean, standardize, and shorten the titles. The Proper function ensured consistent capitalization for improved readability. Titles were limited to 50 characters to maintain clarity and meet the required constraints.

# Files
- <a href="https://github.com/Real-Chris205/E-Commerce-Product-Data-Cleaning-Title-Optimization-/blob/main/Data%20cleaning%20hng.xlsx">Cleaned_data</a>
- <a href="https://github.com/Real-Chris205/E-Commerce-Product-Data-Cleaning-Title-Optimization-/blob/main/DATA%20CLEANING%20REPORT.pdf">Report</a>

## Dataset Overview 
### Source : HNG Internship : 

| Column | Type | Description |
|--------|------|-------------|
| Product_id | Integer | Unique product Identifier |
| Title | Text | Full original product title |
| Shortt_title | Text | Engineered column - SEO- Optimized title (<= 50 characters |
| bullet_points | Text | Product feature highlights |
| description | Text | Full product description |
| product_type_id | Integer | Product category identifier |
| product_length | Numeric | Product length measurement |
