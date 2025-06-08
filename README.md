1. Project Title:- 🎬 Movie Recommendation System

2. Short Description:- A simple and interactive web app built using **Streamlit** that recommends movies based on similarity using **cosine similarity** of movie metadata.

---

3. ## 🔍 Features

- 🎞️ Recommends top 5 similar movies based on selected title
- 📽️ Displays movie posters using TMDB API
- 📦 Trained with TMDB 5000+ movie dataset
- ⚙️ Built with Python, Pandas, scikit-learn, Streamlit

---

4. ## 📁 Files Overview

- `app.py` → Main Streamlit app
- `movies.pkl` → Dataframe of movie titles and metadata
- `similarity.pkl` → Cosine similarity matrix (Large file tracked via Git LFS)
- `tmdb_5000_movies.csv`, `tmdb_5000_credits.csv` → Raw datasets used
- `MovieRecommende_system.ipynb` → Notebook for EDA & model building

---

5. ## Technologies Used

- Python
- Streamlit
- Pandas
- Pickle
- TMDB API
- Git Large File Storage (LFS)

---

6.  ## 🚀 Deployment

This app can be deployed using **Render.com**, **Streamlit Cloud**, or **locally**:

---


7.  ## Notes

- `similarity.pkl` is a large file, managed using Git LFS.
- To run the project smoothly, ensure all dependencies from `requirements.txt` are installed.

8.  ### ▶️ Run Locally:

```bash
pip install -r requirements.txt
streamlit run app.py

