# Griffin-Scoring
A Griffin Scoring Algorithm ranks items by giving different importance (weights) to different criteria.
For example, to rank sports goods, we might use:

Price → weight = 20%
Quality → weight = 30%
Rating → weight = 30%
Popularity → weight = 20%

The overall score is:

Score=(PriceScore×0.20)+(QualityScore×0.30)+(RatingScore×0.30)+(PopularityScore×0.20) 


Step-by-step algorithm
Read the number of items.
Read the number of criteria.
Read the weight of each criterion.
For each item:
Read its score for every criterion.
Multiply each score by its corresponding weight.
Add the weighted scores.
Store the total score for every item.
Sort items by total score in descending order.
Output the ranked items.
