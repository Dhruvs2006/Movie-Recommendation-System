# 🎬 Movie Recommendation System

A **Movie Recommendation System** built with **Python** and **Streamlit** that recommends movies based on content similarity. The application uses machine learning techniques to analyze movie metadata and suggest similar movies through a simple and interactive web interface.

---

## 📌 Features

- 🎥 Content-based movie recommendations
- 🔍 Easy movie selection using a dropdown menu
- ⭐ Displays top similar movies
- 🖼️ Movie poster support (using TMDb API)
- ⚡ Fast recommendations with a precomputed similarity matrix
- 🎨 User-friendly Streamlit interface

---

## 🛠️ Tech Stack

- Python
- Streamlit
- Pandas
- NumPy
- Scikit-learn
- Pickle
- Requests
- TMDb API (Optional)

---

## 📂 Project Structure

```
movie-recommendation-system/
│── app.py                  # Streamlit application
│── movies.pkl              # Processed movie dataset
│── similarity.pkl          # Similarity matrix
│── requirements.txt        # Project dependencies
│── README.md               # Project documentation
│── notebook.ipynb          # Model development notebook
│── posters/                # Movie posters (optional)
```

---

## 🚀 How It Works

The recommendation system follows these steps:

1. Load the movie dataset.
2. Clean and preprocess the data.
3. Combine important features such as genres, cast, crew, keywords, and overview.
4. Convert the text into numerical vectors using **CountVectorizer**.
5. Calculate similarity scores using **Cosine Similarity**.
6. Store the similarity matrix for fast recommendations.
7. Recommend the top similar movies based on the selected movie.

---

## 📊 Dataset

This project uses the **TMDb 5000 Movie Dataset**, which includes:

- Movie Title
- Genres
- Cast
- Crew
- Keywords
- Overview
- Popularity
- Ratings

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/movie-recommendation-system.git
cd movie-recommendation-system
```

### 2. Create a Virtual Environment (Optional)

**Windows**

```bash
python -m venv venv
venv\Scripts\activate
```

**Linux/macOS**

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Run the Application

```bash
streamlit run app.py
```

After running the above command, Streamlit will open the application in your default web browser.

---

## 💻 Usage

1. Open the Streamlit application.
2. Select a movie from the dropdown menu.
3. Click the **Recommend** button.
4. View the list of recommended movies.
5. If TMDb API integration is enabled, movie posters will also be displayed.

---

## 📦 Requirements

```
streamlit
pandas
numpy
scikit-learn
requests
```

Install all dependencies with:

```bash
pip install -r requirements.txt
```

---

## 📈 Future Enhancements

- Collaborative Filtering
- Hybrid Recommendation System
- User Authentication
- Movie Ratings & Reviews
- Personalized Recommendations
- Watchlist Feature
- Trending Movies Section
- Genre-Based Filtering
- Streamlit Cloud Deployment

---

## 📸 Screenshots

Add screenshots of your application here.

```
screenshots/home.png
screenshots/recommendation.png
```

---

## 🎯 Sample Recommendation

**Selected Movie:**

```
Avatar
```

**Recommended Movies:**

```
Guardians of the Galaxy
John Carter
Star Trek
Aliens
The Fifth Element
```

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository.
2. Create a new branch.

```bash
git checkout -b feature-name
```

3. Commit your changes.

```bash
git commit -m "Added a new feature"
```

4. Push your branch.

```bash
git push origin feature-name
```

5. Open a Pull Request.

---

## 📄 License

This project is licensed under the **MIT License**.

---

## 🙏 Acknowledgements

- TMDb 5000 Movie Dataset
- Streamlit
- Scikit-learn
- Pandas
- NumPy

---

## 👨‍💻 Author

**Your Name**

GitHub: https://github.com/yourusername

If you found this project helpful, don't forget to ⭐ star the repository!
