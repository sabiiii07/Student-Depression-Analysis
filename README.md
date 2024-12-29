# Student Depression Project

This repository contains a project notebook that explores, analyzes, and models data related to student dependencies. The primary focus is on understanding trends and building predictive models.

## File Structure

- **`Student_dep_proj.ipynb`**: The main Jupyter Notebook containing the code, analysis, and results.

## Dependencies

The following Python libraries are used in this project:

- `pandas`: Data manipulation and analysis.
- `matplotlib`: Data visualization.
- `lightgbm`: Gradient boosting framework for predictive modeling.
- `scikit-learn`: Machine learning library for model training, evaluation, and optimization.

## Project Overview

1. **Data Preprocessing**:
   - Load and clean the dataset.
   - Split the data into training and testing sets.

2. **Exploratory Data Analysis (EDA)**:
   - Visualize data trends and distributions.

3. **Modeling**:
   - Train a predictive model using LightGBM.
   - Perform hyperparameter optimization with `GridSearchCV`.

4. **Evaluation**:
   - Evaluate model performance on test data.
   - Analyze results and insights.

## How to Run

1. Clone this repository and navigate to the directory.
2. Install dependencies:
   ```bash
   pip install pandas matplotlib lightgbm scikit-learn
   ```
3. Open the notebook:
   ```bash
   jupyter notebook Student_dep_proj.ipynb
   ```
4. Execute the notebook cells sequentially.

## Results

The notebook includes detailed outputs of the exploratory analysis and the model's performance metrics. Visualizations are embedded for better understanding.

## Contributing

Contributions are welcome! If you'd like to improve this project, please fork the repository and submit a pull request.
