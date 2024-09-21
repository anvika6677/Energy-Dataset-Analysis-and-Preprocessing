# Energy Dataset Analysis and Preprocessing

## Project Overview

This project focuses on the exploration, cleaning, and analysis of an energy dataset. Various data preprocessing techniques, including handling missing values, removing duplicates, identifying numerical and categorical features, and performing data visualization, are implemented to better understand the dataset. Key statistical insights are derived using descriptive statistics and correlation matrices. This project is implemented in Python, utilizing libraries like pandas, NumPy, Matplotlib, Seaborn, and SciPy.

## Project Structure

- **Data Cleaning**: 
  - Loaded dataset and inspected its structure using `.head()`, `.tail()`, `.shape()`, and `.info()` functions.
  - Removed duplicate rows using the `drop_duplicates()` function.
  - Handled missing data by calculating the percentage of missing values and dropping columns with more than 40% null values.
  
- **Data Exploration**:
  - Descriptive statistics generated using the `.describe()` method to summarize central tendency, distribution, and shape of the dataset.
  - Calculated unique values in each column to identify categorical and numerical variables.
  
- **Categorizing Attributes**: 
  - Implemented a custom function to categorize features into discrete, continuous, categorical, and numerical based on their types.

- **Skewness Calculation**: 
  - Calculated skewness for each numerical column to identify asymmetry in data distribution using the `scipy.stats.skew()` function.

- **Correlation Analysis**: 
  - Generated a correlation matrix for the numerical columns to identify relationships between variables.

- **Data Visualization**:
  - Histograms: Visualized the distribution of numerical attributes using the `.hist()` function.
  - Boxplots: Created boxplots to visualize the spread and detect outliers in the numerical columns.
  
## Technologies Used

- **Python**: The primary programming language used in this project.
- **pandas**: For data manipulation and analysis.
- **NumPy**: For numerical computing.
- **Matplotlib**: For data visualization.
- **Seaborn**: For enhanced data visualization.
- **SciPy**: For statistical analysis.
  
## Installation

1. Clone the repository:
   
   git clone https://github.com/yourusername/energy-dataset-analysis.git
   
2. Install the required libraries:
   
   pip install pandas numpy matplotlib seaborn scipy
   

## How to Run the Code

- Ensure the dataset (`energy_dataset.csv`) is in the project directory.
- Run the Python script to execute the data cleaning and analysis steps.


python analysis.py


## Results

- The data was cleaned, and missing values were handled.
- Key insights into the distribution and correlation of numerical attributes were obtained.
- Visualizations were generated for better understanding of the dataset.

## Acknowledgements

- This project uses the [pandas](https://pandas.pydata.org/), [NumPy](https://numpy.org/), [Matplotlib](https://matplotlib.org/), [Seaborn](https://seaborn.pydata.org/), and [SciPy](https://scipy.org/) libraries for data analysis and visualization.
