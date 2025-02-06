# NLP_password_strength
NLP Password Strength analyzes and classifies passwords as weak, medium, or strong using NLP techniques. It processes 1M leaked passwords, applying machine learning to evaluate security based on length, characters, and symbols. The project uses SQLite, pandas, and seaborn for data handling and visualization. 🚀

## Overview
This project analyzes the strength of passwords using natural language processing (NLP) techniques. It classifies passwords into three categories:
- **0**: Weak
- **1**: Medium
- **2**: Strong

The dataset consists of **1 million unique passwords** collected from the 000webhost leak, and the classification is based on predefined rules such as the presence of digits, special symbols, and character combinations.

## Features
- Reads data from an **SQLite database (`password_Data.sqlite`)**.
- Uses NLP techniques to analyze password strength.
- Visualizes password strength distribution using **matplotlib** and **seaborn**.
- Implements machine learning models for password classification.

## Installation
To set up the project, install the required dependencies:

```bash
pip install pandas numpy matplotlib seaborn sqlite3 sklearn
```

## Usage
Run the Jupyter Notebook to analyze and visualize password strength:

```bash
jupyter notebook NLP_password_strength.ipynb
```

## Data Source
The passwords used in this analysis are from the **000webhost data leak**, publicly available online. The dataset is stored in an SQLite database (`password_Data.sqlite`) with a table named `Users`.

## Machine Learning Approach
The project applies machine learning models to classify passwords into different strength levels. It includes:
- Data preprocessing (removing duplicates, handling missing values)
- Feature extraction (length, character diversity, special symbols)
- Model training (Logistic Regression, Random Forest, or Neural Networks)
- Evaluation (accuracy, precision, recall metrics)

## Contributions
Feel free to contribute by:
- Adding more features for password classification.
- Experimenting with different machine learning models.
- Improving data preprocessing and visualization.

## License
This project is open-source under the MIT License.

---
**Author:** Mohammedali Patel

