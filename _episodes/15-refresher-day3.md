---
title: Refresher
teaching: 30
exercises: 0 
questions:
objectives:
keypoints:

---

## Takeaways

### Spreadsheets

Never modify your raw data. Always make a copy before making any changes.  
Keep track of all of the steps you take to clean your data in a plain text file.  
Organize your data according to tidy data principles: Avoid using multiple tables within one spreadsheet, avoid spreading data across multiple tabs, record zeros as zeros,
use an appropriate null value to record missing data, don’t use formatting to convey information or to make your spreadsheet look pretty, place comments in a separate column,
record units in column headers, include only one piece of information in a cell, avoid spaces, numbers and special characters in column headers, avoid special characters in your data, record metadata in a separate plain text file.  

  
### Python
One can assign a value to a variable in Python. Those variables can be of several types, such as string, integer, floating point and complex numbers.  
  
Python Data structures:  
 * **list**: `another_list = ["blue", "green", "red"]` - Lists contains an ordered sequence of elements. Each element can be accessed by an index. 
 * tuple: `another_tuple = ("blue", "green", "red")` - Tuples are order lists of elements, but immutable
 * Dictionary: `another_dict = {'first': 'one', 'second': 'two', 'third': 'three'}` - Dictionaries are data structures that provide mappings between keys and values
 
Python uses **0-based indexing**, in which the first element in a list, tuple or any other data structure has an index of 0. 
 
Libraries enable us to extend the functionality of Python.  

### Pandas
One of the best options for working with tabular data in Python is the library Pandas (Python Data Analysis Library).  
  
Pandas provides an object called DataFrame, this object represents tabular data. Dataframes are a **2-dimensional data structure and can store data of different types** (including characters, integers, floating point values, factors and more) in columns.  
  
Aggregating data using the `groupby()` function enables you to generate useful summaries of data quickly.  
  
Dataframes can be subsetted in different ways including using labels (column headings), numeric ranges, or specific x,y index locations.  
* dataframe["column_name"]
* dataframe []
* 

Data from multiple files can be combined into a single DataFrame using merge and concat.

### Plotting
Matplotlib is a Python package that is widely used throughout the scientific Python community to create high-quality and publication-ready graphics.  
  
Useful resources:  
* Matplotlib gallery: https://matplotlib.org/gallery.html  
* The PyViz.org website is an open platform for helping users decide on the best open-source (OSS) Python data visualization tools for their purposes, with links, overviews, comparisons, and examples.”  

The plotnine package is built on top of Matplotlib and interacts well with Pandas, it supports the creation of complex plots from data in a dataframe. Plotnine graphics are built step by step by adding new elements adding different elements on top of each other using the + operator. Putting the individual steps together in brackets () provides Python-compatible syntax.


## Setting up your Anaconda environment
Downloading Anaconda - anaconda prompt/GUI
Creating an environmnent (what is an environment, why do you use it?)
Downloading packages in your environment (default channel, other channels, what are channels)
Checking environments you have
Checking packages you have

### Jupyter Notebook
Activate the correct environment that you want your notebook to use
Open the notebook in the specific location that you need

### Check installs

## Where should your data be?
