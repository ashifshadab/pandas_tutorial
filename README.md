# Pandas
Pandas is an open-source library that is built on top of NumPy library.

# Why Use Pandas?
<ul>
    <li>Fast and efficient for manipulating and analyzing data.</li>
    <li>Data from different file objects can be easily loaded.</li>
    <li>Flexible reshaping and pivoting of data sets</li>
    <li>Provides time-series functionality.</li>
</ul>

# What can you do using Pandas?
<ul>
    <li>Data set cleaning, merging, and joining.</li>
    <li>Easy handling of missing data (represented as NaN) in floating point as well as non-floating point data.</li>
    <li>Columns can be inserted and deleted from DataFrame and higher dimensional objects.</li>
    <li>Powerful group by functionality for performing split-apply-combine operations on data sets.</li>
    <li>Data Visulaization</li>
</ul>

# Pandas Data Structures
Pandas generally provide two data structures for manipulating data, They are: 
<ol>
    <li>Series</li>
    <li>DataFrame</li>
</ol>

# Series
Pandas Series is a one-dimensional labeled array capable of holding data of any type (integer, string, float, python objects, etc.). 
The axis labels are collectively called indexes.

Pandas Series is nothing but a column in an Excel sheet. Labels need not be unique but must be a hashable type. The object supports both integer and label-based indexing and provides a host of methods for performing operations involving the index.

![](/assets/SERIES-300x97.png)

# DataFrame
Pandas DataFrame is a two-dimensional size-mutable, potentially heterogeneous tabular data structure with labeled axes (rows and columns). 

A Data frame is a two-dimensional data structure, i.e., data is aligned in a tabular fashion in rows and columns. 

Pandas DataFrame consists of three principal components: -
<ol>
    <li>data</li>
    <li>rows</li>
    <li>columns</li>
</ol>

![](/assets/pandas-dataframe.png)

# The syntax of creating dataframe is:
<h1 align="middle">pandas.DataFrame(data, index, columns)</h1>
<ol>
<li><b style="font-size:20px">data:</b> It is a dataset from which dataframe is to be created. It can be list, dictionary, scalar value, series, ndarrays, etc.</li>

<li><b style="font-size:20px">index:</b> It is optional, by default the index of the dataframe starts from 0 and ends at the last data value(n-1). It defines the row label explicitly.</li>

<li><b style="font-size:20px">columns:</b> This parameter is used to provide column names in the dataframe. If the column name is not defined by default, it will take a value from 0 to n-1.</li>
</ol>

# Pandas from_records() function
Pandas from_records() function of DataFrame changes structured data or records into DataFrames. It converts a structured ndarray, tuple or dict sequence, or DataFrame into a DataFrame object.

# The DataFrame.from dict() method
The DataFrame.from dict() method in Pandas builds DataFrame from a dictionary of the dict or array type. By using the dictionary’s columns or indexes and allowing for Dtype declaration, it builds a DataFrame object.

# json_normalize() 
Pandas have a nice inbuilt function called json_normalize() to flatten the simple to moderately semi-structured nested JSON structures to flat tables.

# 
<table class="series-table"><tbody><tr><th style="background-color:#c6ebd9">Function</th><th style="background-color:#c6ebd9">Description</th></tr><tr><td><strong><a href="https://www.geeksforgeeks.org/python-pandas-series-add/" rel="noopener" target="_blank">add()</a></strong></td><td>Method is used to add series or list like objects with same length to the caller series</td></tr><tr><td><strong><a href="https://www.geeksforgeeks.org/python-pandas-series-sub/" rel="noopener" target="_blank">sub()</a></strong></td><td>Method is used to subtract series or list like objects with same length from the caller series</td></tr><tr><td><strong><a href="https://www.geeksforgeeks.org/python-pandas-series-mul/" rel="noopener" target="_blank">mul()</a></strong></td><td>Method is used to multiply series or list like objects with same length with the caller series</td></tr><tr><td><strong><a href="https://www.geeksforgeeks.org/python-pandas-series-div/" rel="noopener" target="_blank">div()</a></strong></td><td>Method is used to divide series or list like objects with same length by the caller series</td></tr><tr><td><strong><a href="https://www.geeksforgeeks.org/python-pandas-series-sum/" rel="noopener" target="_blank">sum()</a></strong></td><td>Returns the sum of the values for the requested axis</td></tr><tr><td><strong><a href="https://www.geeksforgeeks.org/python-pandas-series-prod/" rel="noopener" target="_blank">prod()</a></strong></td><td>Returns the product of the values for the requested axis</td></tr><tr><td><strong>mean()</strong></td><td>Returns the mean of the values for the requested axis</td></tr><tr><td><strong><a href="https://www.geeksforgeeks.org/python-pandas-series-pow/" rel="noopener" target="_blank">pow()</a></strong></td><td>Method is used to put each element of passed series as exponential power of caller series and returned the results</td></tr><tr><td><strong><a href="https://www.geeksforgeeks.org/python-pandas-series-abs/" rel="noopener" target="_blank">abs()</a></strong></td><td>Method is used to get the absolute numeric value of each element in Series/DataFrame</td></tr><tr><td><strong><a href="https://www.geeksforgeeks.org/python-pandas-series-cov-to-find-covariance/" rel="noopener" target="_blank">cov()</a></strong></td><td>Method is used to find covariance of two series</td></tr></tbody></table>

