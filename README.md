AIM
To perform data binning and data formatting using Python, and to understand how raw data can be categorized,
transformed, and organized for better analysis using libraries like Pandas and NumPy.

THEORY
1. Data Binning
Data binning (also called data discretization) is the process of converting continuous numerical data into discrete categories or groups (bins).
It helps in:
Simplifying data
Reducing noise
Improving data analysis and visualization
In the experiment:
The pd.cut() function is used to divide data into bins.

2. Data Formatting
Data formatting refers to transforming data into a consistent and usable format.

a) Data Type Conversion
Changing data types using .astype()
Helps in performing correct calculations

b) Rounding Values
Numerical values are rounded using .round()
Improves readability and precision control

c) String Formatting
Text data can be modified using string functions

d) Sorting Data
Sorting helps in organizing data

3. Data Analysis using Binning
Categorized data is analyzed using:

4. Practical Implementation
In this experiment:
Product dataset is created
Order dataset is created
Binning is applied on:
Price / Order Value
Units Sold
Delivery Time
Data is formatted and sorted for better understanding


CONCLUSION
The experiment successfully demonstrated how to perform data binning and data formatting using Python. Using Pandas functions like pd.cut(), sort_values(), and string operations, raw data was effectively transformed into meaningful categories.
This process improves:

Data clarity
Analytical efficiency
Decision-making capability
Overall, data binning and formatting are essential preprocessing steps in data analysis and play a crucial role in handling real-world datasets efficiently.
