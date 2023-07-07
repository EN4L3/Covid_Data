This project aims to visualize COVID-19 death rates and total cases by continent using Python and the Pandas library. The dataset used in this project is sourced from "Our World in Data" and contains COVID-19 statistics for various countries.

The project workflow includes the following steps:

Data Loading and Cleaning:

The dataset is loaded from a local directory using Pandas' read_csv() function.
Duplicate rows are removed, and missing values are handled by filling them with zeros.
Data types are appropriately converted, such as converting float values to integers and the date column to a datetime format.
Data Exploration:

The shape of the dataset and the first few rows are examined to gain initial insights.
Data types are checked to ensure proper handling and analysis.
Visualization:

Bar plots are used to visualize death rates by continent, displaying the proportion of total deaths relative to total cases for each continent.
Line plots are used to illustrate the trends of total cases and total deaths over time by continent.
Pie charts are used to represent the distribution of total cases and total deaths across continents.
Insights and Observations:

The bar plots provide a clear comparison of death rates across different continents, highlighting continents with high or low death rates.
The line plots depict the trends of total cases and total deaths over time, allowing for the observation of variations and patterns across continents.
The pie charts offer a visual representation of the proportion of total cases and total deaths by continent, enabling easy comparison.
It's important to note that the visualizations presented in this project are based on aggregated data at the continental level. Further analysis can be performed by considering additional factors or diving deeper into regional or country-level data.

Overall, this project provides valuable visual insights into the COVID-19 pandemic, allowing for a better understanding of the distribution, trends, and variations in total cases and total deaths across continents.
