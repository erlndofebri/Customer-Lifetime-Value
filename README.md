# Customer Lifetime values and RFM analysis
This dataset is transaction data set of two years. Consist of 540k records and 9 variable. The variables are Price, Customer ID, Stock Code, Country, Invoice, Invoice Data, Quantity, and Description. Our goals here are finding CLV each customer, segement customer by RFM and CLV values, and making recommendation

## Customer Lifetime Value Defined 
The present value of the expected sum of discounted cash flows of an individual customer. Or simply we can say, it’s the total purchases made (cash flow) over the lifetime of that customer. We will use CLV to predict how much the customer will spend in future 

## Benefits Knowing CLV
1. Determine the traits of our most valuable customers and find similar customers
2. Push the marketing channels that bring you our most valuable customers
3. Know how much we should be spending to acquire a particular type of customer
4. Use our best customers for market research and product feedback


## CLV Result

![Screen Shot 2022-08-22 at 19 56 44](https://user-images.githubusercontent.com/106853320/185926560-133016e7-df10-436f-ad7d-7d24de1e83d0.png)

The model predict in the next 2 months, these customers will make a purchase in CLV dollar monetary unit. 

## RFM Clustering
Now we cluster our customers using RFM + Tenure and CLV method. Tenure represents the age of the customer in whatever time units chosen (weekly, in the above dataset). According to Elbow Method, the best cluster number in this case is 3 cluster, so we decided to cluster our customers into 3 groups

## Clustering Summary

![Screen Shot 2022-08-22 at 18 37 35](https://user-images.githubusercontent.com/106853320/185926743-dcd6ae98-1328-4eb1-8f0c-f82878217c65.png)

1. Cluster 0
This cluster is low spender group but they bought most recent. We can say that mostly this group consist of new customer/first time buyer
2. CLuster 1
Cluster 1 represent mid-spender customers. They are existing customer who bought less frequent
3. Cluster 2
Cluster 2 is the best customers. They are most frequent and high spender buyer. Those are existing buyer and predicted will buy higher value in the next 2 months


## Reccomendation
1. In the cluster 0, mostly consist of first time buyer, in order to keep them 'alive', we can offer them discount/cashback. So, at least they will back again in certain time to buy our product. Indeed, this is need certain amount of investment, but keeping this cluster 0 is better rather than convert the new customer

2. Similar method to cluster 0, we will offer them discount treatment to make these customers in cluster 1 back to our company. Our focus is to increase buying frequency on cluster 0 and cluster 1. But in cluster 1 , since they are not first time buyer,  budget to toffer them  discount promotion is slightly cheaper than budget to treat cluster 0

3. Since cluster 2 consist of the best customers, we can focus to make them loyal.  One of most used method is using loyalty program. We can increase their spending to buy our product trough loyalty program we created. 


## Business Insights
![Screen Shot 2022-08-22 at 17 02 17](https://user-images.githubusercontent.com/106853320/185927170-081cc2e5-0f5c-470f-9e7d-4559703c9ff5.png)
![Screen Shot 2022-08-22 at 17 02 28](https://user-images.githubusercontent.com/106853320/185927181-6e3ad65b-f3da-482e-98f7-a4fe173ca111.png)
![Screen Shot 2022-08-22 at 17 02 44](https://user-images.githubusercontent.com/106853320/185927185-a4568d2f-17ed-44ca-9d22-7a4f514cf18e.png)
![Screen Shot 2022-08-22 at 17 02 57](https://user-images.githubusercontent.com/106853320/185927188-24a13f33-f6c4-4404-ae89-caed47445a4f.png)

