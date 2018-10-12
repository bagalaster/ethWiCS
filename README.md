<h1>ethWiCS Hack Overflow Hackathon Project</h1>

Contributors: Mac Bagwell, Matthew King, Megumi Sano, Julia Gong, Ben Newman

Using the Kaggle dataset https://www.kaggle.com/aljarah/xAPI-Edu-Data

The goal of this project was to experiment with different statistical models for primary school and
secondary school student performance based on class participation data and student demographics. To
build our model we considered a data set of 480 students tracking 17 features including basic
demographic data, class participation data, and parent satisfaction data. More details about the
dataset can be found at the link above.

We constructed 4 machine learning models, including a logistic regression model, an SVC model, a
LinearSVC model, and a Naive Bayes model. We then split the data set into a training set and a testing
set (about an 80/20 split). For each model, we then trained on the training data and experimented with 
their respective hyperparameters to determine the combination that optimized their accuracy on the test data.
All of the source code for this can be found in ethWiCS/Engaging_with_Ethucation.ipynb

We found that the Logistic Regression model was able to predict performance with the highest accuracy,
but our search was far from exhaustive. Limiting factors included computing power and time. Given
more resources, we would have liked to conduct more preliminary analysis on the data as well as a more 
exhaustive grid search of the hyperparameters.

We would also have liked to investigate other potentially deeper biases in the data. For example, 
in some of the preliminary analysis of the data, we found that for male students, participation 
in class correlated strongly with student performance, whereas this was not the case for female students. 
One could make the argument that social expectations for female students' behavior in these classrooms
was different from those for their male counterparts'. If this were the case, its possible that our
models believe that females who participate more are more likely to perform poorly than males who
participate just as much; certainly a bias which most can agree we ought to avoid. More investigation
would be needed.
