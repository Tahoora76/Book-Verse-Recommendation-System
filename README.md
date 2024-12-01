# Book Verse Recommendation System

## Overview
Book Verse Recommendation System is a collaborative filtering-based recommendation engine that suggests books to users based on their preferences and past interactions. By leveraging advanced techniques such as Singular Value Decomposition (SVD), the system offers personalized book recommendations with high accuracy.

## Features
- Personalized book recommendations using collaborative filtering.
- Memory-based and model-based approaches for recommendation.
- Data cleaning, preprocessing, and feature engineering for robust predictions.
- Evaluation using RMSE (Root Mean Squared Error).

## Datasets
The project uses three datasets:
1. **Books Dataset**:
   - Contains ISBN, Book-Title, Book-Author, Year-Of-Publication, Publisher, and image URLs.
2. **Users Dataset**:
   - Includes User-ID, Location, and Age.
3. **Ratings Dataset**:
   - Includes User-ID, ISBN, and Book-Rating.

## Methodology
### Collaborative Filtering Techniques
1. **Memory-Based Collaborative Filtering**:
   - Finds similarities between users or items based on their ratings.
   - Recommends books based on user-user or item-item similarity.

2. **Model-Based Collaborative Filtering**:
   - Uses Singular Value Decomposition (SVD) for matrix factorization.
   - Extracts latent factors for better recommendations.

### Model Evaluation
- The models are evaluated using RMSE (Root Mean Squared Error). The lower the RMSE, the better the model's performance.
- SVD outperforms memory-based methods with an RMSE score of **1.63**.

## Installation
Follow these steps to run the project locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/Tahoora76/Book-Verse-Recommendation-System.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Book-Verse-Recommendation-System
   ```

3. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

## Usage
1. Open the Jupyter notebook in your browser.
2. Load the datasets provided in the `data/` folder.
3. Run the cells to preprocess the data, train the models, and generate recommendations.
4. View personalized book recommendations for users based on their preferences.

## Results
- The SVD-based model achieved an RMSE score of **1.63**.
- Top book recommendations are generated based on user preferences and ratings.

## Technologies Used
- **Python**
- **Pandas**: Data manipulation
- **NumPy**: Numerical operations
- **Scikit-learn**: Machine learning models
- **Matplotlib** & **Seaborn**: Data visualization
