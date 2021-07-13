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

## Load the DataFrames into pgAdmin - Successful Connections
![Postgres_pgAdmin_Tables](https://user-images.githubusercontent.com/80075982/125423481-f83506ee-831d-4eb1-8665-b94640dc0f18.png)


![Postgres_pgAdmin_Customers_Table](https://user-images.githubusercontent.com/80075982/125423492-8e202f1e-eaad-4a89-bda8-e29f72f4bd67.png)
![Postgres_pgAdmin_Products_Table](https://user-images.githubusercontent.com/80075982/125423501-6962f29b-8e19-4f52-9899-eda5d1087886.png)
![Postgres_pgAdmin_review_id__Table](https://user-images.githubusercontent.com/80075982/125423509-498a3997-9747-44c5-b2f1-ce3bd3b233b8.png)
![Postgres_pgAdmin_Vine_Table](https://user-images.githubusercontent.com/80075982/125423521-ea1ae701-d698-40ca-923e-43704c6ba875.png)

