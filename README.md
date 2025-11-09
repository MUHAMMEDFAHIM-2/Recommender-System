In this task, I developed a recommender system using user behavior data from Steam, a popular video game distribution platform. The dataset contains over 200,000 entries detailing whether a user has purchased or played a game, with playtime represented in hours. By analyzing these implicit feedback signals, I used collaborative filtering to generate personalized game recommendations.

I leveraged Apache Spark's MLlib library, particularly the Alternating Least Squares (ALS) algorithm, to handle large-scale matrix factorization. My workflow included data loading, cleaning, preprocessing, model training, hyperparameter tuning, and result evaluation. The entire pipeline was implemented in Databricks for scalable performance and integrated MLflow tracking.

This notebook is structured to provide not only functional code but also thorough explanations of each step to promote clarity, reproducibility, and good software engineering practice.
