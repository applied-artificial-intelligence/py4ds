---
layout: post
title:  "Pandas Practice"
date:   2017-02-07 14:16:18 -0500
categories: jekyll update
---

## Practice Session: Lab

Let's work through the Pandas Practice Lab.

## Additional Visualization Tools

- [Seaborn: Statistical Data Visualization](http://seaborn.pydata.org/)
- [Bokeh](http://bokeh.pydata.org/en/latest/)

## More Practice: Sales Funnel

Let's use `read_csv` to open the file in a notebook.

### Basic Manipulation

1. Let's read in the data.
2. How do we see what columns are available?
3. How do we look at just the head or tail of the dataset?
4. How do we look at only a few rows?
5. How do we only look at certain columns?
6. How do we pull out a column and look at it as a series?

### Filtering DataFrames

1. How do we look at only those rows that have Status = won
2. Exercise: How many accounts have a price greater than $12,000?
3. How do we get the maximum value of a certain column?
4. Exercise: What is the minimum account price? The mean? The sum? The standard deviation?

### Aggregating Data

What is the total dollar amount pending?

1. How do we add columns?
2. Let's add a column called Amount that is equal to Quantity * Price
3. Exercise: Let's select just those rows where status is pending and sum up those amounts.

### Pivot tables

Question: What are pivot tables? Why are they useful?

Let's take a look at the [documentation](http://pandas.pydata.org/pandas-docs/stable/generated/pandas.DataFrame.pivot_table.html).

1. Let's pivot using one index.
2. Let's pivot on multiple indexes
3. Let's reverse those indexes
4. Let's specify which values we care about
5. Let's specify which columns we want broken down
6. Let's specify how we want the values to be aggregated (aggfunc)
7. Let's fill N/A values
8. Let's get subtotals


## Optional Practice: Bike Sharing Data

- What is this dataset about?
- Let's delete the Unnamed: 0 column.
- Let's compute the duration by turning starttime and stopttime into datetime objects and computing their difference.
- What is the average trip time? What is the minimum and maximum trip time? What is the standard deviation?
- What is the average trip time by station? (Hint: Use pivot tables)

