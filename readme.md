# F1 Drivers Analysis

## Description
This project analyzes a dataset of F1 drivers to explore various relationships and build predictive models. The analysis includes visualizations, correlation studies, and binary classification to predict whether a driver can become a champion.

## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/F1DriversAnalysis.git
    cd F1DriversAnalysis
    ```
2. Install the required packages:
    ```bash
    pip install pandas matplotlib plotly seaborn scikit-learn
    ```

## Usage
1. Load the dataset:
    ```python
    df = pd.read_csv("F1DriversDataset.csv")
    ```
2. Run the analysis scripts in the provided Jupyter Notebook or Python scripts.

## Data
The dataset `F1DriversDataset.csv` contains information about F1 drivers, including their nationality, years active, race wins, pole positions, and other relevant statistics.

## Models
The project uses several models to analyze and predict driver performance:
- **Random Forest Regressor**: Used to predict race wins based on years active.
- **Linear Regression**: Analyzes the relationship between pole positions and race wins.
- **SGD Classifier**: Binary classification to predict if a driver is a champion.
- **SVM**: Support Vector Machine for binary classification.
- **Decision Tree**: Binary classification to predict champions.
- **Random Forest Classifier**: Binary classification to predict champions.
- **Gradient Boosting Classifier**: Binary classification to predict champions.

## Results
- **Correlation**: Found a correlation between years active and race wins.
- **Classification**: Decision Tree classifier provided the best prediction for identifying champions with the highest accuracy and F1 score.

## Contributing
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.

## License
This project is licensed under the MIT License.