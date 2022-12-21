# Amazon_Vine_Analysis

### Overview of the analysis: Explain the purpose of this analysis.

Jennifer on the SellBy project was so successful, you’ve been tasked with another, larger project: analyzing Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

In this project, you’ll have access to approximately 50 datasets. Each one contains reviews of a specific product, from clothing apparel to wireless products. You’ll need to pick one of these datasets and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, you’ll use PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset. Then, you’ll write a summary of the analysis for Jennifer to submit to the SellBy stakeholders.

### Results: 

- How many Vine reviews and non-Vine reviews were there? 
- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?


To answer the above questions the following screenshots are added.
![Aggregate count of paid and unpaid](https://user-images.githubusercontent.com/111100908/208957585-f831a517-d830-4be7-86ee-fcc66ec82acd.png)
![Paid analysis output](https://user-images.githubusercontent.com/111100908/208956895-48c6f222-782a-4f97-813d-40eeb9dcecc5.png)
![Unpaid Analysis output](https://user-images.githubusercontent.com/111100908/208956900-69eec8fa-61bd-46e5-95ff-8d7eadcb9e17.png)


### Summary: In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. 
After reviewing the results comparing the Vine vs. Non-Vine reviews, there is not a bias for reviews in the Vine program. As seen in the images above, 42% of Vine members reviews were 5-star and 47% of Non-Vine reviews were 5-star. The number of Vine reviews total in comparison to Non-Vine reviews is significantly less though.

