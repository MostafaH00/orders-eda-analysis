# Sales Data Exploratory Analysis

## Objective

This project analyzes a sales dataset to understand sales performance across products, categories, and cities.

The objective is to clean the data, explore its main characteristics, visualize important patterns, and extract useful insights.

## Dataset

The dataset contains sales orders with information about products, categories, prices, quantities, customers, and cities.

## Data Cleaning

- Remove duplicate records
- Standardize categorical variables
- Handle missing values based on the context of each variable
- Replace missing ages with the median age
- Impute missing prices using the median price of the corresponding product
- Remove records containing impossible values, such as negative prices or quantities
- Identify potential outliers

## Analysis

The project includes:

* Data understanding and inspection
* Data cleaning
* Feature engineering
* Exploratory Data Analysis (EDA)
* Data visualization
* Correlation analysis
* Interpretation of the results

## Tools

* Python
* Pandas
* NumPy
* Matplotlib

## Key Insights

1. **Products — Revenue**
 Phones generate the highest total revenue, likely due to their high unit price and their presence in multiple orders.
2. **Quantity**
 Cheaper products, such as Chargers and Headphones, tend to be purchased in larger quantities than more expensive products.
3. **Categories**
The Electronics category generates higher total revenue than Accessories, which may be explained by its higher product prices.
4. **Cities**
 Lyon generates the highest total revenue despite having a similar number of orders to Paris. The revenue gap may be explained by differences in the products ordered.
5. **Price - Quantity relation**
 Price and quantity show a negative relationship, with higher-priced products generally purchased in smaller quantities; however, this does not imply causation.

## Repository Structure

- `data/` → Contains the dataset used for the analysis
- `notebooks/` → Contains the Jupyter notebook with the complete EDA
- `.gitignore` → Specifies files and folders that Git should ignore
- `README.md` → Provides an overview of the project, methodology, and key findings

## How to Run

1. Clone the repository.
2. Install the required Python libraries: Pandas, NumPy, and Matplotlib.
3. Open `notebooks/EDA_project.ipynb` in Jupyter Notebook.
4. Run the cells in order.


## Future Improvements

- Perform deeper statistical analysis

- Explore additional relationships between variables

- Apply the analysis to a larger real-world dataset

