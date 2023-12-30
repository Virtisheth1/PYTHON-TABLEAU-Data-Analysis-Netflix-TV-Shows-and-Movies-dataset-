# Data-Analysis-Netflix-TV-Shows-and-Movies

Our project centered around a robust and extensive Netflix dataset comprising 5,850+ unique titles encompassing movies and TV shows. Acquired in May 2022, this dataset provided a rich array of attributes including title details, release years, genres, runtimes, IMDb ratings, and more.

1. Pandas:
   - `read_csv()`: Allows customization of various parameters such as specifying data types, parsing dates, and handling missing values using parameters like `dtype`, `parse_dates`, `na_values`.
   - `groupby()`: Enables advanced grouping operations, allowing aggregation with functions like `agg()`, facilitating multi-level grouping and transformations.
   - `apply()`: Applies a function along an axis of the DataFrame or specific columns/rows, useful for complex data transformations.
   - `merge()`, `join()`, `concat()`: Offer flexibility in combining datasets based on various conditions, keys, or axes.

2. Data Cleaning:
   - Regular Expressions: Advanced text pattern matching used in Pandas through functions like `str.contains()` or `str.extract()` for intricate string operations.
   - Handling Datetime: Utilizing `to_datetime()` and extracting date components like day, month, or year using `.dt` accessor for time-based analysis.

3. Visualization:
   - Subplots and Customizations: Advanced plotting using subplots, customizing color schemes, adding annotations, and using seaborn styles for aesthetic improvements.

4. Statistical Analysis:
   - Groupby Operations: Advanced statistical computations with `groupby()`, enabling calculations like rolling means, cumulative sums, or customized functions via `apply()` within groups.
   - Statistical Tests: Utilizing statistical tests (e.g., t-tests, ANOVA) from libraries like `scipy.stats` for hypothesis testing on DataFrame subsets.

5. Machine Learning:
   - Pipeline: Constructing data processing and modeling pipelines using `Pipeline` from Scikit-learn, integrating data transformation steps with model training for seamless execution.
   - Hyperparameter Tuning: Employing techniques like GridSearchCV or RandomizedSearchCV to optimize model performance by tuning hyperparameters efficiently.

6. Feature Engineering:
   - Custom Functions: Creating custom functions and applying them to DataFrame columns using `apply()` or `transform()` for feature extraction, transformation, or creation.
   - One-Hot Encoding: Generating dummy variables not just for categorical columns but also handling scenarios with hierarchical or multi-level categorical data.

7. Insight Generation:
   - Advanced Aggregations: Using custom aggregation functions combined with `groupby()` to derive deeper insights, calculating weighted averages, or percentile-based analysis.
   - Time Series Analysis: Applying time series techniques such as resampling, rolling window statistics, and decomposition for temporal data exploration.

These advanced Pandas functionalities and data analytics techniques enable more sophisticated data manipulation, exploration, and modeling, empowering in-depth analysis and extraction of nuanced insights from complex datasets.
