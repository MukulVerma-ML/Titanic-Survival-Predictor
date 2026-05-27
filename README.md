# IMDB Movie Review Sentiment Analysis 🎬

Classify IMDB movie reviews as Positive or Negative using TF-IDF + Logistic Regression.

**Accuracy: 85.44%** on 10,000 test reviews

### 📊 Results
| Metric | Score |
| --- | --- |
| Accuracy | 85.44% |
| Precision | 0.89 |
| Recall | 0.88 |
| F1-Score | 0.88 |

### 🛠️ Tech Stack
- Python, Pandas, Scikit-learn
- TF-IDF Vectorization 
- Logistic Regression
- Regex for Text Cleaning

### 📂 How to Run
1. Download `IMDB Dataset.csv` from [Kaggle](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)
2. Install requirements: `pip install pandas scikit-learn`
3. Run `main.py` or open `IMDB_Sentiment.ipynb` in Colab
4. Model trains in ~2 minutes on CPU

### 📌 Key Features
1. Text preprocessing: HTML removal, lowercase, noise cleaning
2. TF-IDF with 5000 features for optimal speed/accuracy trade-off
3. Stratified train-test split to maintain class balance
4. Custom prediction function for new reviews


⭐ If you like this project, give it a star!
