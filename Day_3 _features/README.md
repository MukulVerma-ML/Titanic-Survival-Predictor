# Day 3 - Feature Engineering

Goal: Accuracy 75.42% → 78%+ using domain knowledge

**Model:** Logistic Regression - Same as Day 2 
**Accuracy:** 75.42% → **78.77%** (+3.35%) 
**Kaggle Score:** **0.77990**

**New Features Created:**
1. **Title** - Extracted from `Name`: Mr, Mrs, Miss, Master, Rare
   ```python
   df['Title'] = df['Name'].str.extract(' ([A-Za-z]+)\.', expand=False)
