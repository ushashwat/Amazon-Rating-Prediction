# Amazon Rating Prediction
Predict the average review ratings of products on Amazon </br>


Online product reviews provided by consumers who previously purchased products have become a major information source for consumers and marketers regarding product quality. Research has shown that consumer online product ratings reflect both the customers' experience with the product and the influence of others' ratings. Websites prominently display consumers' product ratings, which influence consumers' buying decisions and willingness to pay. </br>


![Image!](https://github.com/ushashwat/Amazon-Rating-Prediction/blob/main/ratings.png) </br>


### Data Description
There are 16 independent variables and 1 dependent variable. There are nearly 10k observations combining both train and test dataset. </br>
* uniq_id
* product_name
* manufacturer
* price
* number_available_in_stock
* number_of_reviews
* number_of_answered_questions
* average_review_rating
* amazon_category_and_sub_category
* customers_who_bought_this_item_also_bought
* description
* product_information
* product_description
* items_customers_buy_after_viewing_this_item
* customer_questions_and_answers
* customer_reviews
* sellers


The test set contains all the above variables except for average_review_rating, which is to be predicted. </br>


### Acknowledgement
This dataset was created by PromptCloud's in-house web-crawling service. </br>
