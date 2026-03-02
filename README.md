# Exploring-and-Visualizing-a-Simple-Dataset
# Iris Flower Classification & EDA

## Task Objective
The goal of this project is to perform an Exploratory Data Analysis (EDA) on the Iris dataset and build a machine learning pipeline to classify species based on physical measurements. This includes:
* Data cleaning and inspection.
* Visualizing distributions and relationships between features.
* Training a classification model to predict flower species.

## Dataset Used
The **Iris Dataset** consists of 150 samples of Iris flowers from three different species:
1. **Setosa**
2. **Versicolor**
3. **Virginica**

Each sample includes four features:
* Sepal Length (cm)
* Sepal Width (cm)
* Petal Length (cm)
* Petal Width (cm)

## Models Applied
For this analysis, we utilized:
* **Exploratory Tools:** `Pandas` for data manipulation, `Seaborn` and `Matplotlib` for visualization.
* **Machine Learning:** A **Random Forest Classifier** was used to train the model, utilizing an 80/20 train-test split to ensure accuracy on unseen data.

## Key Results and Findings
* **Setosa is Distinct:** The exploratory scatter plots clearly show that the *Setosa* species is completely separable from the other two species, particularly when looking at petal length.
* **Feature Importance:** Petal measurements (length and width) were found to be the most significant indicators for species classification.
* **Model Performance:** The model achieved high accuracy (typically >95%), with slight overlap observed only between the *Versicolor* and *Virginica* species due to their similar physical dimensions.
* **Outliers:** Box plots revealed minimal outliers in the dataset, indicating high-quality data.
