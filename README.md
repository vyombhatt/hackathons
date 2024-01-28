# hackathons
Repository for Hackathons

### 1. Product Category Prediction from Invoice Data
- As part of a HackerEarth challenge, the invoice data for different products from different suppliers was provided. As part of the challenge, we had to identify certain features by breaking down the item description of each product to elp classify the products into the different classes that were provided in the training dataset

- In the case of my solution, the Random Forest Classification learning algorithm was used to create our final multi-class model that classifies the different products in the test data into their corresponding product category

### 2. India v. Australia Cricket Series Prediction

Predictions for the top scorer, top wicket taker, player who will hit the most 4's and 6's for the upcoming India-Australia ODI Series Feb 2019

Initial dataset The data that was considered for the prediction was post 2011 ICC Cricet World Cup onwards. All the matches that featured India and Australia have been considered. The data was put together from varoius sources i.e. howstat.com, cricinfo statsguru API, and the cricinfo statistics

For the match level predictions:
Logistic regression was done on the match level data to identify - output (1- India wins, 0- Australia wins) Input variables: "Opponent Rating", "Average Stadium Runs per Wicket", " Average Stadium Runs per Over", "Stadium Home Team Win %", "Stadium Away Team win %"
Output: India wins series 5:0

For Predicting Highest Run Scorer:
Linear regression was done on batsmen level data Input variables: "Opponent Rating", "Average Stadium Runs per Wicket", " Average Stadium Runs per Over", "Stadium Home Team Win %", "Stadium Away Team win %", "Batsman ICC Rating"
Output: Virat Kohli is the highest run scorer in the series
Breakdown of Top Run Scorers: Player Virat Kohli (Capt) 249.0 Rohit Sharma (vc) 240.0 Shikhar Dhawan 211.0 MSD (wk) 195.0 Aaron Finch(c) 182.0

For Predicting the most number of 4's and 6's
Linear Regression was done on batsmen level data Input variables: "Opponent Rating", "Average Stadium Runs per Wicket", " Average Stadium Runs per Over", "Stadium Home Team Win %", "Stadium Away Team win %", "Batsman ICC Rating"
Output: Virat Kohli will hit the most 4's and 6's

For Predicting the highest wicket-taker
Linear Regression was done on bowler level data Input variables: "Opponent Rating", "Average Stadium Runs per Wicket", " Average Stadium Runs per Over", "Stadium Home Team Win %", "Stadium Away Team win %", "Bowler ICC Rating"
Output: Yuzvendra Chahal will be the highest wicket taker