# Financial-Consumer-Complaints-analysis
## Introduction:
This project an analysis on Consumer complaints on financial products &amp; services for Bank of America from 2017 to 2023, including the dates the complaint was submitted to the CFPB and then sent to the company, the product and issue mentioned in the complaint, and the company's response. 

## Objective:
Develop a Simple Dashboard that provides insightful reporting on Consumer complaints on financial products & services for Bank of America from 2017 to 2023. The dashboard should serve as a decision-support tool highlighting key metrics. 

## Data Source:
The data used in this analysis was sourced from Maven Analytics' website.

## Metadata: 

- Complaint ID: The unique identification number for a complaint
- Submitted via: How the complaint was submitted to the CFPB
- Date submitted: The date the CFPB received the complaint
- Date received: The date the CFPB sent the complaint to the company
- State: The state of the mailing address provided by the consumer
-Product: The type of product the consumer identified in the complaint
- Sub-product	: The type of sub-product the consumer identified in the complaint (not all Products have Sub-products)
- Issue	: The issue the consumer identified in the complaint (possible values are dependent on Product)
- Sub-issue: The sub-issue the consumer identified in the complaint (possible values are dependent on Product and Issue, and not all Issues have corresponding Sub-issues)
- Company public response: The company's optional, public-facing response to a consumer's complaint. Companies can choose to select a response from a pre-set list of options that will be posted on the public database. For example, "Company believes complaint is the result of an isolated error."
- Company response to consumer: This is how the company responded. For example, "Closed with explanation."
Timely response?  Whether the company gave a timely response (Yes/No)


## Data Cleaning and Preparation: 
The data was loaded to Power Query in Microsoft Power Bi where the data types for each column was checked and verified. Empty categorical columns were replaced with N/A. New columns for Month, Month number and Year were created as well as a table to store Dax measures. 


## Key Insights: 
- A total of 62,516 complaints were filed from 2017 to 2023 
- Totalling complaints from 2018 to 2022(2017 and 2023 were not included because the data for those years does not represent a full cycle), the month of April (4328) registered the most number on complaints. February (3510) registered the least. This was to determine which of the months registered the greatest number of complaints.
- It takes about a day for complaints to be responded to and about 94% (58,619) of complaints were responded to in a timely response.
- The top five products for total complaints were as follows:
  1. checking or savings account
  2. credit card or prepaid card
  3. credit reporting, credit repairs services, or other personal consumer reports.
  4. Mortgage
  5. Money transfer, virtual currency, or money service
The main Issues for each product can be identified with the '+' icon in the product-total complaints table.
- Issues are typically resolved by closing the account with an explanation
- California had the most complaints submitted. 


## Recommendations
Based on the analysis of consumer complaints submitted to the CFPB regarding Bank of America's financial products and services from 2017 to 2023, the following recommendations are proposed to support strategic decision-making and enhance customer experience:
1.	Focus on Improving High-Complaint Product Areas: 
Checking/Savings Accounts and Credit Cards recorded the highest number of complaints. Investigate the most frequent issues within these products and prioritize improvements in those areas, such as fee transparency, account access, and unauthorized transactions.
2.	Strengthen Support Around Peak Complaint Periods: 
April consistently recorded the highest volume of complaints. It is recommended to review internal policies, marketing campaigns, or system changes occurring around this period that may contribute to increased customer dissatisfaction. Additional staffing or proactive communication strategies may be needed during this time.
3.	Sustain and Monitor Timely Response Performance: 
With a 94% timely response rate, Bank of America is performing well in addressing complaints promptly. However, it is essential to monitor this KPI regularly to maintain service standards and investigate the remaining 6% to understand and resolve delays.
4.	Enhance Complaint Resolution Communication: 
The most common resolution type is “Closed with explanation.” To reduce repeat complaints and improve customer satisfaction, consider enhancing the clarity and personalization of explanations provided to consumers.
5.	Regional Monitoring and Outreach: 
California showed the highest number of complaints. This may be due to its population size, but it also signals an opportunity to explore regional patterns in service delivery and customer concerns. Targeted outreach or customer education campaigns in high-complaint states may reduce issues and boost customer trust.
6.	Investigate Submission Channels: 
Analyse trends in the “Submitted via” channel to understand if certain platforms (e.g., phone, web, referrals) are associated with complaint types or slower response rates. Optimizing these channels may enhance accessibility and responsiveness.

