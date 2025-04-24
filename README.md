A Python-based recommendation system that leverages Collaborative Filtering techniques to suggest movies based on user preferences and interactions. Built using the MovieLens 100K dataset, the system includes both user-based and item-based collaborative filtering models, model evaluation, and optional visualizations.

📝 Project Description
The project focuses on building a recommender system that:

Learns user preferences from the MovieLens 100K dataset.
Implements User-Based and Item-Based Collaborative Filtering.
Evaluates model accuracy using RMSE, Precision@K, and Recall@K.
Outputs top-N movie recommendations tailored to each user.
Collaborative Filtering assumes that users with similar tastes will prefer similar items. This project brings that to life through data analysis, algorithm implementation, and metric evaluation.

📂 Project Structure
collaborative-filtering-recommender/
├── README.md
├── requirements.txt
├── data/
│   ├── u.data
│   ├── u.item
│   └── u.user
├── notebooks/
│   ├── 01_data_preprocessing.ipynb
│   ├── 02_user_based_cf.ipynb
│   ├── 03_item_based_cf.ipynb
│   └── 04_evaluation_and_visualization.ipynb
├── src/
│   ├── __init__.py
│   ├── data_loader.py
│   ├── recommender.py
│   └── evaluation.py
└── results/
    ├── top_n_recommendations.csv
    └── evaluation_metrics.json
✅ Features
Load and preprocess the MovieLens 100K dataset
User-Based Collaborative Filtering
Item-Based Collaborative Filtering
Model Evaluation with RMSE, Precision@K, and Recall@K
Top-N movie recommendations for users
Optional visualizations for similarities and performance
