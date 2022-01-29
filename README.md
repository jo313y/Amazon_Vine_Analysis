# Amazon_Vine_Analysis

## Overview
The Amazon Vine Analysis was performed to analyze the paid Amazon Vine Program. It is a paid service which allows manufactuerers and publishers to receive reviews for their products. Companies can pay a small fee to Amazon and provide products to Amazon Vine Members, who are then required to provide a review. For this analysis, the E-Book Purchase library was used. "https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Digital_Ebook_Purchase_v1_01.tsv.gz"

## Results
In the data, there were only 27 Amazon Vine Member reviews for the E-Book Purchase total. 

In order to determine significant values, the data was filterd to look at anything with greater than 20 votes, and a percentage of at least 50% of the votes were to be deemed "Helpful". Once this was evaluated, there were 0 Amazon Vine Member reviews and 65,149 non-Amazon Review votes. 

Out of the Non-Amazon Reviewer votes, there were 24,673 5-Star rating votes (37.87%). 

### List Results

![VineReviews](https://user-images.githubusercontent.com/86981530/151673695-1dd7c749-2217-41c6-b03b-d007bc4e3db5.PNG)


## Summary
Looking at all of the data, there can be no biased determined. This is because there weren't enough Amazon Review Members reviewing enough of the products. Only 27 out of the entire database (which is over 100,000 reviews) is such a small percentage. It's basically zero. This means that there is no biased, because there are no votes to really count.

Out of the reviews, it looks like 37.87% of the reviews are 5-star. This also coincides with the total review amount becuase there were no Amazon Reviewers in the data set. I would say that this is higher than usual.

Since there are 5 possible votes (1, 2, 3, 4, 5) I would expect 2/5 or around 40% to be 5 and 4 stars if they are all equally weighted. We see that 5-Star alone is 38%, which means there are more people voting for 5-Stars than expected. It's a fair assumption to say that when people enjoy a book, they would tend to take the time and leave a review. 

The analysis that is missing is the 1-Star and poor reviews. The real quesion is "Who leaves Reviews" if it isn't the Amazon Reveiwers. Is it mostly people who enjoy the book, or people who dislike the book. It would be a good analysis to determine the number of each star vote ratings to determine what the average reviewer votes. 
