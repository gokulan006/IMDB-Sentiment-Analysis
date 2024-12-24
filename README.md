IMDB Sentiment Analysis  
Project Description   
This project performs sentiment analysis on IMDB movie reviews to classify them as either positive or negative. It utilizes Natural Language Processing (NLP) techniques to clean the data and create a Bag of Words model. A logistic regression model is then trained and evaluated for its performance.  

Features  
 *Text preprocessing (removal of special characters, stopwords, and stemming).  
 *Bag of Words model for feature extraction.  
 *Logistic Regression for classification.  
 *Model evaluation using accuracy, confusion matrix, and classification report. 

Dataset  
The dataset contains movie reviews with their corresponding sentiment labels (positive/negative). It was imported as IMDB Dataset.csv.  

Results  
Accuracy: 87.42%  

Confusion Matrix:  
 
  [[4376  659]  
   [ 599 4366]]  
   
Classification Report:
 
              precision    recall  f1-score   support

           0       0.88      0.87      0.87      5035
           1       0.87      0.88      0.87      4965

    accuracy                           0.87     10000
    

macro avg          0.87      0.87      0.87     10000    
weighted avg       0.87      0.87      0.87     10000  

Technologies Used  
  Python  
  Libraries: NumPy, pandas, scikit-learn, NLTK, Matplotlib  
  
Installation and Setup  
  *Clone the repository:  
   git clone https://github.com/your-username/your-repository.git  
  *Install the required dependencies:  
   
   pip install -r requirements.txt  
 *Place the dataset file (IMDB Dataset.csv) in the project directory.  
 *Run the Jupyter Notebook or Python script to execute the project.  
 
Usage  
 *Preprocess the text data.  
 *Train the logistic regression model on the training dataset.  
 *Evaluate the model on the test dataset.  
 
Contributors  
 gokulan006  
 
