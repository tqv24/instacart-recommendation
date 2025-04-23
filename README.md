# Market Basket Analysis & Recommendation System

This project explores consumer purchasing behavior through market basket analysis and develops personalized recommendation systems. It uses both classic association rule mining (Apriori and FP-Growth) and modern recommendation techniques (Collaborative Filtering and Deep Neural Networks).


## 🔍 Objectives

- Understand customer behavior through itemset association rules.
- Compare Apriori and FP-Growth algorithms in terms of efficiency and rule generation.
- Build a hybrid recommendation engine using:
  - **Collaborative Filtering** for user-user and item-item similarity.
  - **DNN** for capturing complex interaction between users and items.

## 🧰 Technologies Used

- **Python** (Pandas, NumPy, Scikit-learn, TensorFlow/Keras)
- **MLxtend** – for Apriori and association rule generation
- **Efficient-Apriori** / **FP-Growth**
- **Surprise / LightFM** – for collaborative filtering (if used)
- **Matplotlib / Seaborn / Plotly** – for data visualization
- **Jupyter Notebooks**

## 📊 Key Features

- Frequent itemset mining using **Apriori** and **FP-Growth**.
- Association rule extraction with metrics: *support, confidence, lift*.
- EDA to explore customer patterns and purchase trends.
- Collaborative filtering to recommend items based on user history.
- DNN-based recommender that incorporates user/item embeddings and interactions.

## 📈 Example Outputs

- Market basket rules such as:
{milk, bread} => {butter} (support: 0.06, confidence: 0.8, lift: 1.3)
- User-specific product recommendations ranked by predicted rating or relevance.

## 🚀 How to Run

1. Clone the repository:
 ```bash
 git clone https://github.com/yourusername/yourrepo.git
 cd yourrepo
