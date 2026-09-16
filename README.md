# 📊 ApexPlanet Data Analytics Internship Portfolio

## 👩‍💻 About This Portfolio

Welcome to my **ApexPlanet Data Analytics Internship Portfolio**.

This repository serves as the central collection of my work completed during the **ApexPlanet Data Analytics Internship**. It brings together the practical skills, analysis, visualizations, business insights, dashboard development, and statistical validation completed across Tasks 1–4.

The internship provided hands-on experience with the end-to-end data analytics workflow:

- Data understanding
- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Statistical analysis
- SQL-based business analysis
- Data visualization
- KPI development
- Business Intelligence
- Interactive dashboard development
- Data storytelling
- Hypothesis testing
- Business insight generation
- Data-driven recommendations

---

# 🎯 Internship Overview

The main purpose of this internship was to develop practical data analytics skills by working with business-oriented datasets and converting raw data into meaningful insights.

The overall analytics journey followed this process:

```text
Raw Data
   ↓
Data Understanding
   ↓
Data Cleaning & Preprocessing
   ↓
Exploratory Data Analysis
   ↓
SQL & Business Analysis
   ↓
Data Visualization
   ↓
KPI Development
   ↓
Power BI Dashboard
   ↓
Statistical Validation
   ↓
Data Storytelling
   ↓
Business Insights & Recommendations
```

---

# 🗂️ Internship Tasks

## 🔹 Task 1 – Data Cleaning, EDA & Visualization

### 🔗 Repository

**[View Task 1 Repository](https://github.com/M-vyshnavi/APPEX-PLANNET-TASK-1)**

### 📌 Objective

Task 1 focused on preparing the ApexPlanet sales dataset for analysis through data exploration, cleaning, preprocessing, exploratory analysis, and visualization.

### Key Work

- Imported and explored the dataset
- Examined dataset dimensions and data types
- Checked missing values
- Removed duplicate records
- Corrected data types where required
- Created a cleaned dataset
- Prepared a data dictionary
- Performed descriptive analysis
- Studied sales, customers, products, categories, and orders
- Created visualizations
- Extracted initial business insights

### 📊 Visualizations

The analysis included:

- Bar charts
- Histograms
- Pie charts
- Box plots
- Scatter plots
- Correlation heatmaps

### 🛠️ Tools & Technologies

- Python
- Google Colab / Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Excel

### 📚 Skills Developed

- Data cleaning
- Data preprocessing
- Exploratory Data Analysis
- Statistical analysis
- Data visualization
- Data interpretation

---

# 🔹 Task 2 – Exploratory Data Analysis & Business Intelligence

### 🔗 Repository

**[View Task 2 Repository](https://github.com/M-vyshnavi/APPEX-PLANNET-TASK-2)**

### 📌 Objective

Task 2 focused on deeper Exploratory Data Analysis and Business Intelligence. The analysis used descriptive statistics, SQL queries, multivariate analysis, and a KPI-focused dashboard mock-up.

### Key Activities

- Performed descriptive statistics
- Studied numerical and categorical variables
- Analyzed data distributions
- Developed business-oriented questions
- Used SQL for data analysis
- Performed filtering and aggregation
- Used grouping and sorting
- Applied joins for multi-table analysis
- Performed multivariate analysis
- Used correlation analysis
- Created visualizations
- Identified important business patterns
- Designed a static BI dashboard mock-up

### 📊 Statistical Analysis

The analysis included:

- Mean
- Median
- Minimum
- Maximum
- Standard deviation
- Frequency distributions
- Categorical summaries

### 🗃️ SQL Analysis

Business questions were explored using SQL operations such as:

```text
SELECT
WHERE
GROUP BY
ORDER BY
Aggregate Functions
Filtering
Joins
```

### 📈 Multivariate Analysis

Relationships between variables were explored using:

- Scatter plots
- Correlation matrices
- Heatmaps
- Comparative visualizations

### 📊 Business Intelligence

The dashboard mock-up focused on:

- KPIs
- Business metrics
- Trends
- Performance indicators

### 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SQL
- Jupyter Notebook
- Excel
- PowerPoint

---

# 🔹 Task 3 – Deep-Dive Analysis & Interactive Power BI Dashboard

### 🔗 Repository

**[View Task 3 Repository](https://github.com/M-vyshnavi/APPEX-PLANNET-TASK-3)**

### 📌 Objective

Task 3 focused on transforming the cleaned business data into an interactive Power BI dashboard.

The main objectives were to:

- Define important KPIs
- Analyze sales performance
- Study product and category performance
- Analyze city-wise sales
- Understand customer purchasing behavior
- Identify repeat customers
- Perform customer cohort analysis
- Identify trends and patterns
- Build an interactive Power BI dashboard
- Present business insights and recommendations

### 📊 Dataset Overview

The Task 3 analysis uses the ApexPlanet Data Analytics Dataset.

The documented dataset contains:

- 1,000 transaction records
- 947 unique customers
- Approximately ₹139.40M in total sales

### Important Columns

- `Customer_ID`
- `Customer_Name`
- `Age`
- `Gender`
- `City`
- `Order_ID`
- `Order_Date`
- `Product`
- `Category`
- `Quantity`
- `Unit_Price`
- `Total_Sales`

### 📌 Key Performance Indicators

The Power BI dashboard includes:

| KPI | Purpose |
|---|---|
| Total Sales | Measures total sales generated |
| Total Transactions | Counts transaction records |
| Unique Customers | Counts distinct customers |
| Average Transaction Value | Measures average sales per transaction |
| Repeat Customers | Identifies customers with multiple transaction records |
| Repeat Customer Rate | Measures repeat customers relative to unique customers |

### 🧮 DAX Measures

Important calculations include:

```text
Total Sales
= SUM(Sheet1[Total_Sales])
```

```text
Total Transactions
= COUNTROWS(Sheet1)
```

```text
Unique Customers
= DISTINCTCOUNT(Sheet1[Customer_ID])
```

```text
Average Transaction Value
= DIVIDE([Total Sales], [Total Transactions])
```

The project also includes DAX logic for identifying repeat customers and calculating the repeat customer rate.

### 🔍 Deep-Dive Analysis

The dashboard examines:

- Monthly sales trends
- Sales by category
- Sales by city
- Top products by sales
- Sales by age group
- Customer purchasing behavior
- Repeat customers
- Customer cohorts
- Customer activity across purchase periods

### 📊 Dashboard Features

The Power BI dashboard contains:

- Total Sales KPI
- Total Transactions KPI
- Unique Customers KPI
- Average Transaction Value KPI
- Repeat Customers KPI
- Repeat Customer Rate KPI
- Monthly Sales Trend
- Sales by Category
- Sales by City
- Top 10 Products by Sales
- Customers by Gender
- Sales by Age Group
- Customer Cohort Analysis
- Interactive filters and slicers

### 🛠️ Tools & Technologies

- Microsoft Power BI
- DAX
- Power Query
- Microsoft Excel
- Data Visualization
- Business Intelligence

### 💡 Key Business Insights

The Task 3 analysis reports that:

- Electronics is the leading category by sales in the analyzed dataset.
- Laptop is the leading product by sales.
- Patna is the highest-sales city.
- The dataset contains 1,000 transaction records.
- There are 947 unique customers.
- 52 customers have at least two transaction records.
- The documented repeat customer rate is approximately 5.49%.

### 💼 Business Recommendations

The analysis suggests considering:

- Customer loyalty programs
- Personalized offers
- Post-purchase communication
- Inventory planning for high-performing categories
- City-level marketing strategies
- Complementary product bundles
- Monitoring customer cohorts

---

# 🔹 Task 4 – Data Storytelling & Statistical Validation

### 🔗 Repository

**[View Task 4 Repository](https://github.com/M-vyshnavi/APPEX-PLANNET-TASK-4)**

### 📌 Objective

Task 4 focused on converting analytical findings into a structured business story and supporting important findings through statistical validation.

### Key Areas

- Business objective definition
- Data overview
- Business insights
- Data visualization
- Statistical validation
- Hypothesis formulation
- Statistical testing
- P-value interpretation
- Confidence intervals
- Business implications
- Recommendations
- Final presentation

### 📖 Data Storytelling

The findings from earlier tasks were organized into a clear business narrative covering:

- Key performance indicators
- Business trends
- Customer-related observations
- Dashboard findings
- Business impact
- Recommendations

### 🧪 Hypothesis Testing

A business-related hypothesis was formulated from the observed data and evaluated using an appropriate statistical method.

The statistical validation process involved:

```text
Business Question
      ↓
Hypothesis Formulation
      ↓
Select Statistical Test
      ↓
Calculate Test Statistic
      ↓
Calculate P-value
      ↓
Interpret Confidence Interval
      ↓
Business Conclusion
```

The Task 4 repository documents statistical methods including:

- T-Test
- Welch's T-Test
- Chi-Squared Test

### 📊 Statistical Interpretation

The analysis uses:

- P-value
- Significance level
- Confidence interval
- Statistical significance

The purpose is to determine whether an observed difference or relationship is supported by statistical evidence.

### 🛠️ Tools & Technologies

- Microsoft Power BI
- Microsoft Excel
- PowerPoint
- GitHub
- Statistical analysis
- Hypothesis testing

---

# 📚 Related Internship Repositories

The individual task repositories are maintained separately and linked below for easy navigation.

| Task | Focus Area | Repository |
|---|---|---|
| **Task 1** | Data Cleaning, EDA & Visualization | [Open Task 1](https://github.com/M-vyshnavi/APPEX-PLANNET-TASK-1) |
| **Task 2** | EDA & Business Intelligence | [Open Task 2](https://github.com/M-vyshnavi/APPEX-PLANNET-TASK-2) |
| **Task 3** | Deep-Dive Analysis & Power BI Dashboard | [Open Task 3](https://github.com/M-vyshnavi/APPEX-PLANNET-TASK-3) |
| **Task 4** | Data Storytelling & Statistical Validation | [Open Task 4](https://github.com/M-vyshnavi/APPEX-PLANNET-TASK-4) |

---

# 🛠️ Tools & Technologies

## Programming & Data Analysis

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy

## Database & Querying

- SQL
- SQL-based business analysis
- Filtering
- Aggregation
- Grouping
- Joins

## Business Intelligence

- Microsoft Power BI
- DAX
- Power Query
- KPI development
- Dashboard design

## Office & Presentation Tools

- Microsoft Excel
- Microsoft PowerPoint

## Development & Documentation

- Google Colab
- Jupyter Notebook
- Git
- GitHub

---

# 📈 Skills Demonstrated

## Technical Skills

- Python Programming
- Data Cleaning
- Data Preprocessing
- Exploratory Data Analysis
- Statistical Analysis
- SQL
- Data Visualization
- Power BI
- DAX
- Power Query
- Dashboard Development
- KPI Analysis
- Hypothesis Testing
- GitHub Documentation

## Analytical Skills

- Business Problem Understanding
- Trend Analysis
- Customer Analysis
- Product Analysis
- Category Analysis
- City-wise Analysis
- Customer Retention Analysis
- Cohort Analysis
- Correlation Analysis
- Statistical Interpretation
- Business Insight Generation
- Data-driven Decision Making

## Communication Skills

- Data Storytelling
- Business Presentation
- Dashboard Presentation
- Insight Communication
- Business Recommendations
- Analytical Reporting

---

# 🔄 End-to-End Data Analytics Workflow

The internship demonstrates how a data analytics project can progress from raw data to business recommendations.

### 1. Data Understanding

Understand the dataset, columns, data types, and business context.

↓

### 2. Data Cleaning

Identify missing values, duplicate records, inconsistent values, and data-type issues.

↓

### 3. Exploratory Data Analysis

Explore distributions, trends, patterns, and relationships within the dataset.

↓

### 4. Business Analysis

Use SQL and analytical techniques to answer business-oriented questions.

↓

### 5. Visualization

Represent important findings using charts and visual summaries.

↓

### 6. KPI Development

Define and calculate metrics that help measure business performance.

↓

### 7. Dashboard Development

Transform analytical results into an interactive Power BI dashboard.

↓

### 8. Statistical Validation

Use hypothesis testing and statistical measures to validate selected findings.

↓

### 9. Data Storytelling

Present the findings in a structured and understandable business narrative.

↓

### 10. Recommendations

Translate analytical findings into practical business considerations.

---

# 📊 Overall Internship Learning

This internship provided practical exposure to the complete data analytics lifecycle.

### Major Learning Outcomes

- Learned to inspect and understand business datasets.
- Improved data cleaning and preprocessing skills.
- Developed practical EDA experience.
- Learned to identify patterns and trends.
- Practiced SQL for business analysis.
- Strengthened data visualization skills.
- Learned to define and calculate KPIs.
- Developed Power BI dashboarding skills.
- Practiced DAX and Power Query.
- Learned customer purchasing and retention analysis.
- Applied statistical validation concepts.
- Improved hypothesis-testing knowledge.
- Developed data storytelling skills.
- Learned to communicate insights clearly.
- Practiced converting analytical results into business recommendations.

---

# 💡 Key Takeaway

The internship demonstrated that data analytics is more than simply creating charts.

A complete analytics process involves:

```text
Understand
   ↓
Clean
   ↓
Explore
   ↓
Analyze
   ↓
Visualize
   ↓
Validate
   ↓
Communicate
   ↓
Recommend
```

The combination of Python, SQL, Power BI, Excel, statistical analysis, and data storytelling helped build a practical understanding of how data can support business decision-making.

---

# 📁 Repository Structure

The master repository can be organized as:

```text
ApexPlanet-Data-Analytics/
│
├── README.md
│
├── Task-1/
│
├── Task-2/
│
├── Task-3/
│
├── Task-4/
│
├── Presentation/
│
└── Screenshots/
```

The individual task repositories remain available through their respective GitHub links.

---

# 🌟 Internship Highlights

### 📌 Task 1
Data cleaning, preprocessing, EDA, statistical analysis, and visualization.

### 📌 Task 2
EDA, SQL business analysis, multivariate analysis, and Business Intelligence concepts.

### 📌 Task 3
Power BI dashboard development, KPI analysis, customer analysis, and cohort analysis.

### 📌 Task 4
Data storytelling, hypothesis testing, statistical validation, and business presentation.

---

# 🎓 Internship Experience

Through the ApexPlanet Data Analytics Internship, I worked across multiple stages of the analytics lifecycle and developed practical experience in handling business data.

The progression from **data preparation to analysis, visualization, dashboarding, statistical validation, and storytelling** provided an end-to-end view of the role of a data analyst.

---

# 🙏 Acknowledgement

I sincerely thank **ApexPlanet Software Pvt. Ltd.** for providing the internship opportunity and practical exposure to data analytics.

The internship provided an opportunity to apply classroom concepts to structured analytics tasks and improve both technical and analytical skills.

---

# 👩‍💻 Author

**Medam Vyshnavi**

**B.Tech – Computer Science & Engineering (Data Science)**

**Data Analytics Intern @ ApexPlanet Software Pvt. Ltd.**

---

# 🔗 GitHub Task Links

- 📊 **Task 1:** https://github.com/M-vyshnavi/APPEX-PLANNET-TASK-1
- 📈 **Task 2:** https://github.com/M-vyshnavi/APPEX-PLANNET-TASK-2
- 📊 **Task 3:** https://github.com/M-vyshnavi/APPEX-PLANNET-TASK-3
- 📋 **Task 4:** https://github.com/M-vyshnavi/APPEX-PLANNET-TASK-4

---

# ⭐ Final Note

Thank you for visiting my **ApexPlanet Data Analytics Internship Portfolio**.

Feel free to explore the individual task repositories to view the notebooks, datasets, analysis, dashboards, presentations, and supporting project files.
