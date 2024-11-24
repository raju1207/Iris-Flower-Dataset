# Iris-Flower-Dataset

The Iris Dataset is a classic dataset used in machine learning and statistics, especially for classification and pattern recognition tasks. It contains measurements of iris flowers from three species: Iris-setosa, Iris-versicolor, and Iris-virginica.

## Dataset Overview

- **File Name:** ``IRIS.csv``
- **Number of Samples:** 150
- **Features:**
  - ``sepal_length``(float): Sepal length in cm
  - ``sepal_width`` (float): Sepal width in cm
  - ``petal_length``(float): Petal length in cm
  - ``petal_width`` (float): Petal width in cm
  - ``species``    (string): Iris species (Iris-setosa, Iris-versicolor, Iris-virginica)

## Data Summary

- **Total Entries:** 150
- **Feature Types:** 4 numerical features, 1 categorical label
- **No Missing Values:** All values are present and complete.

## Feature Statistics

|**Feature**	| **Mean**	| **Std Dev**	| **Min**	| **Max** |
|-------------|-----------|-------------|---------|---------|
|Sepal Length	|5.843	    |0.828	      |4.3	    |7.9      |
|Sepal Width	|3.054	    |0.434	      |2.0	    |4.4      |
|Petal Length	|3.759	    |1.764	      |1.0	    |6.9      |
|Petal Width	|1.199	    |0.763	      |0.1	    |2.5      |

## Applications

This dataset is ideal for:
- **Classification Tasks:** Predicting species based on flower measurements.
- **Data Visualization:** Exploring relationships between features.
- **Statistical Analysis:** Understanding variations within and between species.

## How to Use
 1. Clone this repository:
    
    ``git clone https://github.com/your-username/iris-dataset.git``
    
 3. Load the dataset in your preferred programming environment:

      ``import pandas as pd``
    
     ``data = pd.read_csv("IRIS.csv")``
 
 3. Explore and analyze the data to uncover insights!

## License
This dataset is publicly available and commonly used in educational and research contexts. It is originally sourced from the UCI Machine Learning Repository.
