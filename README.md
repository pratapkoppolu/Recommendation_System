## Recommendation_System
#Dataset Description:

The kurtiData.csv dataset sourced from Kaggle contains information related to kurtis, a popular garment in South Asian fashion. This dataset is structured with the following columns:

user_id: Unique identifier for each user interacting with the kurtis.
product_id: Unique identifier for each kurti product.
product_url: URL linking to the product page.
image_url: URL linking to the image of the product.
price: Price of the kurti product.
rating: User-generated rating for the kurti product.
timestamp: Timestamp indicating when the interaction occurred.
Dataset Statistics:

Rows: 425,998
Columns: 7
Purpose:
This dataset is valuable for analyzing user interactions with kurti products on an e-commerce platform. It enables the development of AI models for tasks such as personalized recommendations, content generation, and A/B testing frameworks to enhance user engagement and satisfaction.

# Data Analysis 
Data analysis is performed on the kurtiData.csv dataset to identify popular kurti products based on user interactions. Among the analyzed products, "Adrika Voguish Kurtis" emerges with the highest number of ratings at 4,748 and an average rating of 4.36 stars. Following closely is "Zola Georgette Ethnic Wear" with 385 ratings and an average rating of 4.29 stars. This analysis provides insights into product popularity and user preferences.

# Recommendation based on User-based collaborative filtering
User-based collaborative filtering recommends products to a user based on similarities between their preferences and those of other users. Its advantages include simplicity in implementation and effectiveness in recommending items liked by similar users. Limitations include cold start problem for new users and sparsity of data impacting recommendation quality for less popular items.

# Recommendation based on Item-based collaborative filtering

Item-based collaborative filtering recommends products to a user based on similarities between the items they have interacted with, rather than similarities between users. Its advantages include better scalability with large datasets and robustness against new user introductions (cold start problem). Item-based filtering can excel in scenarios where item characteristics drive recommendations more effectively than user preferences alone, as shown by its effectiveness in suggesting similar products based on item interactions.
# Recommendation system uisng TensorFlow with A/B Framework
Implemented a recommendation system using TensorFlow, employing collaborative filtering with embeddings for user and product interactions. Incorporated an A/B testing framework to evaluate model variations (A and B), tracking user interactions and analyzing average engagement metrics to assess performance and refine recommendations.




