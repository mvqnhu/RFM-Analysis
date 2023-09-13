# RFM-Analyst
🚀This project aims to analysis segment of customer bases on RFM Model, so that Marketing team can deploy each marketing program suitable for each customer group.
## I.Introduction
### 1.What is RFM?
RFM is a marketing analysis technique that stands for Recency, Frequency, and Monetary Value.
- Recency: measures how recently a customer has made a purchase.
- Frequency: measures how often a customer has made purchases.
- Monetary Value: measures the total amount of money a customer has spent on purchases.
RFM is used to identify and categorize customers based on their purchasing behavior and how recently and frequently they have made purchases, as well as the monetary value of those purchases.
### 2.How?
In RFM analysis, customers are scored based on three factors (Recency - how recently, Frequency - how often, Monetary - how much), then labeled based on the combination of RFM scores
## II.Challenges
1. The Marketing Department needs to classify the segments of each customer to deploy each marketing program suitable for each customer group.
2. The Marketing Director also proposed a plan to use the RFM model in Python to segment customers, and then launch marketing campaigns to thank customers for supporting the company over the past time. As well as exploit potential customers to become loyal customers.
3. Suggestions to the Marketing and Sales team with the company's retail model, which of the three indicators R, F, and M should be most interested in?
## III.Visualizations
### Get insights by barplot

<img width="504" alt="image" src="https://github.com/mvqnhu/RFM-Analyst/assets/138433845/f95fc2ba-6564-4039-944b-f4a83832f5b2">

 ### Insight:
- Segmentations ordered recently : Champions (28,5 days), Promising (35 days), New customer (41.5 days)
- Segmentations have not ordered long time: Cannot Lose Them (496,5 days), Lost customers (558 days)

<img width="504" alt="image" src="https://github.com/mvqnhu/RFM-Analyst/assets/138433845/235ea120-c4c0-4f1f-9ac3-e8e73d860567">

 ### Insight:
- The segment with the highest purchasing frequency (Champions) is 3.3 times more frequent than the segment with the lowest purchasing frequency (Lost Customers).
- Segments with high purchase frequency: Champions (10 times), Loyal (8 times), At Risk & Potential Loyalist (7 times), Need Attention (6.5 times)
- Note that customer segments need a New Customers care policy (3.4 times)

<img width="475" alt="image" src="https://github.com/mvqnhu/RFM-Analyst/assets/138433845/bece6962-b9ae-497d-a5cc-042351b99eac">

 ### Insight:
- The Champions segment accounts for the highest average revenue (5,382 units)
- One particular thing is that the At Risk segment has a fairly high revenue level of more than 4,000 units, while the Potential Loyalist segment has a relatively modest revenue level of approximately 1,690 units.

### Piechart

<img width="495" alt="image" src="https://github.com/mvqnhu/RFM-Analyst/assets/138433845/2499d964-37c7-4388-99c0-3f8703142321">

### Insight:
- Revenue mainly comes from the following segments: At Risk(18.2%), Champions(18.1%), Loyal(12.8%), Need Attention(12.3%), Promises(10.6%)
-- Attention should be paid to the At Risk segment, this group brings high revenue

### Scatterplot

<img width="445" alt="image" src="https://github.com/mvqnhu/RFM-Analyst/assets/138433845/03121e46-d3f1-4e1d-b58d-bc808b1f7948">

### Insight:
- Customers who have purchased recently generate more revenue than customers who have purchased in the past.
- Customers who made a purchase in the recent past are more likely to return than customers who made a purchase a long time ago because most of those customers will be Lost customers.
- Thus, higher revenue will be associated with the most recent customers: Champions, Promises, New Customers, Potential Loyalist, Need Attention, Loyal segments (Based on Recency Chart)

## IV.RECOMMENDATION
### From the basic analysis results above, we can draw the following conclusions:
- Prioritize the design and implementation of programs for two customer segments, Champions and Loyal, with the expectation of high profits, low risk, and effective access. These two groups bought recently, had high purchase frequency, accounted for a large % of revenue, and the average order value (AVG Monetary) was also high.
- Have a policy or build a more effective and flexible product system targeting the Potential Loyalist customer segment to exploit a large number of customers considered potential customers to become loyal customers bringing long-term profits. long for the company. Because this group accounts for 14.28% of the total number of customers, the purchasing frequency is high.
- Pay special attention to the At Risk segment, there needs to be an effective solution for this segment because At Risk accounts for TOP 1 revenue of 18.2%, the purchasing frequency is quite large, the order value is high, and is accounting for the largest number of customers. large number of customers (12.1%) -> Need to find out the reason why this group of customers do not return to buy products for many days and attract them back with appropriate solutions.
- Next, we need to pay attention to the two segments Need Attention and Promises because they account for high revenue of 12.3% and 10.6% respectively. It is necessary to build a strategy for these two segments because they have great potential to become loyal customers. Furthermore, the Need Attention segment has a large number of customers, high purchasing frequency, high revenue and order value.

### Which indicator in R,F,M should be interested most?
- Champions, Loyal: 3 relatively high R, F, M indexes
- Potential Loyalist: still limited to R and M index
- At Risk: low R index, haven't bought for a long time, but F and M are relatively high, need to focus on R index
- Need Attention: high F and M index, but low R, need to focus on R index
SHOULD BE MOST INTERESTED IN THE R INDEX
