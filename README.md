# Molecular-Solubility-Prediction-Using-Machine-Learning

This repository contains a machine learning project focused on predicting molecular solubility (`logS`) based on various chemical descriptors. The dataset consists of molecular properties such as lipophilicity (`MolLogP`), molecular weight (`MolWt`), the number of rotatable bonds (`NumRotatableBonds`), and the aromatic proportion of the molecule.

## Project Overview

The goal of this project is to develop a machine learning model to accurately predict the solubility (`logS`) of molecules using the provided chemical descriptors. This can have important applications in pharmaceutical research, material science, and chemical engineering.

### Dataset

The dataset used in this project contains 1,144 entries with the following columns:

- `MolLogP`: Logarithm of the partition coefficient between n-octanol and water (a measure of lipophilicity).
- `MolWt`: Molecular weight of the compound.
- `NumRotatableBonds`: The number of rotatable bonds in the molecule.
- `AromaticProportion`: The proportion of the molecule that is aromatic.
- `logS`: The logarithm of the solubility in water, which is the target variable for prediction.

### Workflow

1. **Data Preprocessing**: Handle missing values, scaling, and feature selection.
2. **Exploratory Data Analysis (EDA)**: Analyze the relationships between molecular descriptors and solubility.
3. **Model Development**: Train different machine learning models such as linear regression, random forest, and others to predict solubility.
4. **Model Evaluation**: Evaluate model performance using metrics like Mean Absolute Error (MAE) and R-squared.

### Requirements

- Python 3.x
- pandas
- scikit-learn
- numpy
- matplotlib
- seaborn

### Installation

To install the required dependencies, run:

```bash
pip install -r requirements.txt
```

### Usage

1. Clone this repository:

```bash
git clone https://github.com/yourusername/solubility-prediction.git
```

2. Navigate to the project directory:

```bash
cd solubility-prediction
```

3. Run the Jupyter notebook or Python scripts to train the model and make predictions.

### Results

The results of the best-performing model will be displayed in the form of performance metrics and visualizations of predicted vs. actual solubility values.

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

### Contributing

Contributions are welcome! Please open an issue or submit a pull request.

