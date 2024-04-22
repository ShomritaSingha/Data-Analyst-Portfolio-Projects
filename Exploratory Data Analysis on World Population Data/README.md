
# Exploratory Data Analysis on World Population Data


[**Link to collab Notebook on GitHub**](https://github.com/ShomritaSingha/Data-Analyst-Portfolio-Projects/blob/main/Python%20projects/EDA_worldPopulation.ipynb)

## Introduction:

In this exploratory data analysis (EDA) project, I have delved into a comprehensive dataset on world population. The primary aim of this analysis is to gain insights into the demographic landscape of various countries, examining factors such as population size, geographical area, population density, and growth rates.

## Data Import and Overview:

The project begins with the importation of essential Python libraries for data manipulation and visualization, such as **Pandas**, **Seaborn**, and **Matplotlib**. The dataset, named 'world_population.csv,' is then loaded into a Pandas DataFrame. This dataset encompasses 234 entries, each representing a unique country, with 17 columns containing information ranging from population figures in different years to geographical data.

**Uncleaned Data**![world population scrapped table](https://github.com/ShomritaSingha/Data-Analyst-Portfolio-Projects/assets/139176490/139de1f7-651a-442b-aa27-1a65bba23811)

## Data Cleaning:

A quick exploration of the data using **`df1.head(10)`** and **`df1.info()`** provides an overview of the structure and nature of the dataset. There are missing values in several columns, such as '2022 Population,' '2010 Population,' and 'Area (km²),' indicating the need for careful handling of missing or incomplete data during the analysis.

## Descriptive Statistics:

The `df1.describe()` function is utilized to obtain descriptive statistics, revealing key metrics such as mean, standard deviation, minimum, and maximum values for each numeric column. This provides a preliminary understanding of the distribution and scale of the data.

**Some Info for further analysis**
![info about the table](https://github.com/ShomritaSingha/Data-Analyst-Portfolio-Projects/assets/139176490/ed33cb81-11ea-474f-ac23-0a7740322f89)

## Sorting and Filtering:

To identify the countries with the highest populations in 2022, the dataset is sorted using the '2022 Population' column in descending order. The top 10 countries, including China, India, and the United States, are then displayed. Additionally, filtering operations, such as selecting data for countries in Oceania, are performed to focus on specific regions.

## Correlation Analysis:

A correlation matrix is computed using `df1.corr()` and visualized as a heatmap using Seaborn. This analysis reveals the relationships between different variables, aiding in identifying patterns and potential insights. For instance, the strong positive correlation between population figures in different years highlights the consistency in growth patterns.

## Heat Map Analysis:

To further explore the relationship between population rank and density, a heat map is generated using Seaborn. The heat map illustrates the density of each city, with the x-axis representing the population rank and the y-axis indicating the cities. The color gradient on the map corresponds to the density values, providing an easy-to-read visualization of how density varies across different population ranks.

**Population Densisty Heatmap**
![population heatmap](https://github.com/ShomritaSingha/Data-Analyst-Portfolio-Projects/assets/139176490/99eb8f9a-7453-48a3-8a77-878acc58f653)

## Grouping and Aggregation:

To understand population trends by continent, the dataset is grouped by 'Continent,' and mean values for different columns are computed. The resulting table provides an overview of average population sizes, densities, and growth rates for each continent.

## Continent-Wise Density Graph:

Additionally, a bar plot is created to visualize the continent-wise distribution of population density. The x-axis of the bar plot represents the continents, and the y-axis displays the average population density for each continent. This graph allows for a comparative analysis of population density across different continents, offering insights into the geographical distribution of population density trends.

**Plotof Density by each continent year wise increase**
![Screenshot 2023-11-12 173638](https://github.com/ShomritaSingha/Data-Analyst-Portfolio-Projects/assets/139176490/288dd91a-89a1-4845-b034-301893f0cdc3)

## Conclusion:

This EDA project offers valuable insights into global population trends. It sets the foundation for more in-depth analyses, potentially exploring the impact of socio-economic factors, environmental variables, and geopolitical events on population dynamics. The visualizations and statistical summaries presented here serve as a starting point for further investigation and interpretation, providing a comprehensive understanding of the dataset.
