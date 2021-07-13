# Amazon_Vine_Analysis
Module_16


## Resources
Amazon Web Services / Google Colab / Postgres PGAdmin / PySpark 


## Project Overview & Challenge
The purpose of this module is to select a dataset from list provided to use PySpark to perform the ETL process to extract the datasets, transform the data, connect to AWS RDS Instance, and load the transformed data into pgAdmin. In addition need to determine if there is any bias toward favorable reviews from Vine members in the dataset selected using either PySpark, Pandas or SQL for analysis.

## Results:

### How many Vine reviews and non-Vine reviews were there?
- A total of 334 vine member reviews
- A total of 61,614 non-vine member reviews

     ![Vine-NonVine_member_reviews](https://user-images.githubusercontent.com/80075982/125246087-2cdc0f80-e2a6-11eb-8226-ecf4676bb4e9.png)


### How many Vine reviews were five stars? How many non-Vine reviews were five stars?
- A total of 139 vine member reviews that were five stars
- A tota of 32,665 non-vine member reviews that were five stars.

     ![Vine-NonVine_5S_member_reviews](https://user-images.githubusercontent.com/80075982/125246081-2baae280-e2a6-11eb-8f3d-44d9f1663372.png)


### What percentage of Vine reviews were five stars? What percentage of non-vine reviews were five stars?
- 42% vine member reviews that were five stars
- 53% non-vine member reviews that were five stars

     ![Vine-NonVine_5S_%Member_reviews](https://user-images.githubusercontent.com/80075982/125246071-29e11f00-e2a6-11eb-9558-82defe2f718a.png)


## Summary

The percentage of reviews that were 5 stars from both Amazon Vine members and not Amazon Vine members shows a slight bias for the US Sports datasets. 

        42% of reviews by Amazon Vine members were 5 stars
        53% of reviews not by Amazon Vine members were 5 stars

A similar analysis could be conducted to compare the one-star or low reviews from both Vine and non-Vine members to further support this conclusion.
