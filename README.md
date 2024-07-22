# CODTECH-Task-2

**Name:** Leo Franklin S

**Company:** CODTECH IT SOLUTION

**ID:** CT08DS3834

**Domain:** Machine Learning

**Duration:** July to Augest 2025

**Mentor:** N.Santhosh


## Overview of the Project

### Project: IMDB Sentiment Analysis Web Application Using Logistic Regression

### Overview
This repository contains a Flask web application for sentiment analysis on IMDB movie reviews. The model uses a logistic regression classifier trained on a dataset of movie reviews to predict whether a given review is positive or negative.

### Features
  1.Text Preprocessing: Cleans and preprocesses movie reviews by removing HTML tags, numbers, punctuation, and stop words.
  
  2.TF-IDF Vectorization: Converts the text data into numerical vectors using TF-IDF (Term Frequency-Inverse Document Frequency).
  
  3.Model Training: Trains a logistic regression model to classify reviews as positive or negative.
  
  4.Web Interface: Provides a user-friendly web interface built with Flask to input reviews and get sentiment predictions.

### Usage

  1. Run the application
     
  2. Access the web application:

          Open your web browser and navigate to http://127.0.0.1:5000/.

  3. Predict Sentiment:

         Enter a movie review in the text box on the home page.
      
          Submit the form to get the sentiment prediction (Positive or Negative).

### File Structure

  1. app.py: Main application file containing the Flask routes and model logic.
 
  2. templates/: Folder containing HTML templates (index.html for input form).
  
  3. IMDB Dataset.csv: Dataset file (not included in the repository, to be placed manually).

### Model Details

  1. Text Preprocessing: Lowercase conversion, HTML tag removal, number removal, extra space removal, punctuation removal, stop words removal.
  
  2. Vectorization: TF-IDF with a maximum of 5000 features.

  3. Model: Logistic Regression with a maximum of 1000 iterations.
  
  4. Evaluation: Accuracy score, confusion matrix, and classification report.

### Output
![image](https://github.com/user-attachments/assets/a486ed2c-88ef-435b-b290-60b51d4c8505)

![image](https://github.com/user-attachments/assets/ed1fde5a-d477-47bb-a7a5-c75b045525ef)

