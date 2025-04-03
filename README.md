# Data-Analysis-and-Extraction-Tool

Overview :
This Data Analysis Tool is a Python-based script that allows users to load, filter, and visualize data from CSV files. 
It provides functionalities to:

Load a dataset from a CSV file.
Apply filters to extract specific data.
Find the closest matches if no exact match is found.
Generate scatter plots with regression lines for visual analysis. (optional)

Features:
1) Load Data Reads a CSV file and loads it into a Pandas DataFrame.
2) Handles missing or incorrect file paths gracefully.
3) Filter Data Allows users to filter the dataset based on specified column values.
4) Supports case-insensitive string matching.
5) Works with both numeric and non-numeric columns.
6) Find Closest Matches If exact matches aren’t found, the script calculates similarity scores for numeric and text-based data.
7) Displays the top 5 closest matches.
8) Data Visualization Generates a scatter plot to visualize relationships between two numeric columns.
9) Fits and displays a regression line using NumPy’s polyfit function.

How to Use Run the script:
bash Copy Edit python Data_Analysis_tool.py Enter the CSV file path when prompted.

1) Select columns for filtering and provide desired values.
2) View filtered results or closest matches if no exact match is found.
3) Choose columns for visualization to generate a scatter plot.
   
Dependencies Make sure you have the following Python libraries installed:
bash Copy Edit pip install pandas numpy matplotlib Future Improvements Add a graphical user interface (GUI) for easier interaction.
Support additional visualization types (histograms, bar charts, etc.).
Implement advanced filtering (e.g., range-based searches)
