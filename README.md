# Diabetes Prediction System

## Overview

This project implements a comprehensive Diabetes Prediction System using various machine learning algorithms to classify patients into three categories: Non-Diabetic, Diabetic, and Pre-Diabetic. By comparing different models, we've developed a high-accuracy prediction system that can serve as a screening tool for diabetes risk assessment.

## Models & Performance

| Model                  | Accuracy | Key Features                                 |
|------------------------|----------|----------------------------------------------|
| SVM (app.ipynb)        | 92.96%   | Baseline model with rbf kernel               |
| Enhanced SVM (app1.ipynb) | ~93%   | Improved preprocessing & error handling      |
| Random Forest (app2.ipynb) | 96.98% | Better non-linear handling & interpretability |
| Ensemble (app3.ipynb)  | 97.49%   | Feature engineering & multiple model voting   |

## Dataset

The dataset (`newDiabetes.csv`) contains important clinical parameters:

- **Demographics**: Gender, Age
- **Blood Chemistry**: Urea, Creatinine, HbA1c
- **Lipid Profile**: Cholesterol, TG, HDL, LDL, VLDL
- **Other Metrics**: BMI
- **Target**: CLASS (N: Non-diabetic, Y: Diabetic, P: Pre-diabetic)

## Project Structure

### 1. app.ipynb - Support Vector Machine (SVM)
- Initial approach using SVM classifier
- Basic data preprocessing
- Hyperparameter tuning with GridSearchCV

### 2. app1.ipynb - Enhanced SVM Implementation
- Improved data preprocessing
- Better handling of missing values
- Enhanced prediction capabilities with probabilities

### 3. app2.ipynb - Random Forest Classifier
- Ensemble learning approach
- Improved handling of non-linear relationships
- Better performance on class imbalance

### 4. app3.ipynb - Advanced Ensemble with Feature Engineering
- Feature engineering based on medical domain knowledge
- Feature selection for focusing on most predictive variables
- Voting Classifier combining Random Forest, Gradient Boosting, and Neural Networks
- Achieved highest accuracy (97.49%)

## Key Findings

- **HbA1c** emerged as the most important predictor of diabetes
- **Feature engineering** (especially HbA1c/BMI ratio) significantly improved performance
- **Ensemble methods** outperformed single models consistently
- **Pre-diabetic** class was the most challenging to predict accurately

## Future Improvements

- Implement deep learning models for potentially higher accuracy
- Add explainability features to help interpret predictions
- Develop a web interface for easy use by healthcare professionals
- Expand the dataset and test on external validation datasets

## Requirements

- Python 3.7+
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- xgboost

## Author

[Ravendra Singh](https://github.com/Ravendra1236)

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Diabetes dataset contributors
- Healthcare professionals who provided domain knowledge
- Open source community for machine learning libraries

---

⭐ If you find this project helpful, please consider giving it a star on GitHub!
