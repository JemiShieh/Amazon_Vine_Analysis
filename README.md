# Amazon Vine Analysis

## Amazon Vine Analysis Overview
Use PySpark to analyze the major appliance dataset to determine if there is any bias toward favorable reviews that were written as part of the paid Vine program, and if having a paid Vine review makes a difference in the percentage of 5-star reviews.

## Amazon Vine Analysis Results
The major appliance dataset analysis produced the following results:

* How many Vine reviews and non-Vine reviews were there?
   - Vine reviews = 35/4,992
   - Non-Vine reviews = 4,957/4,992 
* How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
   - Vine 5-star reviews = 18/35
   - non-Vine 5-star reviews = 1,963/4,957
* What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
   - Vine 5-star review percentage = 51.4%
   - non-Vine 5-star review percentage = 39.6%


![Screenshot (63)](https://user-images.githubusercontent.com/92612370/152629345-06310cb1-172b-4bdf-986a-0f0db2f2ad10.png)


## Amazon Vine Analysis Summary
The results of the major appliance dataset analysis indicate a positivity bias for reviews from members of the paid Vine program given the percentage of 5-star reviews is 51.4% versus 39.6% for paid Vine versus unpaid non-Vine reviews, respectively.

One caveat is that although the major appliance dataset was selected because of its relatively small size (there are far fewer major appliances sold and reviewed on Amazon relative to pet supplies, for example), it may not be the ideal dataset on which to perform the Vine review bias analysis as there are far fewer major appliance paid product reviews relative to, again, pet supplies, for example. 

Additional analysis could be performed to include 4-star ratings as positive, as well as an analysis of whether there were fewer negative 1-2 star ratings for Vine versus non-Vine reviews.
