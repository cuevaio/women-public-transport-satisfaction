# Public Transport Survey Analysis

This project simulates and analyzes public transport survey data using machine learning techniques. It generates synthetic survey responses, builds a decision tree classifier to predict user satisfaction, and provides tools for scenario analysis.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Installation](#installation)
3. [Usage](#usage)
4. [File Descriptions](#file-descriptions)
5. [Interpreting Results](#interpreting-results)
6. [Contributing](#contributing)
7. [License](#license)

## Project Overview

This project consists of four main parts:
1. Generating synthetic survey data
2. Creating and training a decision tree classifier
3. Visualizing the decision tree
4. Simulating scenarios to predict user satisfaction

The analysis aims to understand factors influencing public transport user satisfaction and provide insights for improving services.

## Installation

To run this project, you need Python 3.7+ and the following libraries:
- pandas
- numpy
- scikit-learn
- matplotlib

You can install these dependencies using pip:

```
pip install pandas numpy scikit-learn matplotlib
```

## Usage

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/public-transport-survey-analysis.git
   cd public-transport-survey-analysis
   ```

2. Run the main script:
   ```
   python main.py
   ```

   This will generate the survey data, train the model, create visualizations, and run scenario simulations.

3. Check the output files:
   - `survey_responses.csv`: Generated survey data
   - `decision_tree.png`: Visualization of the decision tree
   - `feature_importances.png`: Bar chart of feature importances

## File Descriptions

- `main.py`: The main script containing all parts of the analysis
- `survey_responses.csv`: Generated synthetic survey data
- `decision_tree.png`: Visualization of the trained decision tree
- `feature_importances.png`: Bar chart showing the importance of each feature

## Interpreting Results

1. **Survey Data Generation**:
   - The `survey_responses.csv` file contains simulated responses to a public transport survey.
   - This data serves as a basis for the machine learning model.

2. **Model Accuracy**:
   - The script outputs train and test accuracies.
   - High accuracies (>0.7) indicate a well-performing model.
   - Similar train and test accuracies suggest good generalization.

3. **Decision Tree Visualization** (`decision_tree.png`):
   - Shows the structure of the model's decision-making process.
   - Each node represents a decision based on a feature.
   - Analyze the tree to understand key decision points affecting satisfaction.

4. **Scenario Simulations**:
   - The script runs predefined scenarios and predicts user satisfaction.
   - Use these to understand how different factors influence satisfaction predictions.

5. **Feature Importances** (`feature_importances.png`):
   - Bar chart showing the relative importance of each feature.
   - Taller bars indicate more influential features in predicting satisfaction.
   - Use this to identify key areas for improving public transport services.

## Contributing

Contributions to this project are welcome! Please fork the repository and submit a pull request with your proposed changes.

## License

This project is licensed under the MIT License - see the LICENSE file for details.
