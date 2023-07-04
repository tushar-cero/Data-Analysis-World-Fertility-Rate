# World Fertility Data Analysis

The total fertility rate (TFR) of a population is the average number of children that would be born to a female over their lifetime if:
* they were to experience the exact current age-specific fertility rates (ASFRs) throughout their lifetime
* they were to live from birth until the end of their reproductive life.
It is obtained by summing the single-year age-specific rates at a given time.

This code file analyzes world fertility data.

To run this code, you can save it as an ipynb file and then open it in a Jupyter Notebook. Once the notebook is open, you can run the code by clicking on the "Run" button. All the representations will be displayed in the notebook.

## Requirements

This code requires the following Python libraries:

* ```pandas```
* ```numpy```
* ```matplotlib```
* ```seaborn```
* ```folium```

## Usage

To use this code, you can follow these steps:

1. Save the code as an ipynb file.
2. Open the notebook in a Jupyter Notebook.
3. Run the code by clicking on the "Run" button.
4. All the representations will be displayed in the notebook.

## Data Set

**DATA SOURCE** — [https://wisevoter.com/country-rankings/fertility-rate-by-country/](https://wisevoter.com/country-rankings/fertility-rate-by-country/)

The World Fertility Data Set is a collection of data on fertility rates from 212 countries or areas of the world. The data is compiled by the [WiseVoter](https://wisevoter.com/) and has data till 2023 country-wise.

The dataset has the following columns — 
Sr. No.    | Column                       | Non-Null Count | Data Type  
--- | ------                       | -------------- | -----  
 0  | Sr. No                       |   212 non-null |  int64  
 1  | Country                      |  212 non-null  |  object 
 2  | Avg. Fertility               |   212 non-null |  float64
 3  | Birth Rate (per 1k)          |   211 non-null |  object 
 4  | Infant Mortality Rate (per 1k)|  185 non-null |  object 

# Results

MEAN | MEDIAN | MODE
-----|--------|-----
2.6 | 2.1 | 1.7

## Bar Chart

The bar chart shows the number of countries in each fertility bucket. This can be a useful way to visualize the distribution of fertility rates around the world.

![Bar Chart](https://github.com/tushar-cero/Data-Analysis-World-Fertility-Rate/blob/main/bar_chart.png)

The buckets defined are — 
A : [ 5.5, 7 ]
B : [5, 5.5 ]
C : [4.5, 5 ]
D : [4, 4.5 ]
E : [3.5, 4 ]
F : [3, 3.5 ]
G : [2.5, 3 ]
H : [2, 2.5 ]
I : [1.5, 2 ]
J : [1, 1.5 ]
K : [0.5, 1 ]

## Box Plot

A box plot is a graphical representation of data that shows the distribution of data points along with the median, first quartile, and third quartile. In the context of world fertility data, a box plot shows the distribution of fertility rates around the world and identifies any outliers.

![Box Plot](https://github.com/tushar-cero/Data-Analysis-World-Fertility-Rate/blob/main/box_plot.png)

## World Map

A world map is used to show the fertility rate of each country. This can be a useful way to visualize the global distribution of fertility rates and to identify any trends.

![Map of the World](https://github.com/tushar-cero/Data-Analysis-World-Fertility-Rate/blob/main/world_map.png)

## Author

This code was written by Tushar Singh.
