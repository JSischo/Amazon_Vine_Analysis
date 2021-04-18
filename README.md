# Amazon_Vine_Analysis

## Overview of the Analysis
> The purpose of this project was to analyze Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

> In this project, I analyzed the category Pet Products for the Amazon database. I used PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and loaded the transformed data into pgAdmin. Next, I utilized PySpark to determine if there is any bias toward favorable reviews from Vine members in the dataset.

> My hypothesis is that the reviews from the Vine (paid) program will have higher ratings than those from the non-Vine (upaid) reviews. 

## Results
### Vine Results

![](Resources/vine_star_count.png)![](Resources/vine_star_summary.png)
* Analysis of the results for the Vine sub-set of reviews reveals:
  * n=170 reviews.
  * There were 65 **"5 star"** reviews.
  * Of all the reviews, 38.24% were **"5 Star"**.

![](Resources/nonvine_star_count.png)![](Resources/nonvine_star_summary.png)
* Analysis of the results for the Vine sub-set of reviews reveals:
  * n=37840 reviews.
  * There were 20,612 **"5 star"** reviews.
  * Of all the reviews, 54.47% were **"5 Star"**.
  
## Summary
