# Spotify Recommendation System

![206826750-ca6c97f1-56d7-4fab-9a9d-8ecc09776774](https://github.com/SyedsProjectPortfolio45/Spotify-Recommendation-System/assets/147240839/f76cd3b1-d792-4cb5-86c8-6bdb8e679b94)



#### Tools used🛠: Python, ML, NLP, NumPy, Pandas, Sk-learn, TensorFlow, Keras, spaCy
🔗dataset link -->https://raw.githubusercontent.com/amankharwal/Website-data/master/ner_dataset.csv 

## 🚧You see the detailed code with visualizations by clicking on the Google Colab logo when you open the ipynb file

# Objective
The aim is to build a ML model that tries to recognize and classify multi-word phrases with special meaning, e.g. people, organizations, places, dates, etc.

# How it works
For example, we want to monitor the news for mentions of Covid-19 patients and for each patient we need the name of the responsible medical organization, location and date.

The Named Entity Recognition task attempts to correctly detect and classify text expressions into a set of predefined classes. Classes can vary, but very often classes like people (PER), organizations (ORG) or places (LOC) are used.

## Step-by-step approach
- Imported necessary Python libraries and Dataset
- Performed data modification and data transformation to prepare the data for a neural network
- Divided the data for training and testing
- Created a function to split the data as LSTM layers only accept sequences of the same length. Thus, each sentence that appears as an integer in the data must be completed with the same length
- Now we import packages like Tensorflow and Keras to train our neural network
- Built layers that will take the dimensions of the LSTM layer and give the maximum length and maximum tags as output
- Create a helper function that will help us to give the summary of each layer of the neural network model for the task of recognizing named entities with Python
- Finally I will use the spacy library in Python to test our NER model. I will add input of some lines about my self and let’s see what we will get after running the code

# Output
