🪔 Diwali Sales Data Analysis
This project is an Exploratory Data Analysis (EDA) of Diwali sales data to understand customer behavior, preferences, and key market trends. The insights gained can help in targeted marketing and strategic decision-making for future campaigns.

📌 Project Overview
The dataset includes customer demographic details and their purchasing behavior during the Diwali festival season. The analysis focuses on identifying:

Top-performing age groups and genders

Sales distribution by state and zone

Popular product categories

Occupations with the highest spending

Marital status trends

Top-selling products

📁 Dataset Description
The dataset contains the following columns:

Column Name	Description
User_ID	Unique ID of the customer
Cust_name	Name of the customer
Product_ID	ID of the product purchased
Gender	Gender of the customer
Age Group	Age group category
Age	Age of the customer
Marital_Status	0 = Single, 1 = Married
State	State of residence
Zone	Geographical zone (e.g., North, South)
Occupation	Profession of the customer
Product_Category	Product category purchased
Orders	Number of items ordered
Amount	Total amount spent
🧼 Data Cleaning
Removed null and unnecessary columns (Status, unnamed1)

Converted Amount column to integer for accurate aggregation

Removed rows with missing values

📊 Exploratory Data Analysis
📍 Gender-wise Sales
Majority of buyers are female

Female customers also have higher purchasing power

📍 Age Group Analysis
26-35 age group is the most active

Followed by 36-45 and 18-25 age brackets

📍 State-wise Sales
Uttar Pradesh, Maharashtra, and Karnataka are top-performing states in both orders and revenue

📍 Marital Status
Married women dominate sales, indicating strong buying power in that demographic

📍 Occupation-wise Trends
Most purchases come from IT, Healthcare, and Aviation sectors

📍 Product Categories
Highest sales from:

Food

Footwear

Electronics & Gadgets

📍 Top-Selling Products
Identified 10 most frequently ordered products

📌 Conclusion
Target Audience Insight
Married women aged 26-35, living in Uttar Pradesh, Maharashtra, or Karnataka, working in IT, Healthcare, or Aviation, are most likely to purchase during Diwali — primarily Food, Clothing, and Electronics.

🛠️ Tools & Libraries Used
Python (Pandas, NumPy)

Data Visualization: Seaborn, Matplotlib

Jupyter Notebook / Colab

📎 How to Run
Clone the repository:

bash
Copy
Edit
git clone https://github.com/your-username/diwali-sales-analysis.git
Install the required packages:

bash
Copy
Edit
pip install pandas matplotlib seaborn
Open the Jupyter Notebook:

bash
Copy
Edit
jupyter notebook Diwali_Sales_Analysis.ipynb
📌 Future Scope
Integrate time-based analysis if timestamps are added

Predictive modeling to forecast Diwali sales

Build a dashboard using Plotly Dash or Power BI
