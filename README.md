# amazon_vine_analysis

## Overview
### Phase 1
This analysis was completed as a test of Amazon AWS ETL process.
Data used was from Amazon S3 bucket containing public demo data of amazon reviews, in this case for kitchenwares. The data was collected from s3, transformed and stored in an RDS instance on AWS. 

### Phase 2
The goal of phase 2 was to determine user bias in reviews from paid vine users verus unpaid. 
This analysis was completed in using pandas in jupyter notebook. By performing a series of filters and some calculations the finished product was was the counts of vine users verus non-vine users, the count of 5 star reviews by each user group, and the percentage of 5 star reviews by user group. 

## Results
There appears to be no paid-user bias in the amazon review for kitchenware product category. The percentage of 5 star review for vine users is 42%, while non-vine users is 47%. In this product category there were many more non-vine users, 97.5k non vine users and only 1,205 vine users. The count of 5 star reviews given by each user category was 509 for vine users and 45,833 for non vine users. 
