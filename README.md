# Chicago Energy Consumption Analysis Using PySpark

## Project Overview
This project involves analyzing energy consumption in Chicago, focusing on electrical and thermal energy usage. The analysis leverages PySpark to handle large datasets efficiently and perform complex data manipulations.

## Data Import and Setup
- **Initial Setup**: Configuration of Spark installation and session initialization.
- **Data Import**: Data is imported from a CSV file to create initial dataframes for analysis.

## Data Preparation
1. **Data Cleaning**:
   - Removal of unnecessary columns such as 'census block' and 'building subtype'.
   - Standardization of column names by converting them to lowercase and removing spaces.
   - Handling missing values by replacing them with the average of the respective columns.

2. **Data Viewing**:
   - Examination of the dataset structure and initial rows.
   - Calculation of distinct counts of column values to understand data distribution.

## Data Analysis
- **Energy Classification**: Separate dataframes for electrical and thermal energy.
- **Consumption Patterns**:
   - Monthly maximum consumption analysis for electrical energy in 2010, identifying December as the peak month.
   - Analysis of geographical distribution of energy usage, highlighting areas with high consumption.

## Advanced Data Handling Techniques
- Use of PySpark functions to handle large datasets efficiently, including RDD transformations and aggregations.

## Comparative Analysis: PySpark vs. Pandas
### Advantages of PySpark
1. **Scalability**: Handles large datasets efficiently with parallel computations across multiple cores and nodes.
2. **Distributed Processing**: Utilizes resilient distributed datasets (RDDs) for robust data handling.
3. **Big Data Tools**: Offers a variety of tools and libraries suited for big data analysis.

### Advantages of Pandas
1. **Ease of Use**: More user-friendly for small to medium-sized datasets.
2. **Performance**: Highly optimized libraries, especially effective for non-complex queries.
3. **Flexibility**: Efficient in handling both large and small datasets without the need for a distributed environment.

### Limitations of PySpark
- Complex SQL queries can be slower and more difficult to optimize.
- Lacks certain functionalities like determining the dataset's shape easily.

## Conclusion
This project demonstrates the power of PySpark in analyzing large-scale data, providing insights into energy consumption patterns in Chicago. The comparative analysis with Pandas highlights the trade-offs between ease of use and scalability.

