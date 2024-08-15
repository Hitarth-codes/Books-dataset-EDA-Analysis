# Books-dataset-EDA-Analysis
This project performs EDA on a books dataset using pandas and matplotlib. It involves cleaning data, creating a Book class, serializing data with pickle, and visualizing it with various plots like bar graphs, heat maps, and scatter plots to uncover insights and trends.

## Project Overview

This project focuses on performing exploratory data analysis (EDA) on a books dataset to uncover insights and trends. The analysis involves several key steps:

1. **Data Parsing and Cleaning**: The dataset is parsed into a pandas DataFrame where duplicate and null values are removed.

2. **Book Class Implementation**: A custom `Book` class is created with attributes including `unique_id`, `date`, `title`, `genre`, `type`, `rating`, `price`, and `average_reading_time`.

3. **Data Serialization**: Data is serialized using pickle files. The objects are converted to strings and saved to a CSV file, which is then loaded back into a pandas DataFrame for further analysis.

4. **Data Wrangling**: The DataFrame is cleaned and transformed, including handling null values.

5. **Data Visualization**: Various types of plots are generated using matplotlib to visualize the data. This includes:
   - Bar Graphs
   - Box Plots
   - Heat Maps
   - Scatter Plots
   - Pie Charts
   - Line Graphs
   - Histograms

## Requirements

- Python 3.x
- pandas
- matplotlib
- pickle

