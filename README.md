# -Iris-Species-Classification-Project
This project performs exploratory data analysis and implements a machine learning model to accurately classify iris flowers based on their measurements.

## Dataset
The Iris dataset contains 150 samples of iris flowers with 4 features:
- Sepal length
- Sepal width
- Petal length
- Petal width  
The target variable is the species: Setosa, Versicolor, or Virginica.

## Project Steps
1. **Data Loading & Cleaning:** Loaded the dataset and checked for missing values.
2. **Exploratory Data Analysis (EDA):**  
   - Descriptive statistics  
   - Visualizations (pairplots, boxplots, correlation heatmap)  
3. **Feature Engineering:** No new features were added as dataset is clean.
4. **Model Building:**  
   - Split data into train and test sets  
   - Scaled features using StandardScaler  
   - Trained a Logistic Regression classifier  
5. **Model Evaluation:**  
   - Accuracy score  
   - Classification report  
   - Confusion matrix

## Technologies & Libraries
- Python 3  
- Pandas  
- Seaborn, Matplotlib  
- Scikit-learn  

## How to Run
1. Clone this repo.  
2. Open the Jupyter Notebook `Iris_Classification.ipynb`.  
3. Run cells sequentially.

## Conclusion
The Logistic Regression model achieved high accuracy in classifying iris species, demonstrating the predictive power of simple features combined with classic ML techniques.

---

**Feel free to reach out if you want to collaborate or ask questions!**

