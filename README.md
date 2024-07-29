# Movie Rating Prediction

## Project Overview

This project aims to predict movie ratings based on various features such as movie name, release year, duration, genre, number of votes, director, and leading actors. The dataset includes movies from various genres and years, providing a rich source of information for building predictive models.

## Dataset

The dataset contains the following columns:

- **Name:** Name of the movie.
- **Year:** Release year of the movie.
- **Duration:** Duration of the movie in minutes.
- **Genre:** Genre of the movie.
- **Rating:** IMDb rating of the movie.
- **Votes:** Number of votes the movie received on IMDb.
- **Director:** Director of the movie.
- **Actor 1:** Leading actor/actress in the movie.
- **Actor 2:** Second leading actor/actress in the movie.
- **Actor 3:** Third leading actor/actress in the movie.

## Steps Performed

1. **Data Loading and Initial Exploration**
   - Imported necessary libraries (`pandas`, `numpy`, `matplotlib`, `seaborn`, etc.).
   - Loaded the dataset and performed initial exploration to understand its structure and contents.

2. **Data Cleaning**
   - Handled missing values by:
     - Filling missing numerical values with the median.
     - Filling missing categorical values with the mode or using a placeholder.
     - Converted string columns with numerical information (Year, Duration) to numeric types.
     - Removed or imputed rows/columns with excessive missing values.

3. **Exploratory Data Analysis (EDA)**
   - Used various plots and summary statistics to understand the distribution and relationships between different features.
   - Created visualizations like histograms, scatter plots, and box plots to explore the data.

4. **Feature Engineering**
   - Extracted numerical data from text columns.
   - Created new features based on existing ones to improve model performance.
   - Encoded categorical variables using techniques like one-hot encoding.

5. **Model Building**
   - Split the dataset into training and testing sets.
   - Built several machine learning models to predict movie ratings:
     - Linear Regression
     - Decision Trees
     - Random Forests
     - Gradient Boosting
   - Evaluated the models using metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R² score.

6. **Model Evaluation**
   - Compared model performance using evaluation metrics.
   - Fine-tuned the best-performing model to improve its accuracy and generalizability.

7. **Conclusion and Future Work**
   - Summarized findings and model performance.
   - Suggested potential improvements and future work, such as incorporating additional features, using more advanced models, or gathering more data.

## Results

- The best-performing model was [Model Name], achieving an RMSE of [value] and an R² score of [value].
- The most influential features in predicting movie ratings were [Feature 1], [Feature 2], and [Feature 3].

## Dependencies

- Python 3.x
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `plotly`
- `wordcloud`

## Acknowledgments
Thanks to IMDb for providing the dataset.
Inspired by various online tutorials and documentation on data science and machine learning.
