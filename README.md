# Amazon_Vine_Analysis



## Overview

 This analysis examines the Amazon Review dataset for kitchen products, downloaded from
https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt to compare the frequency of 5-star ratings among participants of the Vine program, and among the general population.

 This analysis addresses the concern that paid reviewers might be biased toward higher ratings.




## Results


* Paid reviews:
  - 1,207 total
  - 509 5-star
  - 42.2% 5-star

* Unpaid reviews:
  - 97,839 total
  - 45,858 5-star
  - 46.9% 5-star


These statistics are for reviews that got at least 20 votes from other users, with at least half of those "helpful".


## Summary

 Vine reviewers do not appear to be biased towards 5-star reviews: only 42% of paid reviews are 5-star, less that the 47% of unpaid reviews.

 My further analysis of all reviews, including the vast majority that were not marked as "helpful" by other users, also supports this conclusion. Among all reviews, less than 50% of the paid ones were 5-star, but over 60% of the unpaid ones were 5-star. If anything, we see a bias against 5-star ratings among paid reviewers. 

 It could also be interesting to compare paid reviews to verified reviews, in case the bias of unpaid reviewers towards 5-star ratings comes from unsophisticated fake rating-inflation activity, landing those fake 5-star reviews in the "unverified" category.

 I would also rerun the analysis without cutting down the data to just 5-star or not 5-star, to see whether paid reviewers are biased away from low ratings.

