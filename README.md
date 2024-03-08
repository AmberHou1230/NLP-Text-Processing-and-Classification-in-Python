# NLP-Text-Processing-and-Classification-in-Python

## Background 
NLP gives machines the ability to understand, read, and get meaningful insights from the human language.


## Project walkthrough 
1. Data Description and visualization
2. Data Preprocessing

   a. Conversion to lowercase
   
   b. Tokenization
   
   c. Stopwords removal
   
   d. Punctuation removal
   
   e. Stemming
   
3. Bag of Words

   a. Binary
   
   b. Non-binary
   
   c. N-grams
   
4. TF-IDF
5. Model Building and Accuracy
6. Predictions on new reviews

## Tech stack
- Language: Python

- Libraries: pandas, seaborn, matplotlib, sklearn, nltk

## Data Description 
The dataset contains more than a thousand reviews about an application openly available to the public. The data includes reviews and sentiment, i.e., is the review being either positive or negative with various other variables.  

The data looks something like this: 
![image](https://github.com/AmberHou1230/NLP-Text-Processing-and-Classification-in-Python/assets/116517923/cdc60df7-29df-43ec-9cb3-1710a6053193)


## Objective 
- Build a binary text processing and classification model

## Modular Code Overview 
![image](https://github.com/AmberHou1230/NLP-Text-Processing-and-Classification-in-Python/assets/116517923/f404f1ea-d8d7-48f8-ad90-3e7f58c54d0a)

1. The input folder contains the data that we have for analysis, named Canva_reviews.xlsx.

2. The source folder contains all the modularized code for all the above steps in a
modularized manner. It includes the following:

   a. model.py
   
   b. processing.py
   
   c. utils.py

   All these python files contain helpful functions that are being used in the Engine.py file.

3. The output folder contains all the pre-trained models and vectorizers. These
models can be quickly loaded and used for future use, and the user need not
have to train all the models from the beginning.

4. The config.py file contains all the configurations required for this project.

5. The Engine.py file is the main file that needs to be called to run the entire code in
one go. It trains the model and saves it in the output folder.

6. The predict.py file is used to predict the probability of new reviews.

7. The requirements.txt file has all the required libraries with respective versions.



