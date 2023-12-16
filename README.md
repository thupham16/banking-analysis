This analysis is to propose a development strategy in the Banking domain, provided by Codebasics. Here is the [challenge](https://codebasics.io/challenge/codebasics-resume-project-challenge).

# Problem Statement
Mitron Bank is a legacy financial institution headquartered in Hyderabad. They want to introduce a new line of credit cards, aiming to broaden its product offerings and reach in the financial market. 
AtliQ Data Services is requested to make a proposal to implement this project by working with sample data before handing over the full project, which includes 4000 customers across five cities on their online spending and other details.

#	Requirement
- Requirement: Analyze the provided sample data and report key findings to the strategy team of Mitron Bank. This analysis is expected to guide them in tailoring the credit cards to customer needs and market trends by providing insights based on the data, actionable and data-driven recommendations.
- Task
  -	Create Metrics
  -	Design Dashboard
  -	Present Insights
  -	Use additional data based on your own research to support your recommendations.
# Outputs
- [Interactive Dashboard](https://www.novypro.com/project/banking-analysis-power-bi)
- [Presentation](https://github.com/thupham16/banking-analysis/blob/main/Banking%20analysis.pdf) 
# Tools used
Power Query: ETL ⭐ PowerBI: Dashboard ⭐ Canva: Graphics

#	Business-related Term
- Avg income utilization % = avg spending / avg income. The higher the average income utilisation %, the more is their likelihood to use credit cards.
-	Payment method: UPI or Unified Payments Interface is a popular mobile payment method that allows you to transfer funds from one bank account to the other, instantly and free of charge.

#	Data transformation
Data was transformed with the Power Query editor in Power BI.
- Added a conditional column to fact_spend table to convert month into month number for visualization.
>![image](https://github.com/thupham16/banking-analysis/assets/119646834/5e9c5098-fe46-42f0-a615-2b6bfe785c23)

# Analysis
1. **Customer Demographic**
>
>![image](https://github.com/thupham16/banking-analysis/assets/119646834/47bb30d3-69d3-469c-8424-aa4893c50909)

>
Customers are classified based on demography with key findings:
- Number of male customers is nearly double that of female customers. Additionally, a significant portion of total customers falls within the 25-34 age segment, approximately 38%.
- Mumbai and Chennai cities combined contribute almost half of the total customer base, with 27% and 21% of the customers, respectively.
- The majority of customers, accounting for 78.4%, are married, while single customers make up 21.6% of the total.
- The most popular occupation is Salaried IT employees, followed by Salaried other employees and Freelancers; while Business Owners and Salaried IT employees are those have highest income.
- Based on the analysis of monthly average income, customers can be categorized into three groups: under 40k INR (49% of customers), 50-60k INR (46% of customers), and above 70k INR (5% of customers). It reveals that the majority of customers fall within the under 40k INR category, followed closely by the 50-60k INR group.
>![image](https://github.com/thupham16/banking-analysis/assets/119646834/93d72e4f-7d8d-4355-8438-935c4c4c7a58)
>
There is a moderate positive correlation of 0.64 between income and spending, indicating that as income increases, there tends to be a tendency for spending to increase as well. However, it is important to note that correlation does not imply causation, and further investigation is needed to establish any causal relationship between income and spending.

2. **Spending Behavior**
> ![image](https://github.com/thupham16/banking-analysis/assets/119646834/1179fb91-ecc2-4eda-8507-1516133b4a1d)


- Spending tends to increase from May, peaking in September, and then declines. Income utilization rate also experience the same trend. September stands out as the month with the highest customer spending and customers are willing to spend the most, warranting further investigation into this season.
- Regarding the number of transactions, it is worth mentioning that an identical count of 144k transactions was observed for each month throughout the analyzed period. However, it is advisable to recheck this data, as such consistent figures across all months may appear unusual for real-world data. Further verification is necessary to ensure the accuracy of the transaction counts.
- Customers in Mumbai exhibit the highest spending levels, aligning with their significant customer representation. Interestingly, Delhi NCR customers rank second in terms of spending, despite accounting for only 18% of the total customer base, which is the second lowest proportion.
- Accross all transactions, credit card is the most favorable payment type, account for 40% of total spending, followed by UPI, Debit Card and Net Banking.
- Male customers' spending doubles that of females, with a particular emphasis on bill payments, while female customers prioritize health and wellness expenses.
- Three-fourths of the total spending is attributed to customers between the ages of 25 and 45. This finding indicates that customers within this age range should be considered as the primary target audience in terms of spending.
>
>![image](https://github.com/thupham16/banking-analysis/assets/119646834/7fb76e5b-d51f-4955-a21a-8995ce2f3bee)

- Customers allocate a significant portion of their income towards expenditures with average income utilization rate at 42%. This indicates a greater likelihood of customers relying on credit cards to manage their expenses and make purchases.
- Customers in the 34-45 years old segment are utilizing a larger proportion of their income for spending purposes with 47%, which highlights their ability to use credit cards for their purchases.
- While Salaried IT employees spend the most with highest utilization rate at 51%, Freelancers also a potential group for using credit cards as they have lower income but utilization rate rank 2nd high at 46%.
- Male customers demonstrate a higher demand for using credit cards, as indicated by their higher spending and utilization rate.

3. **Key Customer Segment and Recommended credit card features**
>
  | Key Customer Segment | Purpose | Recommendation |
  | --- | -------- | -------- |
  | High value customer group: high income - high utilization rate <br>- Salaried IT employees <br>- Male <br>- 35-45 years old <br>- Main category for spending: Bills, Groceries & Electronics <br>- Location: Mumbai, Delhi NCR| Maintain and Enhance spending habits| - Accelerated Rewards <br>- High Credit Limits and Flexibility <br>- Exclusive Merchant Offers <br>- Concierge Services|
  | Potential customer group: high income - low utilization rate <br>- Business Owner <br>- Male <br>- 25-34 years old <br>- Main category for spending: Bills, Groceries & Electronics <br>- Location: Mumbai, Delhi NCR| Boost spending and Increase card usage| - Spend More, Earn More Rewards <br>- Exclusive Merchant Offers <br>- Annual Fee Waivers <br>- Enhanced Purchase Protection|
>
This analysis focuses on developing new credit card features based on key customer segments with two segments were identified: high-income, high utilization rate and high-income, low utilization rate. I recommend to focus on high income group as this group typically has greater spending power, allowing them to make significant purchases and contribute to higher transaction volumes as well as with a lower credit risk for a launching period of a new line. The proposed features cater to the unique needs of this segment, promote responsible spending, and aim to increase card usage and customer satisfaction. By tailoring the credit card offerings to the high-income segment, issuers can effectively meet their preferences and drive engagement.
