# Stock_Sentiment_Analysis

This is a project that takes the input as news headlines and predicts whether the stock price of a company is going to rise or fall.    
##  Libraries used  
Pandas    
Numpy   
Sklearn   
Nltk    
Re    
##    Process   
We split the dataset into the training and testing data on the basis of a date, that is the start of the year 2015. Then we manipulate the dataset to remove all Non-Alphabet characters from the data and to convert it to all lower characters.    
After this, we implement the bag of words model and use the Random Forest Classifier on the training data.    

After running the testing data, we get the following confusion matrix and model evaluation parameters:    

<img width="483" alt="Screenshot 2023-01-08 at 12 37 12 PM" src="https://user-images.githubusercontent.com/72307339/211184651-54635230-aa25-4dae-b720-0af7ae1b99e8.png">
