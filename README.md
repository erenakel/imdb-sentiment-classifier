# IMDB Sentiment Classifier

## Project Overview
This project builds a sentiment analysis model using a bi-directional LSTM network to classify IMDB movie reviews as positive or negative. The model is trained on a dataset of movie reviews and deployed as a Flask API for real-time predictions.

## Author

Eren Akel

## Dataset
The dataset contains IMDB movie reviews labeled as either positive or negative. It is used to train and evaluate the model’s performance.

## Steps in the Project

### Data Preprocessing
- Loaded and cleaned the dataset  
- Tokenized and vectorized text using the `TextVectorization` layer  
- Converted text into numerical sequences for model training  

### Model Training
- Used a bi-directional LSTM network for sentiment classification  
- Split the dataset into training and test sets (80/20)  
- Achieved a test accuracy of **83.4%**  

### Model Evaluation
- Compared predicted vs. actual sentiment labels  
- Evaluated model performance using accuracy metrics  

### Deployment
- Saved the trained model in `.keras` format  
- Developed a Flask API to serve predictions  
- Used ngrok to make the API externally accessible  

## Results
The model successfully classifies IMDB reviews with high accuracy. The API allows real-time sentiment analysis by processing text input and returning classification results.
