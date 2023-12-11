# Context
Mitron Bank is a legacy financial institution headquartered in Hyderabad. They want to introduce a new line of credit cards, aiming to broaden its product offerings and reach in the financial market. 
AtliQ Data Services is requested to make a proposal to implement this project by working with sample data before handing over the full project, which includes 4000 customers across five cities on their online spending and other details.

#	Requirement
Analyze the provided sample data and report key findings to the strategy team of Mitron Bank. This analysis is expected to guide them in tailoring the credit cards to customer needs and market trends by providing insights based on the data, actionable and data-driven recommendations.

#	Task
-	Create Metrics
-	Design Dashboard
-	Present Insights
-	Use additional data based on your own research to support your recommendations.
# Tools used
Power Query: ETL ⭐ PowerBI: Dashboard ⭐ Canva: Graphics

#	Business-related Term
- Avg income utilization % = avg spending / avg income. The higher the average income utilisation %, the more is their likelihood to use credit cards.
-	Payment method: UPI or Unified Payments Interface is a popular mobile payment method that allows you to transfer funds from one bank account to the other, instantly and free of charge.

#	Methodology
-	Data Preprocessing: The dataset will be cleansed and prepared, addressing missing values, outliers, and data inconsistencies.
o	M language to convert month name => date
o	Strange data: number of transaction is 144000 for every month
-	Exploratory Data Analysis (EDA): A comprehensive EDA will be conducted to understand the distribution, summary statistics, and relationships among variables.
-	Data Visualization: leverage Power BI to create insightful graphs, charts, and interactive dashboards.
-	Interpretation and Conclusion: The visualizations and statistical analysis results will be interpreted to derive meaningful conclusions and actionable insights.

# Analysis
1. **Customer Demographic**
>
><img width="1204" alt="image" src="https://github.com/thupham16/banking-analysis/assets/119646834/1c8df802-afd1-4b11-9731-b27f3f0b5ae4">
>
Customers are classified based on demography with key findings:
- Number of male customers is nearly double that of female customers. Additionally, a significant portion of total customers falls within the 25-34 age segment, approximately 38%.
- Mumbai and Chennai cities combined contribute almost half of the total customer base, with 27% and 21% of the customers, respectively.
- The majority of customers, accounting for 78.4%, are married, while single customers make up 21.6% of the total.
- The most popular occupation is Salaried IT employees, followed by Salaried other employees and Freelancers.
- Based on the analysis of monthly average income, customers can be categorized into three groups: under 40k INR (49% of customers), 50-60k INR (46% of customers), and above 70k INR (5% of customers). It reveals that the majority of customers fall within the under 40k INR category, followed closely by the 50-60k INR group.
2. **Spending Behavior**
> ![image](https://github.com/thupham16/banking-analysis/assets/119646834/ac8bcdab-cdbf-44a5-a369-3e0b39f4f32c)

- Spending tends to increase from May, peaking in September, and then declines. Income utilization rate also experience the same trend. September stands out as the month with the highest customer spending and customers are willing to spend the most, warranting further investigation into this season.
- Regarding the number of transactions, it is worth mentioning that an identical count of 144k transactions was observed for each month throughout the analyzed period. However, it is advisable to recheck this data, as such consistent figures across all months may appear unusual for real-world data. Further verification is necessary to ensure the accuracy of the transaction counts.
- Customers in Mumbai exhibit the highest spending levels, aligning with their significant customer representation. Interestingly, Delhi NCR customers rank second in terms of spending, despite accounting for only 18% of the total customer base, which is the second lowest proportion.
- Accross all transactions, credit card is the most favorable payment type, account for 40% of total spending, followed by UPI, Debit Card and Net Banking.
- Male customers' spending doubles that of females, with a particular emphasis on bill payments, while female customers prioritize health and wellness expenses.
- Three-fourths of the total spending is attributed to customers between the ages of 25 and 45. This finding indicates that customers within this age range should be considered as the primary target audience in terms of spending.
