Task 1: Data Modeling & Cleaning
● Load and transform datasets in Power Query
● Handle duplicates, missing values, and ensure correct data types 
● Create calculated columns:
○ Membership_Duration = Today – Membership_Since
○ Extract Transaction Year, Transaction_Month
● Create a basic Data Model view
○ One-to-Many: Customer_Demographics → Transactions, Loyalty_Program,
Churn_Labelled_Customers
○ Many-to-One: Transactions → Store_Locations
 
Major Approaches:
1.	Power Query.
2.	Calculated Column (for Membership_Duration column).
3.	Model view (to create relations).
4.	Changed data types using power query.
5.	Handled null and duplicate values using power query.
6.	
 <img width="1016" height="535" alt="image" src="https://github.com/user-attachments/assets/f548bc7c-e35f-4b27-b0c2-f13bc88a042b" />

Task 2: Churn & Retention Metrics
Create Churn Rate KPI = (Churned Customers / Total Customers) * 100
= 24.5%
Visualize churn rate by:
○ Region
○ Income Group
○ Channel (Store/Online)
○ Loyalty Tier
 <img width="1103" height="511" alt="image" src="https://github.com/user-attachments/assets/1d38872f-c34c-4bc4-8f67-2979603fd7f8" />
<img width="975" height="441" alt="image" src="https://github.com/user-attachments/assets/4c46f0d9-6afe-4362-aad5-e8b97983cf15" />

Funnel Chart: Total Customers → Repeat Customers → Churned

Major approaches:
1.	Measure for Churn Rate KPI.
2.	Preferred visuals.
Key Findings:
1.	Region with highest churn rate: North.
2.	Income level with highest churn rate: Medium.
3.	Loyalty tier with highest churn rate: Elite.
4.	Channel with highest churn rate: Store.
5.	24.5% is total churn rate KPI.
6.	78.5% customers are repeated customers (Product purchased > 3 times).

Task 3: Repeat Purchase Analysis (10 Marks)
● Segment customers:
○ Low-Tier: 0–3 purchases
○ Mid-Tier: 4–8 purchases
○ High-Tier: 9+ purchases
<img width="975" height="661" alt="image" src="https://github.com/user-attachments/assets/6b1a9b8a-a0ec-42f0-88e1-683fede3403a" />

Compare avg. purchase frequency by Region, Age Group, Loyalty Tier:
 
Identify most purchased product categories by loyal customers:
 
Major Approaches:
1.	Group By (For segment customers).
2.	Conditional column (For categorizing customers).
3.	Preferred visuals. 

Key Finding:
1.	North region has highest Average purchasing frequency. That shows customers are loyal but unhappy.
2.	Loyalty tier: elite purchased the highest Average of products.
3.	Mid aged (30-45) customers purchased highest average of product.
4.	Product apparel is most purchased item by people of all loyalty tiers.
Task 4: Promotion & Loyalty Impact 

Calculate % of transactions with promotion applied.
= 38.49%
● Compare average purchase amount with vs. without promotions.
● Analyze churn rate across loyalty tiers.
● Visualize Points Earned vs. Redeemed by Tier (Clustered Column Chart).
 

Major Approaches:
1.	Measure (for % for total transaction).
2.	Preferred visuals.

Key Findings:
1.	38.49 % of transactions with promotion applied.
2.	Loyalty tier elite has highest churn flag followed by premium.
3.	Average amount spends by promotion applied: 397.70.
4.	Average of amount spends without promotion applied: 411.49.
5.	Basic loyalty tier peoples have highest loyalty points with highest points redemption.



Give recommendations to improve redemption & retention:
1.	Give some extra discount when purchasing through loyalty points.
2.	Add some limited time offer for loyalty point redemption
3.	User with promotion applied has lower average amount spend. So, add value added bundles with promotion applied.
4.	On purchasing high amount of products, add some offers so we can get High average amount spend.
5.	Our major churn customers are from stores we should improve user experience my reducing queue time, improving staff behavior and product availability.
6.	Make bundles with offers so we can add least purchased item to that bundle with most demanding items.
7.	Elite customers are highest churning which is red flag to retain them we should add birthday or anniversary offer for them, dedicated support team and early access to campaigns. 
8.	By purchasing product for 4th time and 9th time give special offer as they moving to next segment.
9.	 north regions has most churned from online platform. hence, make better User Interface, give timely delivery and focus on relevant advertisement.  

Task 5: Store & Channel Performance vs Retention
● Merge store data with transactions

 

● Visualize:
○ Avg. transaction amount by Store Type
○ Churn rate by store type
○ Correlation between store opening year & retention
 

Major approaches:
1.	Merge query (for merging store data with transaction.
2.	Preferred chart.
Key Findings:
1.	Store type: superstore has highest average amount spend.
2.	Major churned customers are from preferred channel: Store.
3.	Store Opening year 2016, 2018 and 2021 has least number of transactions means least retention or repeated customers
4.	Opening year 2012 followed by 2017 and 2009 has highest number of transactions which means highest repeated or retained customers.
5.	Older stores have better retention and repeated customers that show the drop trend line.
6.	Least average of amount is spend by store type: Online.


Task 6: Customer Lifetime Value (CLV) Analysis.
● CLV = Total Amount Spent / Membership Duration (Years)
● Segment customers into Low, High CLV
○ Above Average CLV as High
○ Below Average CLV value- Low
 
Visualize:
○ CLV vs Days Since Last Purchase
○ CLV by Loyalty Tier & Region
 
Major approaches:
1.	Calculated field (For CLV)
2.	ALL (For Average CLV)
3.	Conditional column (For categorizing High/Low)
4.	Preferred Chart.

Key Findings:
1.	Even the peoples with high CLV haven’t purchased from very long time. (Low CLV doesn’t mean Disloyal or Churned).
2.	Peoples with low CLV also purchased items before some days. (High CLV doesn’t mean loyalty)
3.	 People in loyalty tier basic has highest CLV in North and South region.
4.	People on loyalty tier premium has highest CLV in Central and east region.
5.	Even though elite is upper loyalty level still it has least CLV in central, east and west region.
6.	Average CLV is 617.50.





Task 7: Final Dashboard & Executive Summary
Page 1: KPIs (Churn, CLV, Repeat Rate)

 

Key Findings:
1.	Has 40% churn rate from stores in north and majorly are from medium income group (45.5%) and High-income group in online Channel (50%).
2.	Repeat Customer Rate: 78.5%, showing strong repeat engagement and north region got 90% repeat rate from store and 80% online.
3.	Highest churned customer are from elite tier (29%)
4.	Average Customer Lifetime Value (CLV): 617.50, highlighting healthy long-term customer revenue. High income group has highest average CLV.
5.	West Region has least average CLV and least repeated customer.
Page 2: Loyalty & Promotion Impact

 

Key Findings:
1.	Mid- Tier are customers are highest.
2.	In Central, East and west region elite tier customers has least CLV.
3.	Elite loyalty tier has least loyalty points earned and redeemed
4.	In south least people purchased by promotion applied and in West it is highest (42.5%).
5.	Premium Loyalty tier has highest % of people with Promotion Applied and average amount using promotion is also more the without promotion applied.
Page 3: Store/Channel Insights

 

Key Findings:
1.	Superstore has highest average of amount spend by customers.
2.	Stored opened in year 2016, 2018 and 2021 has least number of transactions and repeated customers. While older stores show better stability.
3.	Online stores have high Average CLV.
4.	Online stores have least average transaction amount by customers.
5.	Store channels has higher churn rate and lower repeat rate compared to online stores.
Page 4: Segmentation (Churned, Repeat, High-Value)

   

Key Findings:
1.	Overall 61 customers are at risk who haven’t purchased since 800 days and are active customers.
2.	In north region we have 12.5% of high value customers.
3.	In north we have highest peoples with high CLV and are inactive from long time followed by east.
4.	Elite tier has highest at-risk customers.
5.	Medium income level customers are highest at-risk customers.





Provide Top 3 Recommendations for Target:
1.	 Which customers to prioritize for retention?

I.	Peoples with High CLV and longtime inactive.
Actions can be taken.
a.	Come back discounts.
b.	Win back campaigns.
II.	North region has highest churn rate KPI (35%) which is not good and churn rate is really high.
Actions can be taken
a.	Traditional Campaigns.
b.	Festival offer.
III.	Elite and Premium Loyalty tier. 
Actions can be taken:
a.	Early Access to campaigns.
b.	Dedicated support team
c.	Birthday Offers
IV.	Medium Income level customers.
Actions can be taken:
a.	Price sensitive promotions
b.	Value added bundles.
c.	
2.	Which channels are underperforming?

I.	Store Channels are underperforming. Higher churn rate and low repeat rate.
Actions can be taken:
a.	Reduced queue time.
b.	Product availability.
c.	Better Trial rooms.
d.	Store cleaning and product management.
e.	Improved staff behavior.
II.	Online customers- North region.
Actions can be taken:
a.	Improved delivery time.
b.	Better user interface
c.	Making website and Apps more responsive
III.	Stores Opened in year 2016, 2018 and 2021
Actions can be taken:
a.	Store Awareness campaign.
b.	Localized Advertisement
c.	Cultural products.

3.	How to strengthen loyalty engagement?

I.	Better loyalty points redemption.
II.	Loyalty Point offers.
III.	Milestone based rewards (on 4th purchase or 9th purchase or any other).
IV.	Making bundles with offers (Least purchased items with High demand products). 
V.	Cultural campaigns.
VI.	Early access and dedicated support elite and premium loyalty tier.



Video Link:
Loom Link
Drive Link


