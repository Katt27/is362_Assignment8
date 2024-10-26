# Auto MPG Data Analysis

This project is an analysis of the Auto MPG dataset from the UCI Machine Learning Repository. The analysis involves data cleaning, exploratory data analysis (EDA), and visualization of relationships between various features of the dataset.

## Dataset

The dataset used in this project is the [Auto MPG dataset](https://archive.ics.uci.edu/ml/datasets/Auto+MPG) from the UCI Machine Learning Repository. It includes various attributes for automobiles from the 1970s and 1980s, including fuel efficiency (mpg), engine specifications, weight, and origin.

### Features
- `mpg`: Miles per gallon (fuel efficiency)
- `cylinders`: Number of cylinders in the engine
- `displacement`: Engine displacement
- `horsepower`: Engine horsepower
- `weight`: Vehicle weight
- `acceleration`: Acceleration rate
- `model_year`: Model year of the vehicle
- `origin`: Origin of the car (1 = USA, 2 = Europe, 3 = Asia)
- `car_name`: Car model name

## Project Structure

The Jupyter Notebook in this project includes the following steps:

1. **Import Libraries**  
   Import necessary libraries such as `pandas`, `matplotlib`, and `seaborn`.

2. **Download and Load the Dataset**  
   The notebook downloads the Auto MPG dataset directly from the UCI repository and loads it into a pandas DataFrame.

3. **Data Overview and Cleaning**  
   Review the dataset structure, handle missing values in the `horsepower` column, and convert `origin` codes to region names.

4. **Exploratory Data Analysis (EDA)**  
   Visualize the distribution of key variables and explore relationships between features.

5. **Additional Analysis**  
   Analyze the relationship between specific variables to answer additional questions about the data.

## Data Cleaning Process

- Replaced any `?` values in the `horsepower` column with `NaN`, converted it to numeric, and filled missing values with the median horsepower.
- Converted the `origin` column from integer codes to string values representing regions (`1` = USA, `2` = Europe, `3` = Asia).

## Visualizations

The following visualizations were created:
- **Distribution of Cylinders**: A bar chart showing the distribution of vehicles by cylinder count.
- **Horsepower vs. Weight**: A scatter plot showing the relationship between `horsepower` and `weight`, color-coded by region.
- **Weight by Number of Cylinders**: A boxplot illustrating the weight distribution for each cylinder count.

## Conclusion

This analysis provides insights into the Auto MPG dataset, highlighting the distribution of vehicle attributes and relationships between engine specifications and vehicle weight. The project demonstrates the use of data cleaning and visualization techniques in Python.
