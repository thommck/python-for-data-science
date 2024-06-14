# Week 3 - Virtual environments and using packages

This week's content will explore the use of virtual environments and a handful of example packages. Please take some time to read the additional notes and the relevant links before working through the homework notebooks.

## The Python Standard Library

The Python Standard Library is a collection of modules, which are pre-written pieces of code, that come with Python installation. These modules provide functionalities for a variety of tasks such as file I/O, system calls, string management, internet protocols, and more. It's like a toolbox filled with ready-to-use tools, saving you from writing common functionalities from scratch. To use these modules, you just need to `import` them in your Python script.

## Virtual environments

Python virtual environments are isolated environments where you can install Python packages without affecting your system’s Python or other virtual environments. They’re useful for managing project-specific dependencies and avoiding conflicts between packages.

## Installing additional packages

Python packages are collections of modules, which are reusable pieces of code, grouped together. They can be shared and installed using **pip**, the Python package installer. Pip allows you to install packages from the Python Package Index (PyPI) and other repositories. When you run a command like `pip install <package-name>`, pip downloads and installs the package and its dependencies.

## What is an API?

An API, or Application Programming Interface, is a set of rules and protocols for building and interacting with software applications. It defines methods of communication between various software components. APIs enable different software systems to interact with each other, facilitating the sharing and manipulation of data. In essence, they act as a bridge, allowing different software systems to understand each other and work together.

## What is an SDK?

An SDK, or Software Development Kit, is a collection of software tools and libraries that developers use to create applications for specific platforms or frameworks. It provides a set of pre-written code, documentation, and guidelines to streamline the development process. SDKs often include APIs for integration, debugging tools for testing, and sample code for learning purposes.

## Pandas DataFrame

A pandas DataFrame is a two-dimensional, labeled data structure that is widely used for data manipulation and analysis in Python. It consists of rows and columns, similar to a table or spreadsheet. DataFrames provide a powerful and flexible way to store, manipulate, and analyse structured data.

## Pandas Series vs DataFrame

In Pandas, a Series is a one-dimensional labeled array that can hold any data type. It is similar to a column in a spreadsheet or a single column of data in a table. A Series has both a sequence of values and a sequence of labels, called the index. The index allows for easy and efficient access to the data.

This is different to a DataFrame, which is a two-dimensional labeled data structure with columns of potentially different data types. It can be thought of as a table or a spreadsheet, where each column represents a variable and each row represents an observation. A DataFrame is more versatile and can handle complex data manipulations and analysis.

In short, a Series is a single column of data with an index, while a DataFrame is a collection of Series arranged in a tabular format. Understanding the difference between a Series and a DataFrame is crucial for effectively working with pandas and performing data analysis tasks.

## Pandas .apply() function in conjunction with lambda functions

The `apply` function in pandas is used to apply a function along an axis of a DataFrame or Series. When combined with lambda functions, it allows you to apply custom operations to each row or column of a DataFrame. This can be useful for performing calculations, transformations, or filtering based on specific conditions.

## Correlation

Correlation is a statistical measure that quantifies the relationship between two variables. It indicates the strength and direction of the linear relationship between the variables. Correlation coefficients range from -1 to 1, where -1 represents a perfect negative correlation, 1 represents a perfect positive correlation, and 0 represents no correlation.

## Boxplots, histograms & bar charts

Boxplots, histograms, and bar charts are commonly used visualisations in data analysis and data visualisation. 

- Boxplots provide a visual summary of the distribution of a dataset, displaying the minimum, first quartile, median, third quartile, and maximum values. They are useful for identifying outliers and comparing distributions.
- Histograms display the distribution of a continuous variable by dividing it into bins and counting the number of observations in each bin. They provide insights into the shape, central tendency, and spread of the data.
- Bar charts are used to compare categorical data by displaying the frequency or proportion of each category as bars. They are effective for visualising categorical variables and identifying patterns or trends.

## Relevant links

* [The Python Standard Library](https://docs.python.org/3/library/index.html)
* [Conda virtual environments documentation](https://docs.conda.io/en/latest/)
* [PyPI](https://pypi.org/)
* [Intro to Pandas using the Iris dataset](https://www.geeksforgeeks.org/python-basics-of-pandas-using-iris-dataset/)
* [Intro to Matplotlib](https://www.geeksforgeeks.org/python-introduction-matplotlib/)
* [Plotting the Iris dataset with Matplotlib](https://www.geeksforgeeks.org/plotting-graph-for-iris-dataset-using-seaborn-and-matplotlib/)

Note: The following links essentially cover what is asked of you in this week's homework... only use if you're very stuck!

* [Data analysis on the Iris dataset](https://www.geeksforgeeks.org/exploratory-data-analysis-on-iris-dataset/)
* [Even more data analysis on the Iris dataset](https://towardsdatascience.com/eda-of-the-iris-dataset-190f6dfd946d)