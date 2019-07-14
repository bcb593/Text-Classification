# Text-Classification
Sentiment Analysis - Movie Review 

This is the model to predict whether the movie reviews are positive or negative using natural language processing. 
The used data contains about 5000 different reviews. The file is tab separated file. 

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
