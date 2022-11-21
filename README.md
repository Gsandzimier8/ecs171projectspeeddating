# Speed Dating

## Abstract

We will be exploring the Speed Dating dataset provided on Kaggle. The dataset contains data from a speed dating experiment where participants answered questions relating to dating behavior and qualities of a partner, and whether there was a match between the partners. We are interested in exploring if perceived interest from a partner increases the likelihood of matching with them. Using the attributes for ranking hobbies, we also want to look at shared interest between partners and see if having more shared interests increases the chance of a match. We would also like to see if a participant’s rating of themselves on attractiveness, intelligence, humor, ect. affects match probability.The data set consists of over 190 different attributes relating to 2 subjects (people), indicated as self and partner. The types of attributes range from binary, continuous, scaler, and categorical. The attributes cover the subjects’ hobbies, demographics, personal information, and interest in each other. Our target attribute is whether or not the two subjects are a match. With this data set we will start out by encoding many of the categorical features, for example, yes or no questions will be converted to 1 for yes and 0 for no. From there if the data is not normal we will scale it from zero to one using the MinMax method. Furthermore, we will combine features, drop features and create new features to isolate and analyze the specific data needed to answer our hypotheses. With the preprocessed data, we will explore supervised learning models like linear regression, logarithmic regression and SVM to explore which factors make someone more likely to be a match. We will take a close look at correlation matrices and coefficients produced by these models to evaluate which features were the most influential or if they did not have any influence at all. Our goal in evaluating the dataset is to determine whether or not a confident person is more likely to find a match, whether a match is more likely if both parties share interests, and how good people are at judging what the other person thinks of them.

https://www.kaggle.com/datasets/whenamancodes/speed-dating

## Data Exploration
The columns we are focusing on are: percieved interest, sharedinterestso, sharedinterestpartner, interestscorrelate, attractive, sincere, intelligence, funny, and ambition. Of these columns, the ones relating to assessing oneself are skewed low as a result of people overvaluing themselves we will normalize features and drop columns to evaluate our hypotheses.
