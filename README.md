Water Quality Pollution Classification

Overview

In this project, I worked on classifying water pollution levels using basic chemical parameters like nitrates and phosphates. The idea was to see how simple machine learning models can help identify whether a water sample is polluted or not.

---

Dataset

The dataset used in this project consists of environmental measurements related to water quality, including nitrate and phosphate concentrations.

Due to data ownership and access restrictions, the full dataset cannot be publicly shared. For this project, a subset of the data was used for demonstration and learning purposes.

The focus of this work is on applying machine learning techniques rather than on the dataset itself.

---

Problem

This is a simple classification problem where:

- 0 = Low pollution
- 1 = High pollution

I created the pollution label based on nitrate levels, which is a common indicator in environmental studies.

---

What I did

Data preparation

- Selected relevant columns (nitrates and phosphates)
- Converted data to numeric format
- Removed missing values

Feature creation

- Created a pollution column based on nitrate threshold
- Checked how balanced the dataset is

---

Models used

Logistic Regression

I used this as a baseline model because it’s simple and easy to interpret.

Random Forest

Then I used Random Forest to see if a more powerful model improves performance by capturing non-linear relationships.

---

Results

- Logistic Regression Accuracy: ~0.78
- Random Forest Accuracy: 1.00

The Random Forest performed very well, but since the dataset is small, this might be overfitting.

---

Observations

- Nitrates have a strong influence on pollution classification
- The dataset is slightly imbalanced
- High accuracy doesn’t always mean the model is reliable

---

Visualizations

- Scatter plot of nitrates vs phosphates
- Comparison of model performance

---

Tools & Libraries

- Python
- Pandas
- Scikit-learn
- Matplotlib

---

Future Improvements

- Use a larger dataset
- Include more environmental parameters
- Try deep learning models (Keras)

---

About me
-I am currently building my skills in ML and applying them to specifically environmental data.

I’m currently building my skills in machine learning and applying them to environmental data.
