📊 Customer Behavior Analytics & Dashboarding
📌 Overview
This project is an end-to-end data analytics solution designed to analyze customer purchase patterns and review ratings. The workflow involves extracting and cleaning raw data using Python, storing it in a structured SQL database, and visualizing key insights through an interactive Power BI dashboard. Final insights were presented using Gamma to generate a professional report.

Key Objectives:

Analyze product popularity and average review ratings.

Establish a robust ETL (Extract, Transform, Load) pipeline.

Visualize trends to assist in business decision-making.

📂 Dataset
The dataset focuses on customer transactions and feedback.

Source: [Mention source, e.g., Kaggle, Internal Data, or Simulated]

Key Attributes:

item_purchased: The category/name of the product.

review_rating: Numerical rating given by the customer (1-5).

customer_id: Unique identifier for users.

[Add other columns if applicable, e.g., purchase_amount, location]

🛠 Tools & Technologies
Language: Python 3.12

Libraries: Pandas, SQLAlchemy, Psycopg2 / PyMySQL

Database: PostgreSQL / MySQL

Visualization: Microsoft Power BI

Presentation: Gamma App (AI-powered decks)

🚀 Project Steps
1. Data Cleaning & ETL (Python)
Utilized Pandas to handle missing values and standardize data types.

Established a connection to the database using SQLAlchemy.

Key Skill: Automated the loading of the Pandas DataFrame into SQL tables using to_sql.

2. Database Management
Created a relational database named customer_behavior.

Designed the schema for the customer table.

Executed SQL queries to verify data integrity and perform initial aggregations (e.g., Average rating per item).

3. Dashboard Creation (Power BI)
Connected Power BI to the SQL database using the database connector.

Visuals Created:

Average Rating by Product (Bar Chart).

Top Selling Items (Treemap/Pie Chart).

Customer Rating Distribution (Histogram).

Formatting: Aligned visuals horizontally and applied consistent styling for a professional look.

4. Reporting (Gamma)
Exported key insights and visuals from Power BI.

Used Gamma to generate a structured slide deck summarizing the findings, methodologies, and business recommendations.

📊 Dashboard Results
(Insert Screenshots of your Power BI Dashboard here)

Insight Example: * "The data reveals that while 'Item A' has the highest sales volume, 'Item B' holds the highest customer satisfaction rating of 4.8/5."*

⚙️ How to Run
Prerequisites:

Python 3.x installed.

PostgreSQL or MySQL Server running.

Create a database named customer_behavior in your SQL tool.

Update the connection string in main.py with your credentials (username, password, port).

Run the Script:

Bash

python main.py
View Dashboard:

Open the .pbix file in Power BI.

Click "Refresh" to load the latest data from your local database.
