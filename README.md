# *Amazon Vine Analysis Challenge*

## Overview 

#### We were tasked with analyzing Amazon pet product reviews. To do this, we extracted the data into a data frame using PySpark in Colaboratory. The data was further distributed into four additional data frames and transferred into three SQL tables: review_id_table, products_table, customers_table, and vine_table. The vine data frame was used to calculate the total number of reviews, the number of 5-star reviews, and the percentage of 5-star reviews for paid and unpaid reviews. The percentages were used to determine if having a paid Vine review makes a difference in the percentage of 5-star reviews. 

## Results:

#### - There were a total of 170 paid reviews and 37,840 unpaid reviews. 

#### - There were 65 paid and 20,612 unpaid 5-star reviews.

#### - 38% of the paid reviews were 5-star reviews and 54% of the unpaid reviews were 5-star reviews.

## Summary:

#### The results suggest there is no bias toward 5-star reviews when someone gets paid to write a review. Only 38% of the paid reviews were five-star compared to 54% of the unpaid reviews. Percentages for four-star and three to one-star reviews were also calculated to see if paid reviews were biased toward higher ratings. Of the paid reviews, 32% were 4-star, and 28% were three to one-star reviews. The results further support there is no bias toward five-star reviews when someone gets paid to leave a review. Star rating seem to be eavenly distributed when it comes to paid reviews. 
