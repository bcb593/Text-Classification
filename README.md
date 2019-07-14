# Text-Classification
Sentiment Analysis - Movie Review 

This is the model to predict whether the movie reviews are positive or negative using natural language processing in scikit learn using jyputer notebook.

For this project we'll use the Cornell University Movie Review polarity dataset v2.0 obtained from http://www.cs.cornell.edu/people/pabo/movie-review-data/

This dataset contains about 5000 different reviews and they are tab separated file. 

The procedure for the model is as follows:
- Load the data.
- Clean the data, remove the null items.
- Split the data into training data and test data.
- Create a pipleline model.
- Import TfidfVectorizer which changes the strings into the vector form.
- Train the data using fit method.
- Make predictions the test data.
- Check accuracy of the model.
- Predict your own review by passing in the form of list.
