🎬 Movie Recommender System


A Movie Recommendation System built using Python, Machine Learning, and Streamlit that suggests similar movies based on content similarity.
The system uses a content-based filtering approach and integrates the TMDB API to display movie posters, ratings, release dates, and descriptions.

This project demonstrates how machine learning techniques can be used to build an interactive recommendation system for users.

🚀 Features

✅ Recommend similar movies based on user selection
✅ Content-based filtering using similarity matrix
✅ Movie posters and details fetched from TMDB API
✅ Interactive Streamlit web application
✅ Displays movie rating, overview, and release date
✅ Fast recommendation using precomputed similarity matrix

🧠 How the Recommendation System Works

The system uses Content-Based Filtering.

A dataset of movies is processed.
Movie features (like genres, keywords, etc.) are analyzed.
A similarity matrix is created using machine learning techniques.
When a user selects a movie, the system:
Finds the similarity score
Returns the top 5 most similar movies
🛠️ Tech Stack
Technology	Purpose
Python	Core programming language
Pandas	Data processing
Streamlit	Web application framework
Pickle	Model/data storage
Requests	API calls
TMDB API	Movie metadata and posters
📂 Project Structure
movie-recommender-system
│
├── app.py
│
├── data
│   ├── movie_dict.pkl
│   └── similarity_matrix.pkl
│
├── assets
│   └── app_demo.png
│
├── requirements.txt
├── README.md
└── .gitignore
▶️ Installation and Setup
1️⃣ Clone the repository
git clone https://github.com/yourusername/movie-recommender-system.git
2️⃣ Navigate to project folder
cd movie-recommender-system
3️⃣ Install dependencies
pip install -r requirements.txt
4️⃣ Run the Streamlit application
streamlit run app.py
🎥 How to Use
Open the Streamlit app in your browser.
Select a movie from the dropdown menu.
Click "Get Recommendations".
The system will display 5 similar movies with posters and details.
📸 Application Preview

(Add a screenshot of your Streamlit app here)

assets/app_demo.png
🔗 API Used

This project uses the TMDB (The Movie Database) API to fetch:

Movie Posters
Ratings
Overview
Release Date

Website: https://www.themoviedb.org/

📊 Future Improvements

🚀 Improve recommendation accuracy using deep learning
🚀 Add collaborative filtering
🚀 Add user login and watch history
🚀 Deploy application on cloud (Streamlit / AWS / Heroku)
🚀 Add search functionality

👨‍💻 Author

Alok Kumar

Data Science Student
Passionate about Machine Learning, AI, and Data Science

⭐ Support

If you like this project, please consider giving it a star ⭐ on GitHub.
