# Amazon_Vine_Analysis
# Overview of the analysis: 

The purpose of this project is to analyze amazon review written by members of the paid Amazon Vine program. It is a service that allows manufacturers and publishers to receive reviews for their product. Companies like Sellby pay a small fee to amazon and provide products to amazon vine members, who are then required to publish a review. 
In this project, we have picked 1 dataset out of 50 datasets. Each one contains reviews of a specific product, from clothing apparel to wireless products. This data is particularly about wireless products. We will be using one of these datasets and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and the load the transformed data into pgAdmin. We will be checking for favorable reviews from Vine members in the dataset. 

# Results:
Vine Review Analysis (SQL): 

![Amazon_Vine_Analysis](https://github.com/Zainak94/Amazon_Vine_Analysis/blob/main/Resources/customer_table.PNG)

![Amazon_Vine_Analysis](https://github.com/Zainak94/Amazon_Vine_Analysis/blob/main/Resources/products_table.PNG)

![Amazon_Vine_Analysis](https://github.com/Zainak94/Amazon_Vine_Analysis/blob/main/Resources/review_id_table.PNG)

![Amazon_Vine_Analysis](https://github.com/Zainak94/Amazon_Vine_Analysis/blob/main/Resources/vine_table.PNG)

## Total count of Vine Reviews vs Non-Vine Reviews: 

## Vine Reviews: 

![Amazon_Vine_Analysis](https://github.com/Zainak94/Amazon_Vine_Analysis/blob/main/Resources/y_vines.PNG)

## Non-Vine Reviews: 

![Amazon_Vine_Analysis](https://github.com/Zainak94/Amazon_Vine_Analysis/blob/main/Resources/n_vines.PNG)

![Amazon_Vine_Analysis](https://github.com/Zainak94/Amazon_Vine_Analysis/blob/main/Resources/total_count.PNG)

•	There are 618 vine reviews and 71,969 were non-vine reviews. It shows that more reviews were by non-vine. 

•	There are 223 Vine reviews that were 5 stars and 31,390 were non-vine reviews. 223 people are paid members of amazon vine program. 

•	There were 36.08% of the vine reviews were 5 stars and the 43.61% were non-vine reviews that were 5 stars. 

# Summary: 

There is a positivity bias for reviews of the products in this program. There are Vine members reviews that would create a bias on these products. There are huge number of wireless products; these reviews help other unpaid non-vine to purchase these products. In comparison, these vine members are required to write the reviews, but the unpaid non-vine reviews are more. The reason these paid members are required to write the products because they are receiving the products for free. To gather more Vine reviews in this program, we could filter the reviews by 4 stars as well, it might provide us more visibility of the vine reviews or we can pick other small product category where it shows a clear snapshot. 
