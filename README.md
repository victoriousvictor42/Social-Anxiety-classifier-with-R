# **Social Anxiety Classifier (R)**

## **Overview**

This project develops a **machine learning classification model** to predict **social anxiety levels** based on a dataset of demographic, lifestyle, and psychological factors. The aim is to analyze how various features (such as sleep, physical activity, and caffeine intake) relate to social anxiety, and to build predictive models that can identify individuals at higher risk.

---

## **Dataset**

The dataset includes multiple dimensions:

* **Demographics:** Age, Gender, Occupation
* **Lifestyle Factors:** Sleep hours, Physical activity, Diet quality, Alcohol use, Caffeine intake, Smoking habits
* **Health & Mental Indicators:** Anxiety level (1–10 scale), Stress levels, Other psychological attributes

---

## **Project Workflow**

1. **Setup & Packages**

   * Install and load R packages such as `ggplot2`, `gridExtra`, `psych`, `GGally`, `janitor`, and `skimr`.

2. **Data Cleaning & Preprocessing**

   * Remove unnecessary columns.
   * Convert categorical (factor) variables into numeric codes.
   * Handle missing values and normalize predictors.
   * Apply transformations using the **`recipes`** package (dummy encoding, normalization, removing zero-variance predictors).

3. **Exploratory Data Analysis (EDA)**

   * Visualize categorical features with countplots.
   * Explore correlations between features using **`ggcorrplot`** and **GGally**.
   * Summarize data distributions and identify key patterns.

4. **Feature Engineering**

   * Encode categorical variables into dummy variables.
   * Scale and normalize numeric variables.
   * Ensure predictors are consistent and suitable for modeling.

5. **Modeling**

   * Train multiple classifiers (e.g., Logistic Regression and Simple Extreme Gradient (XGBoost)models in R).
   * Use training and test data splits for evaluation.

6. **Evaluation**

   * Assess models with metrics such as **accuracy and confusion matrix**.
   * Compare models to determine the most effective approach for predicting social anxiety.

---

## **Dependencies**

The notebook uses the following R packages:

* `ggplot2`
* `gridExtra`
* `psych`
* `ggcorrplot`
* `GGally`
* `magrittr`
* `janitor`
* `skimr`
* `recipes`
* `caret` (likely for model training and evaluation)

Install them in R with:

```r
install.packages(c("ggplot2", "gridExtra", "psych", "ggcorrplot", 
                   "GGally", "magrittr", "janitor", "skimr", "recipes", "caret"))
```

---

## **Results**

* Preprocessed and cleaned the dataset for reliable modeling.
* Built classification models capable of predicting **social anxiety levels**.
* Identified **key lifestyle and behavioral factors** influencing anxiety risk (e.g., sleep, caffeine, stress).

---

## **Author**

**Victor Mwenda Kinyua**

