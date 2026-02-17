# 🎬 Movie Recommendation System

An AI-powered Movie Recommendation System that suggests similar movies based on user search or selection. The application uses Machine Learning (TF-IDF + cosine similarity) to recommend relevant movies and provides an interactive UI for exploring movie details.

---

## 🚀 Live Demo

* 🌐 **Live URL:** [https://movie-recommendation-system-platform.streamlit.app]
---

## 📌 Features

✅ Search movies by title
✅ Content-based movie recommendation system
✅ Dynamic recommendations displayed instantly
✅ Movie poster grid layout
✅ Movie details view
✅ Query parameter navigation (shareable URLs)
✅ FastAPI backend integration
✅ Machine Learning powered recommendations
✅ Responsive UI using Streamlit

---

## 🧠 Recommendation Logic

The recommendation system uses a **content-based filtering approach**.

### Process:

1. Movie metadata is processed and combined into feature text.
2. TF-IDF (Term Frequency–Inverse Document Frequency) vectorization converts text into numerical vectors.
3. Cosine similarity is calculated between movie vectors.
4. When a user selects or searches for a movie:

   👉 Similar movies are retrieved based on similarity scores.

This approach recommends movies with similar genres, keywords, or content features.

---

## 🛠️ Tech Stack

### Frontend

* Streamlit
* Python

### Backend

* FastAPI
* REST API

### Machine Learning

* Scikit-learn
* TF-IDF Vectorizer
* Cosine Similarity

### Data Processing

* Pandas
* NumPy

### Model Handling

* Pickle (Serialized ML model)

### APIs

* TMDB API (Movie posters and details)

---

## 📊 Dataset

* Custom movie dataset used for generating recommendations.
* Preprocessed movie metadata converted into TF-IDF features for similarity calculations.

---

## 🏗️ Project Architecture

```
User → Streamlit UI → FastAPI Backend → ML Recommendation Engine → Response
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository

```
git clone https://github.com/YOUR_USERNAME/movie-recommendation-system.git
cd movie-recommendation-system
```

---

### 2️⃣ Create Virtual Environment

```
python -m venv venv
```

Activate:

```
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows
```

---

### 3️⃣ Install Dependencies

```
pip install -r requirements.txt
```

---

### 4️⃣ Run Backend (FastAPI)

```
uvicorn main:app --reload
```

---

### 5️⃣ Run Frontend (Streamlit)

```
streamlit run app.py
```

---

## ☁️ Deployment

### Backend

* Deployed using **Render**
* Built with FastAPI for scalable API architecture.

### Frontend

* Deployed using **Streamlit Cloud**
* Interactive UI connected to backend API.


---

## 👨‍💻 Author

**Ankit Mishra**

Full Stack Developer | Machine Learning Enthusiast

---

## ⭐ Show Your Support

If you like this project, consider giving it a ⭐ on GitHub!
