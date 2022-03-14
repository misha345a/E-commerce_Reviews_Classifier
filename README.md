# E-commerce Reviews Classification

## Dataset
The dataset used is from https://www.kaggle.com/nicapotato/womens-ecommerce-clothing-reviews.

## Notebooks
This repo contains several notebooks:
- ```EDA``` contains visualizations and analysis gathered from the dataset.
- ```TF-IDF_Random_Forest.ipynb``` includes a RF model trained on TF-IDF and optimized with grid-search.
- ```Create_Balanced_Dataset.ipynb``` cleans and balances the dataset using two different methods: resampling and text augmentation.
- ```LSTM_Models_And_Attack.ipynb``` trains an LSTM neural network and evaluates its performance after a textual adversarial attack.
- ```ASBA.ipynb``` demonstrates aspect-based sentiment prediction to find relevant business insights.

## Published Article
https://towardsdatascience.com/nlp-project-with-augmentation-attacks-aspect-based-sentiment-analysis-3342510c90e7

## Attack on a Trained LSTM Model!
![TextAttack_In_Progress](https://user-images.githubusercontent.com/84154105/153041919-02df48fb-0be1-4194-9990-a3182386c3c8.gif)
