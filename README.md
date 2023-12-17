# Hybrid Joke Recommendation System

Welcome to the Hybrid Joke Recommendation System! This project combines the power of collaborative filtering and content-based filtering to provide users with personalized and entertaining joke recommendations. Whether you're a fan of witty one-liners, clever puns, or humorous stories, this recommendation system is designed to tickle your funny bone.

## Overview

The Hybrid Joke Recommendation System employs a combination of Collaborative Filtering (CF) and Content-Based Filtering (CBF) to enhance the accuracy and diversity of joke recommendations. By leveraging user preferences and joke content features, the system aims to deliver personalized suggestions that align with individual tastes.

### Collaborative Filtering

Collaborative Filtering is based on the idea that users who have agreed in the past tend to agree in the future. This system utilizes both user-based and item-based collaborative filtering techniques to identify similar users and items, respectively. By analyzing user preferences and behaviors, the system can recommend jokes liked by users with similar tastes.

### Content-Based Filtering

Content-Based Filtering focuses on the characteristics of items and users' preferences for those characteristics. In the context of joke recommendation, this involves extracting features from jokes (e.g., humor style, topic, language complexity) and tailoring recommendations based on users' preferences for these features.

## Components

1. **Data Collection**: Gather a dataset of jokes, including user ratings and relevant joke features.

2. **Data Preprocessing**: Clean and preprocess the dataset, handling missing values and ensuring uniformity in the data.

3. **Collaborative Filtering**:
   - **User-Based CF**: Identify similar users and recommend jokes liked by those with similar tastes.
   - **Item-Based CF**: Determine similar jokes and recommend them based on user preferences.

4. **Content-Based Filtering**:
   - **Feature Extraction**: Extract relevant features from jokes, such as humor style, topic, and length.
   - **TF-IDF Vectorization**: Convert textual features into numerical vectors.
   - **Recommendation Generation**: Use content-based techniques to generate personalized joke recommendations.

5. **Hybrid Model Integration**: Combine collaborative and content-based filtering to create a hybrid model that leverages the strengths of both approaches.

## Getting Started

1. **Clone the Repository**:

    ```bash
    git clone https://github.com/your-username/joke-recommendation-system.git
    ```

2. **Install Dependencies**:

    ```bash
    pip install -r requirements.txt
    ```

3. **Data Preparation**:

    - Acquire a dataset of jokes with user ratings and relevant features. We are using famous jester-joke dataset 1 with 4.1 million ratings
    - Organize the dataset into training and testing sets.

4. **Training and Evaluation**:

    - Train the collaborative filtering and content-based models.
    - Evaluate the performance of each model individually has been done.

5. **Hybrid Model Integration**:

    - Combine the collaborative and content-based models to create the hybrid recommendation system.
    - Fine-tune parameters for optimal performance.

For more details please check project report, which is provided in repo.

Get ready to laugh out loud with personalized joke recommendations! 😄🎉
