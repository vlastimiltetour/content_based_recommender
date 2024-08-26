### Product Recommendation System Using Efir the Brand Data

This project focuses on building a product recommendation system by utilizing product data from the Efir brand's webpage. The workflow includes:

1. **Data Collection**: Extracting product data from the Efir brand's feed & **element tree**.
2. **Data Preparation**: Using **pandas** to adjust and clean the data in a DataFrame format.
3. **Feature Extraction**: Leveraging product descriptions as the source data, applying **TF-IDF** **vectorization**** by sci-kit** to extract relevant features.
4. **Similarity Calculation**: Implementing cosine similarity using **scikit-learn** to determine product similarities.
5. **Clustering**: Applying the elbow method to estimate the optimal number of **clusters** for product categorization.
6. **Recommendation System**: Predicting and recommending products based on the calculated similarities.

This system is designed to provide accurate and efficient product recommendations, enhancing the user experience on Efir's platform.

Major tools: Python, Sci-kit learn, ETtree, Pyplot. See requirements.txt

