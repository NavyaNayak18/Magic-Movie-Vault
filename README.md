# **Magic Movie Vault: Collaborative Filtering Movie Recommendation System**

This repository contains a deep learning-based movie recommendation system built using **collaborative filtering**. The system uses the **MovieLens 100k dataset** to predict movie ratings for users and generate personalized movie recommendations. The model is implemented using **TensorFlow/Keras**.

The goal of this project is to recommend movies to users based on their historical ratings, leveraging a collaborative filtering approach with neural networks and embeddings.

---

## **Features**

- **MovieLens 100k Dataset**: A dataset containing 100,000 ratings from 943 users on 1,682 movies.
- **Collaborative Filtering**: Uses collaborative filtering techniques to predict movie ratings and generate recommendations.
- **Neural Network Model**: Utilizes a deep learning model with user and movie embeddings to predict ratings.
- **Recommendations**: Personalized movie recommendations are generated based on the predicted ratings.
- **Evaluation**: Model performance is evaluated using **mean squared error (MSE)**.

### Key Components:

1. **Model Architecture**:
   - Embedding layers for both users and movies.
   - Dot product of user and movie embeddings to predict ratings.
   - Fully connected layers for non-linear transformations and improved prediction accuracy.

2. **Data Preprocessing**:
   - User IDs and Movie IDs are encoded using **LabelEncoder**.
   - Dataset is split into training and testing sets.

3. **Recommendation Generation**:
   - After training, the model can recommend movies by predicting ratings for unseen movies for a given user.

4. **Model Evaluation**:
   - The model is evaluated using MSE to ensure the predictions are as accurate as possible.
