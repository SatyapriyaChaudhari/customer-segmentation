### Project Overview

 Aim is to check out the customers behavior based on the CutomerId,InvoiceNo,Quantity,UnitPriceand Countryetc. This is an unsupervised leaning project.


### Learnings from the project

 Concepts utilised

- [ ] Data preprocessing
- [ ] Data Visualisation
- [ ] k means clustering


### Approach taken to solve the problem

 Steps involved:
1. Subsetting the data. We will be working only on data from United Kingdom.
2. Create customer-level dataset - The original dataset was organized long, with invoices nested within customer. Our aim is to create a customer-level dataset and add recency, frequency, and monetary value data to it.first calculate the recency. The recency variable refers to the number of days that have elapsed since the customer last purchased something (so, smaller numbers indicate more recent activity on the customer’s account).
3. Frequency refers to the number of invoices with purchases during the year. Now let's calculate the frequency of purchase.
4. Calculate the Monetary - Some customers have negative monetary values. These customers probably returned something during the year that they had purchased before the year started.
5. Standardizing the input variables by taking the log of the features.
6. Use the elbow method to find the optimum number of clusters.
7. Use Kmeans to cluster data.


