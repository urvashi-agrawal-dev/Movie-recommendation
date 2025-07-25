# 🎬 Movie Recommendation System using Collaborative Filtering

This project is a beginner-friendly Movie Recommendation System built using **Python**, **pandas**, and **Google Colab**. It uses **Item-Based Collaborative Filtering** to suggest movies similar to the ones a user already likes — just like Netflix or Amazon!

---

## 📌 Project Highlights

- ✅ Simple and easy to understand — made for beginners
- ✅ Uses the popular [MovieLens 100k dataset](https://grouplens.org/datasets/movielens/100k/)
- ✅ Built entirely in **Google Colab**
- ✅ No machine learning experience required
- ✅ Optional Streamlit web app version

---

## 🚀 How It Works

The system finds movies that are **most similar in user rating patterns** to a movie you choose.

It follows these steps:

1. Load and merge the dataset
2. Create a user-movie rating matrix
3. Use **Pearson correlation** to find similar movies
4. Filter out movies with low rating counts
5. Return top 10 most similar movie recommendations

---

## 🧠 Techniques Used

- **Collaborative Filtering** (Item-Based)
- **Pivot Tables** with `pandas`
- **Correlation (Pearson)** for similarity
- **Filtering** for reliability
- (Optional) `streamlit` for simple UI

---

## 🗂️ Files Included

- `movie_recommendation.ipynb` – Google Colab notebook with full code and explanations
- `u.data`, `u.item` – MovieLens dataset files (downloaded manually)
- `app.py` *(optional)* – Streamlit web app (if implemented)
- `README.md` – Project description

---

## 📥 Dataset Info

We use the **MovieLens 100k** dataset:
- 100,000 ratings
- 943 users
- 1,682 movies

[🔗 Download MovieLens 100k Dataset](https://grouplens.org/datasets/movielens/100k/)

---

## 📸 Sample Output

Example: Recommendations for **"Star Wars (1977)"**

---

## ⚙️ How to Run

### Option 1: Run in Google Colab (No setup needed)

1. Open the `.ipynb` notebook
2. Upload `u.data` and `u.item` files
3. Run the cells one by one

### Option 2: Run Locally

1. Clone this repo
2. Install dependencies:

