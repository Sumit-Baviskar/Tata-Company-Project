# :chart_with_upwards_trend:   Tata-Company-Project (Data Visualisation: Empowering Business with Effective Insights)  :chart_with_upwards_trend:

# **Problem Statement :**


The online retail store is aiming to enhance its strategic decision-making through data-driven insights. To support the CEO and CMO in making informed choices about the company's expansion strategy, we will be analyzing the revenue trends, customer behavior, and regional demand. The analysis will be performed on a clean and structured dataset, ensuring no adverse impact from erroneous data. The goal is to provide the executives with clear visualizations and insights that will allow them to understand the main factors influencing the store’s performance and how to leverage them for future growth.


## **Specific Requirements :**

1. **Revenue Trends for 2011 (CEO)**:  
   The CEO seeks an analysis of the monthly revenue for the year 2011 to identify seasonal patterns, fluctuations, and trends. This information will help the CEO forecast revenue for the upcoming year and plan for peak and low months.

2. **Top 10 Countries by Revenue (CMO)**:  
   The CMO wants a visualization of the top 10 countries generating the highest revenue, excluding the United Kingdom. Additionally, the quantity of items sold in each country should be presented alongside the revenue figures. This analysis will inform the CMO’s marketing and pricing strategies for the highest-performing regions.

3. **Top 10 Customers by Revenue (CMO)**:  
   The CMO requires a ranking of the top 10 customers by revenue, starting with the highest-paying customer. The CMO is focused on ensuring that high-revenue customers remain satisfied and loyal. This visualization will help in identifying key customers who can be targeted for personalized marketing and loyalty programs.

4. **Demand Distribution by Country (CEO)**:  
   The CEO wants to view a geographical distribution of customer demand across all countries (excluding the United Kingdom). This visualization will help the CEO identify regions with high demand, which will inform the company’s expansion strategy and decision-making process regarding targeting these markets.

---

# **Objectives :**

- **Data Cleaning**:  
   The dataset will be reviewed for inconsistencies and errors. We will ensure that negative quantities and unit prices below $0 are removed or corrected. Data integrity will be prioritized to provide reliable insights.
  
- **Data Visualization**:  
   The visuals for each question will be created in Tableau or Power BI (with separate tabs for each question) to make the data easily interpretable and actionable.

- **Insights**:  
   Each visual will be accompanied by insights that explain key observations, trends, and their implications for decision-making. This will empower the CEO and CMO to make informed decisions that align with the company's growth and expansion strategy.

By providing detailed, clean, and insightful visualizations, the project will assist the executives in making targeted and effective decisions regarding expansion and improving overall business performance.


# Dataset - Online Retail 

Dr Daqing Chen, Director: Public Analytics group. chend '@' lsbu.ac.uk, School of Engineering, London South Bank University, London SE1 0AA, UK. 

:link:     **Data set Link---https://www.kaggle.com/datasets/tunguz/online-retail**


# :chart_with_upwards_trend:  **Visualization Tools - Power BI and Tableau**  :chart_with_upwards_trend:

 
So before performing tasks , we have to clean the data as per requirement. As the “data is new oil,but we cannot use it in raw form “ so we have to clean before use .So company’s CMO and CEO can take data driven decision for company.  

There was 2 requirement--
- Create a check that the quantity should not be below 1 unit
  
- Create a check that the Unit price should not be below $0 

For which I have used tableau filter for this task moving to the task. Now as the data is clean we can start our data analysis part in this project 


 
# :paperclip: TASK 1 **(Monthly revenue of 2011)**
**The CEO of the retail store is interested to view the time series of the revenue data for the year 2011 only. He would like to view granular data by looking into revenue for each month. The CEO is interested in viewing the seasonal trends and wants to dig deeper into why these trends occur. This analysis will be helpful for the CEO to forecast for the next year.**


## Solution 


### Time Series Analysis of Revenue Data for 2011

#### Summary:
The chart illustrates the monthly revenue for the retail store during the year 2011. The data shows significant seasonal trends with notable fluctuations in revenue across different months.

#### Key Observations:
1. **Initial Decline**: The year started with a moderate revenue of around 691,365 units in January, followed by a decline to 523,632 units in February.
2. **Steady Increase**: There was a steady increase in revenue from March (717,639 units) to June (761,740 units).
3. **Mid-Year Stability**: July and August showed relatively stable revenue figures, with slight decreases to 719,221 units and 759,138 units respectively.
4. **Sharp Increase in Autumn**: A significant increase in revenue occurred from September (1,058,590 units) to October, peaking at 1,509,496 units in October.
5. **End-of-Year Drop**: The revenue saw a sharp decline in November to 1,154,979 units, followed by a further decrease in December to 638,793 units.

#### Insights:
- **Seasonal Trends**: The sharp increase in revenue during September and October may be attributed to seasonal factors such as holiday preparations or promotional events.
- **Forecasting**: These trends can help in forecasting future revenues by identifying peak months and preparing strategies to optimize sales during high-revenue periods.
- **Strategic Planning**: Understanding the reasons behind the mid-year stability and the sharp autumn increase can inform strategic decisions, such as inventory management, marketing campaigns, and staffing.

By digging deeper into the underlying causes of these trends, the CEO can better plan for the upcoming year, leveraging high-revenue periods and addressing low-revenue months with targeted strategies.

**Soultion 1 ---** https://public.tableau.com/app/profile/sumit.baviskar/viz/TataProject1_17044404080020/Solution1


![Solution1](https://github.com/Sumit-Baviskar/Tata-Company-Project/assets/153518735/3464b8c1-36a1-4e30-9350-8289db57d136)



# :paperclip: TASK 2 **(Top 10 countries by revenue)**
 
**The CMO is interested in viewing the top 10 countries which are generating the highest revenue. Additionally, the CMO is also interested in viewing the quantity sold along with the revenue generated. The CMO does not want to have the United Kingdom in this visual.** 

## Solution

### Top 10 Countries by Revenue (Excluding the United Kingdom)

#### Summary:
The bar chart displays the top 10 countries that generated the highest revenue for the retail store. It also includes the quantity of items sold in each country, providing a comprehensive view of both revenue and sales volume.

#### Key Observations:
1. **Netherlands**:
   - Revenue: 286,421 units
   - Quantity: 20,284 items

2. **EIRE (Ireland)**:
   - Revenue: 288,544 units
   - Quantity: 147,272 items

3. **Germany**:
   - Revenue: 221,705 units
   - Quantity: 27,405 items

4. **France**:
   - Revenue: 209,065 units
   - Quantity: 112,043 items

5. **Australia**:
   - Revenue: 138,417 units
   - Quantity: 62,943 items

6. **Switzerland**:
   - Revenue: 133,989 units
   - Quantity: 28,643 items

7. **Spain**:
   - Revenue: 106,238 units
   - Quantity: 27,918 items

8. **Belgium**:
   - Revenue: 94,693 units
   - Quantity: 41,546 items

9. **Sweden**:
   - Revenue: 85,009 units
   - Quantity: 39,378 items

10. **Japan**:
    - Revenue: 92,050 units
    - Quantity: 13,248 items

#### Insights:
- **High Revenue and Quantity**: EIRE and Netherlands stand out with the highest revenue and significant quantities sold, indicating strong markets.
- **Revenue vs. Quantity**: Some countries like Germany and France have a high revenue but relatively lower quantities sold, suggesting higher unit prices or premium product sales.
- **Market Potential**: Countries with high quantities but lower revenues, such as Belgium and Sweden, might offer potential for pricing strategy adjustments to increase revenue.

By focusing on these key markets and understanding the dynamics of revenue and quantity sold, the CMO can develop targeted marketing and sales strategies to maximize revenue growth while addressing market-specific needs.


**Soultion 2 ---** https://public.tableau.com/app/profile/sumit.baviskar/viz/TataProjects2/Solution2


![Solution2](https://github.com/Sumit-Baviskar/Tata-Company-Project/assets/153518735/038a629d-88b4-40bf-b865-ab0add822ac6)


 
# :paperclip: TASK 3 **(Top 10 customers by revenue)**
 
**The CMO of the online retail store wants to view the information on the top 10 customers by revenue. He is interested in a visual that shows the greatest revenue generating customer at the start and gradually declines to the lower revenue generating customers. The CMO wants to target the higher revenue generating customers and ensure that they remain satisfied with their products.** 


## Solution 
As per the bar chart that visualizes the top 10 customers by revenue for an online retail store. The chart is sorted in descending order, with the highest revenue-generating customer on the left and the lowest on the right. Here is a summary of the information:


Customer ID 14646: $279,489


Customer ID 18102: $256,438


Customer ID 17450: $187,482


Customer ID 14911: $132,573


Customer ID 12415: $123,725


Customer ID 14156: $113,384


Customer ID 17511: $88,125


Customer ID 16684: $65,892


Customer ID 13694: $62,653


Customer ID 15311: $59,419


The CMO can use this visual to identify the top revenue-generating customers and focus on strategies to ensure their satisfaction and retention. The chart clearly shows the revenue contribution of each customer, making it easier to prioritize efforts.

To ensure the satisfaction of top revenue-generating customers, the CMO can implement the following strategies:

1. **Personalized Communication and Engagement**:
   - Assign dedicated account managers.
   - Schedule regular check-ins.
   - Provide exclusive updates on new products and offers.

2. **Customized Offers and Discounts**:
   - Develop loyalty programs with exclusive discounts and rewards.
   - Create tailored promotions based on purchasing habits.

3. **Enhanced Customer Support**:
   - Offer priority support with faster response times.
   - Proactively resolve any issues with their orders.

4. **Value-Added Services**:
   - Provide product customization options.
   - Offer free upgrades and add-ons as appreciation tokens.

5. **Feedback and Improvement**:
   - Regularly solicit feedback through surveys and forms.
   - Invite top customers to participate in focus groups.

6. **Exclusive Events and Experiences**:
   - Organize VIP events and personalized experiences.
   - Offer behind-the-scenes looks at product development.

7. **Recognition and Appreciation**:
   - Feature top customers in newsletters and social media.
   - Send personalized thank you notes or gifts.

8. **Data-Driven Insights**:
   - Analyze purchase history to tailor future interactions.
   - Use predictive analytics to anticipate and meet their needs.

Implementing these strategies will help ensure top customers feel valued and satisfied, fostering loyalty and continued business growth.

**Soultion 3 ---** https://public.tableau.com/app/profile/sumit.baviskar/viz/TataProject3/Solution3


![Solution3](https://github.com/Sumit-Baviskar/Tata-Company-Project/assets/153518735/3f0ab912-4238-468d-b41a-594b099f41ce)

 
# :paperclip: TASK 4 **(Map distribution by count of customer per country)**
 
**The CEO is looking to gain insights on the demand for their products. He wants to look at all countries and see which regions have the greatest demand for their products. Once the CEO gets an idea of the regions that have high demand, he will initiate an expansion strategy which will allow the company to target these areas and generate more business from these regions. He wants to view the entire data on a single view without the need to scroll or hover over the data points to identify the demand. There is no need to show data for the United Kingdom as the CEO is more interested in viewing the countries that have expansion opportunities.** 

 
## Solution

As seen in map chart we can observe that a world map highlighting the demand for products in various countries, excluding the United Kingdom. The map uses color coding and numerical values to represent the demand in different regions. Here is a summary of the regions with the greatest demand:

Australia: 83,653


United States: 2,763


Germany: 16,787


France: 4,719


Netherlands: 5,224


Canada: 1,034


Brazil: 356


Spain: 1,197


Sweden: 1,066


Belgium: 1,032


These regions show significant demand for the company's products and present potential opportunities for expansion. The CEO can use this visual to identify high-demand areas and develop targeted expansion strategies to generate more business from these regions. The map provides a clear, single-view representation of the data, making it easy to identify key markets without the need to scroll or hover over data points. 

 
**Soultion 4 ---** https://public.tableau.com/app/profile/sumit.baviskar/viz/Solutin4/Solution4


![Solution4](https://github.com/Sumit-Baviskar/Tata-Company-Project/assets/153518735/7c9fd2f9-a61f-4997-827b-aef8a5d5eba5)


 
# :paperclip: Overall Sales and Revenue Dashboard 


**Project Dashboard Link---** https://public.tableau.com/app/profile/sumit.baviskar/viz/Tata_ProjectSubmission/Solution1


![DASHBOARD](https://github.com/Sumit-Baviskar/Tata-Company-Project/assets/153518735/fe64e482-86c7-4e53-a138-908651f2ab09)


# :paperclip: SOLUTION LINKS
------------------------------------------------------------------------------------------------------------------------------------------

**Project Dashboard Link---** https://public.tableau.com/app/profile/sumit.baviskar/viz/Tata_ProjectSubmission/Solution1


**Soultion 1 ---** https://public.tableau.com/app/profile/sumit.baviskar/viz/TataProject1_17044404080020/Solution1


**Soultion 2 ---** https://public.tableau.com/app/profile/sumit.baviskar/viz/TataProjects2/Solution2


**Soultion 3 ---** https://public.tableau.com/app/profile/sumit.baviskar/viz/TataProject3/Solution3


**Soultion 4 ---** https://public.tableau.com/app/profile/sumit.baviskar/viz/Solutin4/Solution4


# **Final Recommendations :**

To further enhance the value of this project and ensure it provides actionable insights, consider the following recommendations:

---

#### **1. Refine and Expand the Analysis**
- **Seasonal Trends Insights**:  
  Dive deeper into the reasons behind the sharp revenue fluctuations in September and October (e.g., holiday preparations or major sales events). Include external data (e.g., marketing campaigns or global events) to correlate with revenue changes.
  
- **Customer Behavior Analysis**:  
  Segment top customers by demographics or purchase history to identify patterns. Use clustering techniques to group similar customers and tailor strategies accordingly.
  
- **Product-Level Analysis**:  
  Identify the top-performing products and analyze their contribution to revenue in key markets. Highlight underperforming products to address gaps.



#### **2. Enhance the Visualizations**
- **Interactive Dashboards**:  
  Add filters for time, product categories, or customer segments to make the dashboards more user-friendly. This will allow decision-makers to customize views based on specific needs.
  
- **Heatmaps for Geographic Insights**:  
  Use heatmaps in Power BI to show demand intensity across regions, making it easier to spot high-demand areas visually.

- **KPI Indicators**:  
  Include Key Performance Indicators (KPIs) such as average revenue per customer, revenue growth rate, and customer retention rates for a quick overview of business health.



#### **3. Implement Predictive Analysis**
- **Revenue Forecasting**:  
  Use statistical models or Power BI’s forecasting feature to predict revenue for the next fiscal year, based on historical trends.
  
- **Customer Lifetime Value (CLV)**:  
  Estimate CLV for top customers to identify long-term revenue potential and allocate resources for retention.



#### **4. Automate Reporting**
- **Power BI Service**:  
  Publish the Power BI report to the Power BI Service and set up automated updates and email alerts for stakeholders.
  
- **Scheduled Refreshes**:  
  Enable automatic data refresh for real-time insights, ensuring decision-makers always have the latest information.



#### **5. Strategic Recommendations**
- **Targeted Marketing**:  
  Focus marketing campaigns on high-revenue regions and customers with high purchase frequency but lower revenue, to upsell or cross-sell products.
  
- **Global Expansion**:  
  Prioritize countries with high demand and lower market penetration (e.g., Germany, France, Netherlands) for expansion strategies.

- **Customer Retention Strategies**:  
  Implement loyalty programs and personalized offers for top customers to ensure continued satisfaction and engagement.


By integrating these recommendations, the project can evolve into a comprehensive business intelligence tool, enabling the Tata Company to make informed, data-driven decisions that maximize revenue and market opportunities.



# **Conclusion :**
 

- The **Tata Company Project: Data Visualization Empowering Business with Effective Insights** has been successfully implemented using both **Tableau** and **Power BI**. These tools allowed for effective cleaning, analysis, and visualization of the dataset, enabling key insights to drive business decisions.  

   - **Tableau Version**: Focused on interactive dashboards and insights addressing specific business questions. The visualizations provided granular details like monthly revenue, top-performing countries, and customer behavior.  
   - **Power BI Version**: Extended the same analyses with Power BI’s interactive features, enabling a comparative view of how similar insights can be achieved across platforms.  

- Both tools demonstrate the versatility and importance of data visualization in addressing critical business challenges, such as identifying revenue trends, market opportunities, and customer retention strategies.  

- By including both versions in your GitHub repository, you showcase proficiency in multiple visualization tools, highlighting adaptability and a strong understanding of data analysis and presentation. This dual approach provides a comprehensive perspective on leveraging data to empower decision-makers effectively.  

