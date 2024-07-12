# Weather-Data-Analysis
**Description**

This Jupyter Notebook explores a weather dataset containing various weather conditions, temperatures, and other measurements.

**Instructions**

1. Create  and save this Jupyter Notebook and the "Weather Data.csv" file in the same directory.
2. Open the Jupyter Notebook in your preferred environment.
3. Run the notebook cells sequentially to execute the code and explore the weather data.
   
**Required Libraries**

* pandas
* numpy (optional, depending on analysis needs)
* matplotlib (for data visualizations)


** performs the following analyses:**

Calculates descriptive statistics (mean, standard deviation, variance) for numerical columns.
Creates data visualizations (histograms, scatter plots) to explore relationships between variables. (Code example included)
Identifies potential patterns, correlations, and outliers.

** Further Explanation:**

* Loads the data from a CSV file named "Weather Data.csv".
* Provides an overview of the data by displaying the first few rows (`df. head()`) and basic information about the DataFrame (`df.info()`, `df. describe()`).
* Discovers unique values for specific columns (`df['Wind Speed_km/h'].unique()`).
* Counts occurrences of specific weather conditions (`df['Weather Condition'].value_counts()`).
* Filters data based on specific criteria (`df[df['Wind Speed_km/h'] == 4]`).
* Checks for missing values (`df.isnull().sum()`).
* Renames columns (`df.rename(columns={'Weather':'Weather Condition'}, inplace=True)`).
* Calculates descriptive statistics (mean, standard deviation, variance) for numerical columns.
  



