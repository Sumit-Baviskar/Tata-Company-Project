# :chart_with_upwards_trend:   Tata-Company-Project (Data Visualisation: Empowering Business with Effective Insights)  :chart_with_upwards_trend:
**Data Visualisation: Empowering Business with Effective Insights (Micro internship)**

# Tata Micro Internship  Online Retail Data Mining 

# Dataset --- Online Retail 

Dr Daqing Chen, Director: Public Analytics group. chend '@' lsbu.ac.uk, School of Engineering, London South Bank University, London SE1 0AA, UK. 


:link:     **Data set Link---https://www.kaggle.com/datasets/tunguz/online-retail**

# :chart_with_upwards_trend:  **Tools- Tableau**  :chart_with_upwards_trend:
 
So before performing tasks , we have to clean the data as per requirement. As the “data is new oil,but we cannot use it in raw form “ so we have to clean before use .So company’s CMO and CEO can take data driven decision for company.  

There was 2 requirement--
Create a check that the quantity should not be below 1 unit 
Create a check that the Unit price should not be below $0 

For which I have used tableau filter for this task moving to the task. Now as the data is clean we can start our data analysis part in this project 


 
# :paperclip: TASK 1 **(Monthly revenue of 2011)**
The CEO of the retail store is interested to view the time series of the revenue data for the year 2011 only. He would like to view granular data by looking into revenue for each month. The CEO is interested in viewing the seasonal trends and wants to dig deeper into why these trends occur. This analysis will be helpful for the CEO to forecast for the next year. 


**Solution-—** 


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
 
The CMO is interested in viewing the top 10 countries which are generating the highest revenue. Additionally, the CMO is also interested in viewing the quantity sold along with the revenue generated. The CMO does not want to have the United Kingdom in this visual. 

**Solution-—** 

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
 
The CMO of the online retail store wants to view the information on the top 10 customers by revenue. He is interested in a visual that shows the greatest revenue generating customer at the start and gradually declines to the lower revenue generating customers. The CMO wants to target the higher revenue generating customers and ensure that they remain satisfied with their products. 


**Solution-—** Frist of all , data has to been clean for NULL customer numbers, by observing the chart we can seen the top 10 customer are contributing to revenue to a extent we can target this customer so there can repurchase the goods or we can provide offer to this customer at the lower revenue months for more revenue. 


**Soultion 3 ---** https://public.tableau.com/app/profile/sumit.baviskar/viz/TataProject3/Solution3


![Solution3](https://github.com/Sumit-Baviskar/Tata-Company-Project/assets/153518735/3f0ab912-4238-468d-b41a-594b099f41ce)

 
# :paperclip: TASK 4 **(Map distribution by count of customer per country)**
 
The CEO is looking to gain insights on the demand for their products. He wants to look at all countries and see which regions have the greatest demand for their products. Once the CEO gets an idea of the regions that have high demand, he will initiate an expansion strategy which will allow the company to target these areas and generate more business from these regions. He wants to view the entire data on a single view without the need to scroll or hover over the data points to identify the demand. There is no need to show data for the United Kingdom as the CEO is more interested in viewing the countries that have expansion opportunities. 

 
**Solution--** As seen in map chart we can observe that , Europe has been the major customer of product of our company like Netherlands, Finland ,Sweden etc followed by Austrialia. But we can also Focus on North America had the product sold is less in this region . we have to form different plan for both regionfor more revenue opportunity

 
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

------------------------------------------------------------------------------------------------------------------------------------------
