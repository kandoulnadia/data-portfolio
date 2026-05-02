#  Hybrid Product Recommendation System (Deep Learning + TF-IDF)

##  Project Overview
This project is a product recommendation system built using an Amazon dataset.  
It combines **Natural Language Processing (TF-IDF)** and **Deep Learning embeddings** to recommend similar products based on titles and user interactions.

The goal is to improve product discovery and simulate real-world e-commerce recommendation engines like Amazon.

---

##  Objectives
- Clean and preprocess large e-commerce dataset
- Perform feature engineering on product data
- Build text representation using TF-IDF
- Learn product embeddings using Deep Learning
- Build a hybrid recommendation system
- Analyze business insights using visualizations

---

##  Pipeline

1. Data Cleaning & Preprocessing  
2. Feature Engineering  
   - Discount percentage  
   - Popularity score  
3. Text Processing (clean product titles)  
4. TF-IDF Vectorization  
5. Deep Learning Embeddings  
6. Cosine Similarity Computation  
7. Hybrid Recommendation Engine  
8. Data Visualization & Analysis  

---

##  Models Used

- TF-IDF (Text Similarity)
- Neural Network Embeddings (Deep Learning)
- Cosine Similarity (Distance Metric)
- Hybrid Weighted Model (TF-IDF + DL)

---

## Features Used

- product_title  
- product_rating  
- total_reviews  
- purchased_last_month  
- discounted_price  
- original_price  
- is_best_seller  
- is_sponsored  
- has_coupon  
- popularity_score  

---

##  Key Insights

- Best sellers tend to have higher ratings  
- Discounted products influence purchase behavior  
- Popularity score strongly correlates with sales  
- Hybrid model improves recommendation quality  

---

## 🛠️ Technologies

- Python 🐍  
- Pandas, NumPy  
- Scikit-learn  
- TensorFlow / Keras  
- Plotly / Matplotlib / Seaborn  
- Kaggle / Google Colab  

---

##  Output

The system recommends top-N similar products based on:
- Product similarity (TF-IDF)
- Semantic similarity (Deep Learning embeddings)
- Hybrid scoring system

---

##  Business Value

This system helps:
- Improve product discovery 
- Increase e-commerce sales  
- Enhance user experience   
- Provide personalized recommendations  

---

## How to Run

1. Load dataset (Amazon products)
2. Run preprocessing pipeline
3. Train TF-IDF + embedding model
4. Generate recommendations:

```python
recommend_product("AirPods", top_n=5, method="hybrid")