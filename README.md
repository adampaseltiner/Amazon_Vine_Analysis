# Amazon_Vine_Analysis

Resources: AWS, PostgreSQL, PgAdmin, PySpark, Google Colab

## Analysis Overview

The purpose of this project was to analyze statistics from Amazon's Vine program, where reviewers are given monetary compensation for their written reviews of products. Specifically, we were curious to discover if Vine reviewers returned biased or favorable reviews compared to unpaid reviewers not in the Vine program.

## Results
Below are the results from the analysis on Vine reviews for the musical instrument dataset: 

![Vine_Results](https://user-images.githubusercontent.com/82347825/128654463-20ac508a-1de6-4176-a640-e260ff77ec12.png)

- There were a total of 60 Vine reviews and 14477 non-Vine reviews.
- 34 of the Vine reviews were 5 stars, while 8212 non-Vine reviews were 5 stars.
- 56.67% of Vine reviews were 5 stars, while 56.72% of non-Vine reviews were 5 stars.

## Summary
Based on the above results we can see that there is clearly not a bias for reviews coming from the Vine program, since the percentage of 5 star reviews (56.67%) is essentially identical to those from the non-Vine reviewers (56.72%).

Several further analyses could be conducted to investigate whether our conclusion is accurate:
- We could perform the same analysis on reviews of different star ratings (i.e. 4 stars, 3 stars) to see if there is any significant variance between Vine and non-Vine reviewers.
- We also might run the analysis on more datasets (e.g. music, jewelry, electronics) to see if the same results hold true for Vine reviews vs. non-Vine reviews in those categories.
