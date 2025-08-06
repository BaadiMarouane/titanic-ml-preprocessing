# titanic-ml-preprocessing
# Titanic Data Preprocessing for Machine Learning 🚢

This notebook demonstrates the full preprocessing pipeline for a sample of the Titanic dataset, including:

✅ Handling missing values  
✅ Encoding categorical variables (nominal & ordinal)  
✅ Feature scaling (standardization)  
✅ Splitting into train/test sets  
✅ Visualizing the data using graphs

---

## 📁 Files

- `titanic_data_preprocessing.ipynb`: Main Jupyter notebook
- `README.md`: This file

---

## 📊 Visualizations

The notebook includes visual analysis:
- Bar plot of survival counts by gender
- Histogram of age distribution for survivors vs non-survivors

---

## 🛠️ Preprocessing Steps

1. Load and clean the dataset
2. Fill missing values (e.g., Age)
3. One-Hot Encode categorical variables (e.g., Sex, Embarked)
4. Scale numerical features (Age, Fare)
5. Split the dataset into training and testing sets
6. Plot the results

---

## 💡 Requirements

Install the following Python libraries (you can use pip or conda):

```bash
pandas
numpy
scikit-learn
matplotlib
seaborn
