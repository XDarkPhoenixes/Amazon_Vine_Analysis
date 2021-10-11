# Amazon_Vine_Analysis

## Overview of the analysis 
Access one of fifty datasets of product reviews, in this case: video games reviews from Amazon Vine program; using PySpark to perform ETL by extracting and transform the data on Google Colaboratory, and then load the transformed data into Amazon RDS instance once connected to Postgres. Whether there is any bias toward favorable reviews from Vine members in the video game review dataset was then determined using PySpark.

- PySpark, ETL, Amazon RDS, Postgres, pgadmin

## Results

How many Vine reviews and non-Vine reviews were there?

- There were a total of 94 Vine reviews and 40471 non-Vine reviews.

![VineYT](https://user-images.githubusercontent.com/84931545/136842585-cd6b33be-b72b-48b0-8abb-11c36ca058b4.PNG)
![VineNT](https://user-images.githubusercontent.com/84931545/136842551-236b9c47-1286-4c5f-a2c6-bfb07fb3dd14.PNG)


How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

- 48 Vine reviews that are 5 stars. On the other hand, 15663 non-Vine reviews that are 5 stars. 
![Vine5](https://user-images.githubusercontent.com/84931545/136842629-91509c30-c1c4-4282-9c7e-9b6e3e248b78.PNG)
![VineN5](https://user-images.githubusercontent.com/84931545/136842646-4462463f-5a3e-43e7-8891-33c5ee700c6d.PNG)


What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

- 51.1 percent of Vine reviews were 5 stars while only 38.7 percent of non-Vine reviews were 5 stars. 
![p5p](https://user-images.githubusercontent.com/84931545/136842736-0c15ba79-cd7c-4d84-b4a9-b698075269ad.PNG)
![p5up](https://user-images.githubusercontent.com/84931545/136842764-a5577faa-026c-48eb-8561-0f2a5003dcc5.PNG)


## Summary

There could be bias among this 'star ratings' system since there are more five-star reviews amongst vine reviews than non-vine reviews. However, the number of non-Vine reviews is significantly more than Vine reviews. 
