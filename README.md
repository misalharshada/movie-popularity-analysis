# Movie Popularity Analysis and Prediction

## 📌 Project Overview
This project focuses on analyzing movie data using Exploratory Data Analysis (EDA) and predicting movie popularity using Machine Learning. It explores movie genres, ratings, popularity, vote counts, and other features to understand patterns in the dataset.

## 🎯 Objectives
- Analyze movie data using Python.
- Clean and preprocess the dataset.
- Explore movie genres, ratings, languages, and popularity.
- Visualize patterns and relationships in movie data.
- Build a Machine Learning model to predict movie popularity.

## 🛠️ Technologies Used
- **Python**
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualization
- **Scikit-learn** – Machine Learning

## 📊 Project Workflow
1. Load and understand the dataset.
2. Clean the data and handle missing values.
3. Perform Exploratory Data Analysis (EDA).
4. Create visualizations to identify patterns and relationships.
5. Encode categorical and date-related features.
6. Train a Random Forest Regressor.
7. Evaluate the model using MAE, RMSE, and R² score.
8. Compare actual and predicted movie popularity.

## 🔍 Key Analysis
- Distribution of movie popularity and ratings.
- Most common movie genres.
- Distribution of movies by original language.
- Relationship between vote count and popularity.
- Correlation analysis between numerical features.
- Identification of potential outliers.

## 🤖 Machine Learning Model
A **Random Forest Regressor** is used to predict movie popularity based on the available movie features.

**Evaluation metrics:**
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

The model's performance can be assessed using these metrics after running the notebook.

## 📁 Project Structure

```text
movie-popularity-analysis/
├── Movie.ipynb
└── README.md
```

**Note:** The dataset (`mymoviedb.csv`) is not included in this repository. Download the dataset from its original source and place it in the project folder before running the notebook.

## 🚀 How to Run the Project

1. Clone or download this repository.
2. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

3. Download the dataset and place `mymoviedb.csv` in the same folder as `Movie.ipynb`.
4. Open the notebook:

```bash
jupyter notebook Movie.ipynb
```

5. Run the cells in order.

## 🔮 Future Improvements
- Improve feature engineering and model performance.
- Compare Random Forest with other regression algorithms.
- Add an interactive dashboard for movie data analysis.
- Include additional movie features for better predictions.

## 👩‍💻 Author
**Harshada Misal**

