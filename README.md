online-shopping-customer-behaviour-analysis
An exploratory data analysis project focused on online shopping customer behaviour, purchasing patterns, sales performance and revenue insights using Excel

 **Introduction**
 
This dataset contains online shopping customer behaviour and transaction information. It provides insights into customers' demographics, shopping activities, product preferences, purchasing behaviour and spending patterns across different countries.
I analysed the dataset to understand customer behaviour, evaluate product and sales performance, and identify factors that influence purchasing decisions

**Problem Statement**

The major problem I am trying to solve with this analysis is understanding how customers interact with an online shopping platform and what influences their purchasing decisions.
Businesses often need to understand why customers view products but do not purchase them, which customer groups generate the most revenue, and which product categories perform best.
Through this analysis, I aim to identify purchasing patterns, evaluate customer engagement, compare revenue across countries and product categories, and provide insights that can help improve sales performance and conversion rates

**Data preprocessing and cleaning** 

Remove duplicates: Check for duplicate customer records to avoid double-counting.

Handle missing values: Identify missing information and decide whether to fill or remove affected records.

Check data types: Ensure age, time spent, items viewed and items purchased are numerical values.

Standardise categorical values: Ensure gender, country, device type and product category have consistent spelling and formatting.

Check invalid values: Identify negative ages, negative spending, or impossible values in the numerical columns.

Format currency: Format total_spent_usd as currency in USD.

**Project Structure**

Pre-Analysis Board → Where I defined objectives and analytical approach

In-Analysis Board → Where I explored patterns and generated insights

Post-Analysis Board → Where I summarized findings and recommendations

Dashboard Interface → Where I visualized key metrics


<img width="1310" height="540" alt="adeyeye p 4" src="https://github.com/user-attachments/assets/0fba3cd3-6405-461a-9ba0-b022ddb8998a" />

**key insights**

<img width="364" height="162" alt="4 1" src="https://github.com/user-attachments/assets/61d85b83-8fc7-44c6-8f2a-ca7d579fdedc" />

**Gender performance**


Male spend: $707K (50.47%)
Female spend: $694K (49.53%)
Spending is almost perfectly balanced between male and female customers.
The difference is marginal ($13K), indicating no strong gender dominance in purchasing power

<img width="352" height="157" alt="4 2" src="https://github.com/user-attachments/assets/97d0af66-839e-474f-bfe6-2ebcbba8432a" />

**Age Analysis**
The core revenue drivers are ages 38–47, contributing the largest share.follow by ages 28-47,
Spending declines slightly after age 47 and more significantly after 58.
Younger customers (18–27) are active but spend less than middle-aged groups.

<img width="566" height="195" alt="4 5" src="https://github.com/user-attachments/assets/5affe2fb-2f46-411a-ba74-c24b8dffc103" />

**product category**

Clothing dominates revenue, indicating strong demand and possibly higher purchase frequency.
Categories are relatively close, diversified revenue streams and not over-reliance on one category

<img width="552" height="200" alt="4 3" src="https://github.com/user-attachments/assets/ed0c051e-c7cb-4d84-98cd-032589bbd9fb" />

**country performance**

Top markets:Pakistan ($259K),USA ($257K),Canada ($247K)
Mid-tier: Australia ($222K),UK ($219K)
Lowest: India ($198K)
Revenue is geographically well distributed, but:Pakistan and USA are key revenue drivers while India is the lowest performing country.

<img width="398" height="158" alt="4 4" src="https://github.com/user-attachments/assets/93b5b56d-3562-4e0c-9421-231042190f83" />

**customer behaviour(item view vs item purchase)**

High views across all countries (6K–8K range)
Purchases significantly lower (1.2K–1.5K)
Pakistan & USA has the Highest views andhighest purchases
India: Lowest views and lowest purchases
There is a clear drop-off between viewing and purchasing (conversion gap)
Countries with high engagement (Pakistan, USA) convert better 
India shows low engagement + low conversion, signaling deeper issues


**Reccommendation**

1.Upselling to younger users (18–27) as future high spenders
Retainning 28–47 age group aggressively (they drive revenue now)
Re-engage older users with tailored experiences

2.Doubling Down on High-Performing Categories
Expand Clothing & Sports:More product variety,Premium options

3.Leveraging Behavioral Targeting
 we should Combine: Country + Category + Viewing behavior

4. Improving Conversion Rate (High views but low purchases = lost revenue opportunity)









