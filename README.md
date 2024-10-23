# Data Science Notes

This project serves as a comprehensive reference for relevant data science syntax (pandas, matplotlib) in Python.

The base dataset for all examples in the Pandas and Matplotlib sections will be the well-known "Titanic" dataset, which can be found on [Kaggle](https://www.kaggle.com/competitions/titanic/data). At times, other simplier datasets are used for an example.

#### <u>Last Updated</u>: 23-Aug-2024

#### <u>Author</u>: Vincent Giang  

<br/><br/>

# Table of Contents: Pandas

### Importing Data 
- “read_csv()”  
- “read_excel()” 
- “read_json()” 
- “read_table()”   


### Data Exploration
- “head()” and “tail()”  
- “sample()”
- “shape” 
- “columns”
- “info()” 
- “describe()” 
- “unique()” 
- “value_counts()” 
- “.get()”
- “isin()” 

### Missing Data
- “isna()” 
- “dropna()”
- “fillna()”
- “notna()”   

### Selecting Data
- “iloc[]”
- “loc[]”
- “.iat” 
- “.at”   

### Data Transformation
- “apply()”
    - “lambda x:”
- “replace()”
- “melt()”

### Dataframe Manipulation
- Create a Dataframe 
- Adding a new Column
- Adding a new Row 
- Removing a Column 
- Removing a Row 
- Rearranging order of Columns 
- “rename()”
- “set_index()”
- “reset_index()”

### Sorting and Ordering 
“sort_values()”
“nlargest()” and “nsmallest()” 

### Merging and Joining 
- “merge()”
- “concat()”

### Grouping and Aggregation
- “groupby()” 
    - “mean()” 
    - “sum()” 
    - “count()” 
    - “min()” 
    - “max()” 
    - “std()” 
    - “agg()” 
    - “lambda x:” 

### String Manipulation
- “str.lower()” and “str.upper()” and “str.title()” 
- “str.strip()” and “str.lstrip()” and “str.rstrip()” 
- “str.replace()”
- “str.startswith()” and “str.endswith()”
- “str.len()” 
- “str.join()” 

### Date/Time Manipulation
- “to_datetime()”
- “strftime()”

<br/><br/>

# Table of Contents: Matplotlib.pyplot
- Scatterplot 
- Histogram 
- Barplot 
- Pie Chart 
- Line chart
- Box plot
- Heatmap

