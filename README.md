# 🚢 Titanic: Machine Learning from Disaster

7-day hands-on ML challenge to predict passenger survival on the Titanic. 

**🏆 Best Score: 0.78708** | **📊 Rank: Top 15%** on Kaggle Leaderboard

### 🔍 Key Highlights
- **Feature Engineering**: Extracted `Title` from Name, improved accuracy by 2%
- **Models Compared**: RandomForest vs XGBoost with Cross-Validation
- **Best Model**: RandomForestClassifier with GridSearchCV tuning
- **Key Features**: Title, Sex, Pclass, Age, Embarked, Fare

### 📈 Results
| Model | Features | CV Score | Kaggle Score |
| --- | --- | --- | --- |
| Day 6 RF | 5 features | 0.8286 | 0.78708 |
| Day 7 XGB | 4 features | 0.8148 | 0.75119 |

### 🛠️ Tech Stack
`Python` `Pandas` `Scikit-learn` `XGBoost` `Jupyter`

### 🎓 Learnings
1. Feature engineering beats complex models
2. CV score ≠ Kaggle score, watch for overfitting
3. Title is the strongest single feature for Titanic

### 🚀 How to Run
```bash
python day6_final.py
