# Customer Shopping Behavior Analysis

## 📌 Introduction
This project is about understanding how customers shop and what affects their buying decisions. In today’s retail world, it is very important for companies to know their customers well. By analyzing shopping data, businesses can improve their sales, marketing strategies, and customer satisfaction.

In this project, we used customer purchase data to find patterns, trends, and useful insights that can help a business grow.

---

## 🎯 Project Objective
The main objective of this project is to analyze customer shopping behavior and answer questions like:
- What do customers like to buy?
- What factors influence their decisions?
- Who are the most valuable customers?

The goal is to help the company make better business decisions using data.

---

## 📊 About the Dataset
The dataset contains information about customer purchases.

- Total Records: 3,900
- Total Columns: 18

### The dataset includes:
- Customer details (Age, Gender, Location)
- Product details (Item, Category, Price)
- Shopping behavior (Discounts, Reviews, Frequency)
- Purchase details (Amount, Season, Shipping type)
- Subscription status

Some missing values were found in the review rating column and were handled during data cleaning.

---

## 🛠️ Tools and Technologies Used

### 1. Python
Used for:
- Data cleaning
- Data preprocessing
- Feature creation

Libraries used:
- Pandas
- NumPy
- Matplotlib

### 2. SQL (PostgreSQL)
Used for:
- Storing cleaned data
- Writing queries to analyze data
- Extracting business insights

### 3. Power BI
Used for:
- Creating dashboards
- Visualizing data
- Making insights easy to understand

---

## ⚙️ Project Workflow

### Step 1: Data Collection
- Dataset was provided for analysis

### Step 2: Data Cleaning (Python)
- Loaded dataset using Pandas
- Checked missing values
- Filled missing values using median
- Removed unnecessary columns
- Renamed columns for better readability

### Step 3: Feature Engineering
- Created new columns like:
  - Age Group
  - Purchase Frequency

### Step 4: Database Integration
- Connected Python to PostgreSQL
- Stored cleaned data into database

### Step 5: Data Analysis (SQL)
Performed different types of analysis:
- Revenue by gender
- Top products by rating
- Discount impact analysis
- Customer segmentation
- Subscription vs non-subscription comparison

### Step 6: Data Visualization (Power BI)
- Created interactive dashboard
- Added charts, graphs, and filters
- Displayed key insights clearly

---

## 🔍 Key Insights

- Discounts increase purchase but need proper control
- Some products are highly rated and frequently purchased
- Loyal customers contribute more to revenue
- Subscription users show better engagement
- Certain age groups generate more revenue

---

## 💡 Business Recommendations

- Create strong customer loyalty programs
- Focus on targeted marketing
- Promote best-selling and top-rated products
- Improve subscription benefits
- Use discounts carefully to maintain profit
- Encourage customers to leave reviews

---

## 🚀 Future Scope

- Use real-time data instead of static data
- Apply machine learning to predict customer behavior
- Build recommendation systems
- Automate reports and dashboards
- Expand dataset for better accuracy

---

## 📂 Project Structure
Customer-Shopping-Behavior-Analysis/
│
├── data/ # Dataset files
├── python/ # Python scripts
├── sql/ # SQL queries
├── powerbi/ # Dashboard files
├── report/ # Project report
└── README.md


---

## ✅ Conclusion
This project shows how data analysis can help businesses understand customers better. By using tools like Python, SQL, and Power BI, we were able to find useful insights that can improve decision-making and business performance.

---

## 👨‍💻 Author
- Sabale Vaibhav Sanjay

---

## 📌 Note
This project is created for learning and academic purposes.
