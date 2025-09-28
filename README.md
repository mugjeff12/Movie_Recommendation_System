# 🎬 Movie Recommendation System

A personalized **movie recommendation engine** built in Python, applying both **content-based** and **collaborative filtering** methods.  
This project demonstrates the end-to-end process of working with large datasets: from cleaning and exploration, to implementing ML algorithms, to evaluating performance with real-world metrics.

---

## 📌 Features
- **Data Preprocessing**: Cleaned and structured the MovieLens dataset (user ratings + movie metadata).  
- **Exploratory Analysis**: Identified rating distributions, popular genres, and user behavior patterns.  
- **Content-Based Filtering**: Used movie metadata (genres, keywords, cast, crew) to generate cosine similarity–based recommendations.  
- **Collaborative Filtering**: Implemented user–item similarity models with scikit-learn to recommend movies based on peer preferences.  
- **Evaluation Metrics**: Calculated RMSE, precision, and recall to benchmark accuracy of recommendations.  
- **Visualization**: Generated plots of rating distributions, user similarity scores, and recommendation outcomes using Matplotlib/Seaborn.  

---

## 🛠️ Tech Stack
- **Languages**: Python (Jupyter Notebooks)  
- **Libraries**: NumPy, Pandas, scikit-learn, Matplotlib, Seaborn  
- **Dataset**: [MovieLens Dataset](https://grouplens.org/datasets/movielens/)  

---

## 🚀 How It Works
1. Load and preprocess the dataset (handle missing values, normalize ratings).  
2. Generate recommendations using:
   - **Content-based filtering** → cosine similarity of movie features.  
   - **Collaborative filtering** → user–item interactions and nearest neighbors.  
3. Compare models with RMSE and ranking metrics.  
4. Visualize recommendation outcomes and performance.  

---

## 📊 Results
- Built a working recommendation engine that suggests movies based on both **user preferences** and **movie similarity**.  
- Achieved measurable accuracy improvements over baseline popularity-based recommendations.  
- Demonstrated scalability for real-world applications (streaming, personalization).  



---

## 📌 Future Work
- Implement matrix factorization (SVD, ALS) for improved collaborative filtering.  
- Explore deep learning–based recommendation methods with PyTorch.  
- Deploy as a web app with Flask/Streamlit for interactive demos.  

---

## 👤 Author
**Mugdho Jeferson Rozario**  
- 🌐 [Portfolio](https://www.mjefersonrozario.com)  
- 💻 [GitHub](https://github.com/mugjeff12)  
- 🔗 [LinkedIn](https://www.linkedin.com/in/mugdho-rozario/)  

