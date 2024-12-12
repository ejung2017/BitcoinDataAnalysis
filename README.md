# BitcoinDataAnalysis
Used Jupyter notebook

Goal: What was the change in price of the Bitcoin overtime? 

Lifecycle of a data analytics project: 
1. Understand the (business) use case
- write down all the project requirements
- where to extract data (company's database vs 3rd party APIs, etc)
2. Run ETL pipeline
  E: Extract (forms raw data - ie. JSON or CSV files) - use SQL to extract data very easily
    *JSON = key value pair data 
  T: Transform (into featured data)
    - takes most of the time
    - Pre-processing: fixing error, removing dups, fix data types, fill missing values, etc
  L: Load
    - big data engineer receives the prepared data and loads/exports the data into platforms (for further analysis)
3. Exploratory Data Analysis: EDA
- analyzing the loaded data
  ie. e-commerce company -> which month customers have bought more number of product? month vs. revenue graph?  
4. Make conclusions


Summarized Steps: 
1. Data extraction - collect data from multiple sources (raw data)
2. Data transformation - clean and structurize the data into an acceptable format
3. Load Data - use the transformed, featurized data to perform various data analysis

EDA: Exploratory Data Analysis - leveraging different tools, plots, libraries to come up with a meaningful conclusion. 

Libraries used: 
1. Pandas - collect, manipulate, clean, perform numerical tasks on data
2. Matplotlib - data visualization package
3. Plotlib - used to create dynamic plot
4. NumPy - numerical computations on top of data
5. Seaborn - beautify plots 
