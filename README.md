# Customer-Personality-Analysis :smiley:

[*here you can download the cheatsheet*](https://www.kaggle.com/imakash3011/customer-personality-analysis)

## Introduction
For the given Kaggle Dataset, I will perform the exploratory data analysis with the help of customer segmentation. Customer segmentation will be carried out with the help of K-Means alogorithm. At the end of analysis I would like to answer some questions by gaining some insights from the data.

## Technical
- Language : Python (filetype: *.ipynb*)

## Content
Need to perform clustering to summarize customer segments.

## Data Field
### People :
- **ID** — Customer's unique identifier
- **Year_Birth** — Customer's birth year.
- **Education** — Customer's education level.
- **Marital_Status** — Customer's marital status.
- **Income** — Customer's yearly household income.
- **Kidhome** — Number of children in customer's household.
- **Teenhome** — Number of teenagers in customer's household.
- **Dt_Customer** — Date of customer's enrollment with the company.
- **Recency** — Number of days since customer's last purchase.
- **Complain** — 1 if customer complained in the last 2 years, 0 otherwise.
### Products :
- **MntWines** — Amount spent on wine in last 2 years.
- **MntFruits** — Amount spent on fruits in last 2 years.
- **MntMeatProducts** — Amount spent on meat in last 2 years.
- **MntFishProducts** — Amount spent on fish in last 2 years.
- **MntSweetProducts** — Amount spent on sweets in last 2 years.
- **MntGoldProds** — Amount spent on gold in last 2 years.
### Promotion :
- **NumDealsPurchases** — Number of purchases made with a discount.
- **AcceptedCmp1** — 1 if customer accepted the offer in the 1st campaign, 0 otherwise.
- **AcceptedCmp2** — 1 if customer accepted the offer in the 2nd campaign, 0 otherwise.
- **AcceptedCmp3** — 1 if customer accepted the offer in the 3rd campaign, 0 otherwise.
- **AcceptedCmp4** — 1 if customer accepted the offer in the 4th campaign, 0 otherwise.
- **AcceptedCmp5** — 1 if customer accepted the offer in the 5th campaign, 0 otherwise.
- **Response** — 1 if customer accepted the offer in the last campaign, 0 otherwise.
### Place :
- **NumWebPurchases** — Number of purchases made through the company’s web site.
- **NumCatalogPurchases** — Number of purchases made using a catalogue.
- **NumStorePurchases** — Number of purchases made directly in stores.
- **NumWebVisitsMonth** — Number of visits to company’s web site in the last month.

## What We Got From This Project
- **What are the statistical characteristics of the customers?**
- **What are the spending habits of the customers?**
- **Are there some products which need more marketing?**
- **How the marketing can be made effective?**

## Step Inside The Project
- **Exploratory Data Analysis (EDA)**
- **Machine Learning Model (K-Means)**
- **Cluster Interpretation**
- **Customer Distribution**
- **Relationship: Income VS Spendings**
- **Spending Habits By Clusters**
- **Purchasing Habits By Clusters**
- **Promotions Acceptance By Clusters**

## Conclusion
- It seems very clear that there is no big difference between male and female customers, so a gender-based audience should not be chosen.
- In addition, it seems that the audience between the ages of 20-40 spend more in this store compared to people in other age groups, making special campaigns for the audience between the ages of 20-40 can increase the profit of the supermarket.
- This is not the optimal strategy, but it could be an alternative. Since the average spending scores of middle-income (40k-70k dollars) customers in this store are also at a medium level, it is difficult to increase their spending to higher levels because their income is not conducive to this, but by making campaigns to increase the number of these customers, the store can increase its profit by acquiring more middle-income customers.
- I think the best strategy would be to target high-income customers. The reason is that some of the high-income customers spend high, while a significant portion of these customers spend low, there may be some things that low-spenders are not satisfied. Improvements to be made in service and quality can increase the spending of high-income customers who come to the store, but do not.
- The distribution of the data was generally good, but the standard deviations were a little high and there was no significant positive correlation between the data, only a negative correlation between age and spending score that could be important, showing us that older people who choose this supermarket spend less money than people in other age groups.

## Answering Question
**What are the statistical characteristics of the customers?**<br>
The company's customers are mostly married. There are more Middle Aged Adults, aged between 40 and 60 and most of them like to have one child. Most of the customers hold bachelor degree and their earnings are mostly between 25,000 and 85,000.<br>

What are the spending habits of the customers?

Customers have spent more on wine and meat products. Those without children have spent more than those having children. Singles are spending more than the one's with the partners. Middle aged adults have spent more than the other age groups. Store shopping is the preferred channel for purchasing among the customers. Web and Catalog purchasing also have potential.

Are there some products which need more marketing?

Sweets and Fruits need some effective marketing. Company needs to run promotions for these products in order to increase the revenue from these products. Baskets of the least selling products combined with the most selling products can be effective.

How the marketing can be made effective?

As a marketing recommendation give coupons to the old and high spending customers. Market the cheap and on-offer products to the low income and low spending customers. Web purchasing has some potential. To unlock this give special discounts to the customers who sign up on company's website.

## [Click Here  for Visualize and Analyze](https://arienugroho050396.github.io/project7.html) :thumbsup: :thumbsup: :thumbsup:
   
  
 
 
