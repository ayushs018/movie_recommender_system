# movie_recommender_system

# Movie Recommender System

## 📌 Project Overview
This **Movie Recommender System** suggests movies similar to a given input movie using a **content-based filtering approach**. It analyzes metadata like genres, cast, crew, and keywords to generate recommendations. The project leverages **machine learning techniques** such as **TF-IDF Vectorization** and **Cosine Similarity** for efficient recommendations.

## 🚀 Features
- **Content-Based Filtering**: Recommends movies based on metadata like genres, cast, and keywords.
- **Machine Learning Integration**: Uses **TF-IDF** and **cosine similarity** for similarity calculations.
- **Efficient Data Processing**: Preprocessed and optimized movie metadata for accurate results.
- **Pickle Serialization**: Saves trained models (`movie_list.pkl`, `similarity.pkl`) for fast deployment.

## 📂 Dataset
The dataset contains movie metadata, including:
- **Genres** (e.g., Action, Adventure, Fantasy)
- **Keywords** (e.g., space war, time travel, superhero)
- **Cast & Crew** (e.g., Actors and Directors)
- **Movie Overview** (Brief description of each movie)

## 🛠️ Technologies Used
- **Python**
- **Pandas, NumPy** (Data Processing)
- **Scikit-learn** (Machine Learning - TF-IDF, Cosine Similarity)
- **Natural Language Processing (NLP)**

## 🔧 Installation & Usage
### 1️⃣ Clone the repository:
```bash
https://github.com/your-username/movie-recommender.git
cd movie-recommender
```

### 2️⃣ Install dependencies:
```bash
pip install -r requirements.txt
```

### 3️⃣ Run the script:
```bash
python recommend.py
```

### 4️⃣ Get Movie Recommendations:
In the script, call the `recommend()` function with a movie title:
```python
recommend('Inception')
```

## 📌 Example Output
```
Movies similar to Inception:
1. The Matrix
2. Interstellar
3. The Prestige
4. Shutter Island
5. Memento
```

