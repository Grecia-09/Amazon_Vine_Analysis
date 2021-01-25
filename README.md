# Amazon_Vine_Analysis

## Overview of the analysis

This project analyzes Amazon Vine program and determines if there is a bias toward favorable reviews from Vine members. For this analysis I'm using PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, I used PySpark to determine if there is any bias toward favorable reviews from Vine members in the dataset.

## Results
 1- How many Vine reviews and non-Vine reviews were there?
 
 - Vine reviews = 60
 
 <img width="367" alt="Paid count at 1 38 16 PM" src="https://user-images.githubusercontent.com/70611325/105667257-c5650b80-5e8f-11eb-8b55-e6cd4943fd82.png">
 
 - Non-vine Rewies = 14,477
 
 <img width="477" alt="Unpaid count at 1 38 43 PM" src="https://user-images.githubusercontent.com/70611325/105667259-c6963880-5e8f-11eb-85f1-dca0deb15496.png">
 
 
2- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

- Vine reviews with 5 stars

<img width="723" alt="Paid 5 stars at 1 38 28 PM" src="https://user-images.githubusercontent.com/70611325/105667772-c77b9a00-5e90-11eb-984d-04c18bf7d2ac.png">

- Non-Vine reviews with 5 stars

<img width="756" alt="Unpaid 5 stars at 1 38 53 PM" src="https://user-images.githubusercontent.com/70611325/105667773-c8143080-5e90-11eb-85dd-6844c412cbbf.png">

3- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

- Percentage of Vine reviews with 5 stars

<img width="729" alt="Paid percentage at 1 38 35 PM" src="https://user-images.githubusercontent.com/70611325/105667922-26411380-5e91-11eb-9e40-39d1019ae503.png">

- Percentage of non-Vine reviews with 5 stars

<img width="759" alt="Unpaid percentage at 1 38 59 PM" src="https://user-images.githubusercontent.com/70611325/105667923-26d9aa00-5e91-11eb-8fc3-d7cf163fa415.png">

## Summary

Based on the results of my analysis, there doesn't appear to be any sort of positivity bias because the percentages shown above are very similar at 56%.

Additionally I came up with an extra analysis to determine the percentage of verfied purchases of the non-Vine reviews. We can determine that 59.47% of the non-Vine reviewers end up making a purchase and leaving a positive review.

<img width="863" alt="Screen Shot 2021-01-24 at 10 31 52 PM" src="https://user-images.githubusercontent.com/70611325/105669363-fc3d2080-5e93-11eb-9f50-ba9ceb4f0f45.png">
