# Anime Data Analysis

This project focuses on cleaning and analyzing anime data, as well as applying machine learning models to predict anime ratings. The dataset includes various details about anime, such as title, genre, type, episodes, rating, and more.

## Data Preprocessing

The preprocessing steps include:

1. **Importing Libraries**:
   - `pandas`, `numpy`, `matplotlib.pyplot`, `seaborn`, `os`.

2. **Data Cleaning**:
   - Handling missing values by filling them with appropriate substitutes.
   - Removing duplicates.
   - Splitting the 'genre' column into separate rows and stripping whitespace.

3. **Data Analysis**:
   - Finding the total number of anime.
   - Identifying the highest-rated anime.
   - Counting the number of anime in the 'Action' genre.

4. **Data Visualization**:
   - Creating a bar chart of the top 10 highest-rated anime.

## Machine Learning

Steps involved in the machine learning process:

1. **Reading and Cleaning Rating Data**:
   - Handling problematic lines in the dataset.
   - Removing duplicates.

2. **Feature Engineering**:
   - Aggregating ratings by anime ID.

3. **Data Splitting**:
   - Splitting data into training and test sets.

4. **Scaling Features**:
   - Scaling features using MinMaxScaler.

5. **Model Training and Evaluation**:
   - Training K-Nearest Neighbors (KNN) and Decision Tree classifiers.
   - Evaluating models using confusion matrices, classification reports, and various metrics (recall, precision, accuracy, F1 score).

6. **Hyperparameter Tuning**:
   - Using GridSearchCV to find the best hyperparameters for KNN.

7. **ROC Curve and AUC**:
   - Plotting ROC curve and calculating AUC score.

## Files in the Repository

- `anime_data.xlsx`: Cleaned and processed anime data.
- `rating.csv`: Original rating data.
- `README.md`: This file.
- `ABOUT.md`: Detailed information about the project.

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/anime-data-analysis.git
