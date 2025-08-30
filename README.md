

### Titanic Survival Prediction

This project marks my first foray into a Kaggle competition. It was a great learning experience, and the goal was to apply machine learning techniques to predict passenger survival on the Titanic.

-----

### 💻 Technologies Used

  * **Python**
  * **Jupyter Notebook**
  * **Libraries**: `pandas`, `numpy`, `matplotlib`, `seaborn`, and `scikit-learn`

-----

### 🚀 Overview & Key Features

The project is contained within a single Jupyter Notebook (`titanic_kaggle.ipynb`). It follows a standard data science workflow:

1.  **Data Exploration**: I started by exploring the `train.csv` and `test.csv` datasets to understand the features and identify missing values.
2.  **Data Preprocessing**: I cleaned the data by handling missing values and converting categorical features like `Sex` and `Embarked` into a numerical format.
3.  **Model Building**: I trained two different classification models: `Logistic Regression` and `Random Forest Classifier`.
4.  **Hyperparameter Tuning**: I used `GridSearchCV` to find the best settings for the Random Forest model to improve its accuracy.
5.  **Prediction**: The final model was used to predict survival for the test set, and the results were saved to a `predictions.csv` file.

-----

### ▶️ Setup & Usage

To run this notebook, follow these steps:

1.  Clone the repository (if this were a real repo):
    ```bash
    git clone [repository_url]
    ```
2.  Install the necessary libraries:
    ```bash
    pip install pandas numpy scikit-learn matplotlib seaborn
    ```
3.  Download the `train.csv` and `test.csv` files from the official [Kaggle Titanic competition page](https://www.kaggle.com/c/titanic/data) and place them in the same directory as the notebook.
4.  Open the `titanic_kaggle.ipynb` file in a Jupyter environment and run all the cells.

This will run the entire analysis and generate the `predictions.csv` file.
