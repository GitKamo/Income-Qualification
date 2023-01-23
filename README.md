# Income-Qualification

I identified the output variable as the level of income qualification needed for families in Latin America. I then understood the type of data, which was a dataset of Costa Rican household characteristics. I checked for any biases in the dataset and found that all members of the house did not have the same poverty level. I also discovered that there were some houses without a family head. I set the poverty level of the members and the head of the house within a family and counted how many null values were existing in the columns. I then removed the null value rows of the target variable. I used a random forest classifier to predict the accuracy and checked it using random forest with cross validation. All in all, I found that while the Proxy Means Test (PMT) method using an algorithm to verify income qualification was an improvement, accuracy remained a problem as the region’s population grew and poverty declined. The Inter-American Development Bank (IDB) believed that new methods beyond traditional econometrics, based on a dataset of Costa Rican household characteristics, might help improve PMT’s performance.
