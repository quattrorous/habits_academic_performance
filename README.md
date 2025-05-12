# habits_academic_performance
## Project Summary

This project investigates whether academic performance can be predicted from self-reported student lifestyle habits. Using a dataset of 1,000 synthetic student profiles, nine regression models were evaluated and compared.

### Models Implemented
- Linear Regression
- Ridge Regression
- Lasso Regression
- Polynomial Regression (degree 2)
- SVR (Linear, RBF, Polynomial Kernels)
- Random Forest Regressor
- K-Nearest Neighbors

### Key Findings
- **Lasso Regression** performed best with a Test RMSE of 5.13.
- Study hours, screen time, sleep, and mental health were top predictors.
- PCA showed that 14 principal components could explain over 90% of the dataset's variance.
- Residual analysis and error quartiles revealed stable model performance across most cases.

## Figures Included
- Numeric & categorical distributions
- Correlation heatmap
- RMSE comparison bar chart
- Residual plot and absolute error spread
- Feature importance bar chart
- PCA explained variance curve
- Preprocessing pipeline flowchart

## Dataset

- Source: [Kaggle – Student Habits vs Academic Performance](https://www.kaggle.com/datasets/jayaantanaath/student-habits-vs-academic-performance)
- Type: Survey dataset
- Size: 1,000 samples, 16 features

## Final Report

 [Read the full report (PDF)](./report/student_habits_report.pdf)

## License

This project is released under the MIT License. Feel free to use, adapt, or build upon it.
