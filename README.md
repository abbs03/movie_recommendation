# Movie Recommendation System

This project contains Jupyter notebooks for building movie recommendation systems using **content-based filtering** and **collaborative filtering**.

## Methods Used

1. **Content-Based Filtering**  
   - Utilized movie crew and overview data.  
   - Embedded textual data using the `sentence-transformers` model: `all-MiniLM-L6-v2`.  
   - Recommendations are based on similarity between movie embeddings.

2. **Collaborative Filtering**  
   - Implemented matrix factorization using PyTorch to uncover latent features.  
   - Identified similar users based on these features.  
   - Recommended top-rated movies among those preferred by similar users.

## Data Source
The dataset used in this project is [The Movies Dataset](https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset) from Kaggle.
