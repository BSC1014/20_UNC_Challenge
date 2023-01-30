# 20_UNC_Challenge
***
## Overview
***

    - The purpose of this analysis is to build a neural network machine learning model to better predict which applicants will be successfully funded by Alphabet Soup. In total the results of 34,000 organization that were previously funded will be used to train the model and also test against the results. 
***
## Results
***

Results: Using bulleted lists and images to support your answers, address the following questions.
### Data Preprocessing: 

    - The Target for this model is the "is successful" flag in the data set. We set this target using the code below: 

    - The features for this data set are all encoded classifications such as application type, affiliation, etc. as evidenced by the code snip below: 

    - Things line name and EIN are neither classifers or targets and were dropped from the model, snip below: 


### Compiling, Training, and Evaluating the Model

    - There were two layers using 80 and 30 neurons respectively. The activation function I selected was Sigmoid which was based on accuracy ratings from trying different functions. Screen shot as follows: 

    - The target model was not able to be achieved, but I was able to achieve 70% accuracy after a few tweaks to the model. Screen shot as follows: 

    - To increase the model performance, I tried removing some variables which in my opinion lacked importance in the model, next I tried increasing the hidden layers as well as running more epochs. 

***
## Summary
***
 - Overall, I was able to get the model to perform relativity well. To reach the target state of the desired 75% it would make sense to run a full blown tuner using Keras tuner to determine the appropriate amount of nodes, layers, and activation to best optimize the model.
