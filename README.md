*Advanced Content Recommendation System*

### H&M Personalized Fashion Recommendations
##  Provide product recommendations based on previous purchases

This repository is for Kaggle Competition 
Kaggle Link - https://www.kaggle.com/c/h-and-m-personalized-fashion-recommendations/

H&M Group is a family of brands and businesses with 53 online markets and approximately 4,850 stores. Their online store offers shoppers an extensive selection of products to browse through. But with too many choices, customers might not quickly find what interests them or what they are looking for, and ultimately, they might not make a purchase. To enhance the shopping experience, product recommendations are key. More importantly, helping customers make the right choices also has a positive implications for sustainability, as it reduces returns, and thereby minimizes emissions from transportation.

## Dataset 

For this challenge you are given the purchase history of customers across time, along with supporting metadata. Your challenge is to predict what articles each customer will purchase in the 7-day period immediately after the training data ends. Customer who did not make any purchase during that time are excluded from the scoring.

## Files

* images/ - a folder of images corresponding to each article_id; images are placed in subfolders starting with the first three digits of the article_id; note, not all article_id values have a corresponding image.
* articles.csv - detailed metadata for each article_id available for purchase
* customers.csv - metadata for each customer_id in dataset
* sample_submission.csv - a sample submission file in the correct format
* transactions_train.csv - the training data, consisting of the purchases each customer for each date, as well as additional information. Duplicate rows correspond to multiple purchases of the same item. Your task is to predict the article_ids each customer will purchase during the 7-day period immediately after the training data period.


NOTE: You must make predictions for all customer_id values found in the sample submission. All customers who made purchases during the test period are scored, regardless of whether they had purchase history in the training data.

## Contributing

PR's are welcome !

Found a Bug ? Create an Issue.

Chat on [Slack](https://join.slack.com/t/newworkspace-9gk8128/shared_invite/zt-w6xv6tzr-gbHlelZiLQocs_twNmOypg)

<br/>


## Like this project ?

Leave a ??? If you think this project is cool.

<br/>


## Author

* Pawan Rama Mali 
  * [GitHub](https://github.com/PawanRamaMali) 
  * [Twitter](https://twitter.com/PawanRamaMali) 


## Licence

* [MIT License](LICENSE)
