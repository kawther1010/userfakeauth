# Predicting User Fake Authentication

This project aims to predict user fake authentication using various machine learning classification models, including Support Vector Machine (SVM), Naive Bayes, Decision Trees, and Random Forest. The dataset includes user features, and the task is to classify whether the authentication is fake.

## Dataset

The dataset contains the following columns:

- `pos`
- `flw`
- `flg`
- `bl`
- `pic`
- `lin`
- `cl`
- `cz`
- `ni`
- `erl`
- `erc`
- `lt`
- `hc`
- `pr`
- `fo`
- `cs`
- `pi`
- `class`

The `class` column is the target variable indicating whether the authentication is fake (binary classification) or belongs to one of the multiple classes (multi-class classification).

## Models Used

1. **Support Vector Machine (SVM)**
2. **Naive Bayes**
3. **Decision Trees**
4. **Random Forest**
5. **Logistic Regression**

## Results

After evaluating the performance of each model, the Random Forest model achieved the best accuracy. The detailed results for each model are as follows:

### Binary Classification
- **Random Forest**
  - Accuracy: 0.89598

### Multi-Class Classification
- **SVM**
  - Accuracy: 0.687
- **Naive Bayes**
  - Accuracy: 0.57
- **Decision Trees**
  - Accuracy: 0.866
- **Logistic Regression**
  - Accuracy: 0.67
- **Random Forest**
  - Accuracy: 0.907
