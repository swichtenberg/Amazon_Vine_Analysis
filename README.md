# Amazon Vine Analysis 

## Background
The purpose of the project was to analyze both paid and unpaid Amazon reviews to identify possible bias. Data for the 'Tools' category was accessed from a list of datasets made publicly available by Amazon. PySpark was used to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. The data was then analyzed for bias with PySpark. Key results included the number of total paid and unpaid reviews, the number of paid and unpaid 5-star reviews, and the percentage of 5-star reviews for both paid and unpaid reviews.

## Results
### Total Review Counts
- Paid (i.e. Vine) Review Count: 268
- Unpaid Review Count: 29,452
### 5-Star Review Counts
- Paid (i.e. Vine) 5-Star Review Count: 149
- Unpaid 5-Star Review Count: 13,668
### Percentage of 5-Star Reviews
- Paid (i.e. Vine) 5-Star Review Percentage: 55.6%
- Unpaid 5-Star Review Percentage: 46.4%

#### Below is the script written to obtain the results for Paid (i.e. Vine) Reviews above.
![exampleCode](https://user-images.githubusercontent.com/96216947/163184566-693ec89b-460c-4757-9ffb-10b7a91477ce.JPG)

## Summary
