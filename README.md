# Pandas - Very Brief Introduction for Data Exploration

In a machine learning (ML) project, we often get data from CSV/TSV files. Pandas is a convenient tool to load data, process & analyze it before using the data for training an ML model.

Pandas is a fast, powerful, flexible, and easy-to-use open-source data analysis and manipulation tool. Pandas stands for **Python Data Analysis Library**. It is built on top of the Python programming language.  

Using pandas we can load data from CSV/TSV files. It converts the data into a Python object called DataFrame. The object has rows and columns representing the samples and features, respectively.

To train an ML model, we must convert the pandas DataFrame object into arrays (NumPy array): data matrix and one-dimensional target array. But before we do that, we need to do some data processing and exploration.

      
       -- The following notebooks show the basic steps of Pandas, NumPy, and Matplotlib-based data processing and exploration.


## Notebook 1

We load a small dataset stored in a CSV file as a pandas DataFrame object. Then, we perform basic data exploration.

- Check NaN values
- Check categorical features
- One-hot encode categorical features
- Data cleaning (remove/replace missing values)
- Compute feature correlation with the target
- Visualize feature correlation
- Select a subset of columns
- Convert data frame objects into arrays

See the following link to learn about pandas' methods:
https://pandas.pydata.org/


## Notebook 2

# Pandas - Group Data and Create Bar Plot

We create a Pandas data frame object and then perform the following tasks.
- Group data based on a numeric attribute
- Apply various functions on the samples of each group for the attributes, e.g., count, sum, mean
- Create bar plots to show aggregate values for each group

