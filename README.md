"# MovieMind – AI Driven Movie Discovery Platform" 
🎬 MovieMind – AI Driven Movie Discovery Platform
MovieMind – AI Driven Movie Discovery Platform is an intelligent movie recommendation system designed to help users discover movies based on their interests. The system uses content-based filtering techniques such as TF-IDF text similarity and genre-based recommendations to provide accurate and personalized movie suggestions.

The platform integrates real-time movie data from the TMDB API, allowing users to search for movies, view detailed information (such as overview, genres, and posters), and receive recommendations for similar movies. The backend is built using FastAPI to ensure fast and scalable API responses, while the frontend is developed using Streamlit to provide an interactive and user-friendly interface.

MovieMind demonstrates the practical application of machine learning, API integration, and full-stack development, making it suitable for academic projects, portfolios, and real-world deployment.
🚀 Live Demo

Frontend (Streamlit):
👉 https://moviemind0.streamlit.app

Backend (FastAPI on Render):
👉 https://movie-recommendation-s49e.onrender.com

🧠 Features

🔍 Movie search with autocomplete (TMDB)

🎯 Content-based recommendations using TF-IDF

🎭 Genre-based movie suggestions

📄 Detailed movie information (overview, genres, posters)

⚡ FastAPI backend with clean REST APIs

🎨 Interactive Streamlit UI

🛠️ Tech Stack

Frontend: Streamlit

Backend: FastAPI

Machine Learning: TF-IDF, Scikit-learn

Data: TMDB API

Deployment: Streamlit Cloud & Render

Language: Python 3.10

📂 Project Structure
MovieMind-AI-Driven-Movie-Discovery-Platform/
│
├── app.py                # Streamlit frontend
├── main.py               # FastAPI backend
├── df.pkl                # Movie dataset
├── tfidf.pkl             # TF-IDF vectorizer
├── tfidf_matrix.pkl      # TF-IDF matrix
├── indices.pkl           # Index mapping
├── requirements.txt
├── runtime.txt           # Python version for Streamlit
└── README.md

▶️ Run Project Locally
1️⃣ Clone Repository
git clone https://github.com/surya323-ma/MovieMind-AI-Driven-Movie-Discovery-Platform.git
cd MovieMind-AI-Driven-Movie-Discovery-Platform

2️⃣ Create Virtual Environment (Recommended)
conda create -n moviemind python=3.10 -y
conda activate moviemind

3️⃣ Install Dependencies
pip install -r requirements.txt

4️⃣ Setup Environment Variables

Create a .env file:

TMDB_API_KEY=your_tmdb_api_key_here

5️⃣ Run Backend (FastAPI)
uvicorn main:app --reload


Backend will start at:

http://127.0.0.1:8000

6️⃣ Run Frontend (Streamlit)
streamlit run app.py


Frontend will open at:

http://localhost:8501

🌐 Deployment Notes
Streamlit Cloud

Uses Python 3.10 (via runtime.txt)

Frontend connects to Render backend:

API_BASE = "https://movie-recommendation-s49e.onrender.com"

Render (FastAPI)

Backend serves movie data and recommendations

Handles TMDB API securely

🔐 Environment Variables
Variable	Description
TMDB_API_KEY	TMDB API key
📌 Future Improvements

🔐 User authentication

🤖 Collaborative filtering

📊 User preference learning

🎞️ Trailer integration

👨‍💻 Author

Surya
GitHub: https://github.com/surya323-ma

⭐ If you like this project

Give it a ⭐ on GitHub — it really helps!

✅ EXTRA: One-Line Run Commands (Quick Start)
uvicorn main:app --reload
streamlit run app.py
