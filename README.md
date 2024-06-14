# Data Leakage Prevention

## Project Overview

This project provides a robust pipeline for data analysis and machine learning, specifically designed to prevent data leakage. It includes data preprocessing, model training, evaluation, and visualization, nsuring a comprehensive approach to handling data securely.

## Table of Contents

- [Project Overview](#project-overview)
- [Table of Contents](#table-of-contents)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Data Description](#data-description)
- [Preprocessing](#preprocessing)
- [Model Training and Evaluation](#model-training-and-evaluation)
- [Visualization](#visualization)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Features

- Robust data preprocessing including handling of missing values and scaling.
- Categorical data encoding.
- Machine learning model training and evaluation using Random Forest.
- Cross-validation for model robustness.
- Visualization of confusion matrix and feature importances.
- Correlation matrix heatmap for data analysis.
- Data leakage prevention throughout the pipeline.

## Installation

1. Clone the repository:
    ```sh
    git clone [https://github.com/GaddamVarshith/Data_Leakage_Protection_using_MachineLearning.git](https://github.com/GaddamVarshith/Data_Leakage_Protection_using_MachineLearning.git)
    ```

2. Navigate to the project directory:
    ```sh
    cd Data_Leakage_Protection_using_MachineLearning
    ```

3. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. Place your dataset file (`data.csv`) in the project directory.

2. Run the script:
    ```sh
    python Data_leakage_protection.py
    ```

3. The script will:
   - Load the data.
   - Preprocess the data.
   - Split the data into training and test sets to prevent data leakage.
   - Train a Random Forest model.
   - Evaluate the model.
   - Generate and display visualizations.

## Data Description

The dataset `data.csv` contains the following columns:
- `ID`: Identifier for each entry.
- `Gender`: Categorical feature representing gender.
- `Purchased`: Indicator if the item was purchased.
- `Review`: Text review of the item.
- `Target`: Target variable for machine learning.

## Preprocessing

The preprocessing pipeline includes:
- Handling missing values with `SimpleImputer`.
- Scaling numerical features with `StandardScaler`.
- Encoding categorical features with `OneHotEncoder`.

## Model Training and Evaluation

- The model is a `RandomForestClassifier`.
- Cross-validation is performed to ensure robustness.
- The model's accuracy and other metrics are reported.
- Confusion matrix and classification report provide detailed evaluation.

## Visualization

- **Confusion Matrix**: Shows the performance of the classification model.
- **Feature Importances**: Displays the importance of each feature in the model.
- **Correlation Matrix**: Provides insight into the relationships between numerical features.

## Contributing

Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create your feature branch: `git checkout -b feature/your-feature-name`.
3. Commit your changes: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature/your-feature-name`.
5. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


