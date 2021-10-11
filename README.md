# Amazon_Vine_Analysis

## Overview of the analysis 
Access one of fifty datasets of product reviews, in this case: video games reviews from Amazon Vine program; using PySpark to perform ETL by extracting and transform the data on Google Colaboratory, and then load the transformed data into Amazon RDS instance once connected to Postgres. Whether there is any bias toward favorable reviews from Vine members in the video game review dataset was then determined using PySpark.

- PySpark, ETL, Amazon RDS, Postgres, pgadmin

## Results

- How many Vine reviews and non-Vine reviews were there?

There were a total of 94 Vine reviews and 40471 non-Vine reviews.


- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

48 Vine reviews that are 5 stars. On the other hand, 15663 non-Vine reviews that are 5 stars. 

- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

51.1 percent of Vine reviews were 5 stars while only 38.7 percent of non-Vine reviews were 5 stars. 

## Summary

There could be bias among this 'star ratings' system since there are more five-star reviews amongst vine reviews than non-vine reviews. However, the number of non-Vine reviews is significantly more than Vine reviews. 
