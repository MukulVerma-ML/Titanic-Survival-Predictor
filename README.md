# Day 4: Titanic Competition - Feature Engineering + Kaggle Submission 🚢

**Date**: 19 Oct 2026 | **Kaggle Score: 0.78229** | **Rank: Top 25%**

---

## ✅ What I Did Today

1. **Kaggle Setup**: Joined the Titanic competition
2. **Feature Engineering**: 
   - Extracted `Title` from `Name` using regex
   - Created `FamilySize = SibSp + Parch + 1`
3. **Model Training**: Built model using `RandomForestClassifier`
4. **Validation**: Got 81.01% accuracy using 80-20 train-test split
5. **Kaggle Submission**: Uploaded `submission_day4.csv` → **Scored 0.78229**

---

## 📚 What I Learned Today

| Concept | Key Takeaway |
| --- | --- |
| **Feature Engineering** | Creating new features improved score by 1.5% |
| **Domain Knowledge** | `Title` like Mr/Master/Miss heavily impacts survival |
| **Label Encoding** | Converted `Sex` and `Title` to 0,1,2 for ML model |
| **Overfitting Check** | Validation 81% vs Kaggle 78.2% = Good generalization |
| **Kaggle Workflow** | Full cycle: Join → Download → Predict → Submit → Leaderboard |

---

## 🛠️ What I Built Today

**Files Created:**
1. `titanic_day4.ipynb` - Complete code with EDA + Model + Predictions
2. `submission_day4.csv` - Final file submitted to Kaggle

**Model Pipeline:**
