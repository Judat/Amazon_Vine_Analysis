# Amazon_Vine_Analysis

## Overview
The purpose of the project is to analyze Amazon reviews written by members of the paid Amazon Vine program. In order to complete this analysis, I used a subset of data for Software subcategory of Amazon. I then performed an ETL on this data by using AWS, Google Colaboratory, PostgreSQL, and PySpark for Challenge 1. 

For Challenge 2 and 3 I used the codes to review if the  the vine reviews had any positivity bias for reviews in the Vine Program.

## Questions asked 

* How many Vine reviews and non-Vine reviews were there?
Total reviews ( votes with total count more than 20 ) = 20,216
Vine Reviews (helpful Vine reviews) = 248
Non Vine Reviews ( helpyl vine reviews) 17514
* How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
5 Star Vine Reviews (paid) = 248
5 Star non-vine Review (unpaid) = 17514
* What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
Percentage of Vine reviews 5 stars = 41.12
Percentage of non-Vine reviews were 5 stars = 29.42

![Vine reviews](https://user-images.githubusercontent.com/93050682/157376409-0c814b70-b00e-460f-9eca-577fba78d210.PNG)

## Summary

From the details we can deduce that there is a bias in voting on paid reviews. The 5 stars for paid reviews is almost double than that of un piad reviews. 
