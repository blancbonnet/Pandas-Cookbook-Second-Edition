


# Pandas 1.x Cookbook - 2nd Edition
This is the code repository for [Pandas 1.x Cookbook - 2nd Edition](https://www.packtpub.com/programming/pandas-1-x-cookbook-second-edition), published by [Packt](https://www.packtpub.com/). It contains all the supporting project files necessary to work through the book from start to finish. The book is available on [O'Reilly](https://learning.oreilly.com/library/view/pandas-1-x-cookbook/9781839213106).

## About the Book
A new edition of the bestselling Pandas cookbook updated to pandas 1.x with new chapters on creating and testing, and exploratory data analysis. Recipes are written with modern pandas constructs. This book also covers EDA, tidying data, pivoting data, time-series calculations, visualizations, and more.

## Instructions and Navigation
All of the code is organized into folders. Each folder starts with a number followed by the application name. For example, Chapter02.

The code will look like the following:
```
def tweak_kag(df):
    na_mask = df.Q9.isna()
    hide_mask = df.Q9.str.startswith('I do not').fillna(False)
    df = df[~na_mask & ~hide_mask]

```
- [Chapter 1](https://github.com/blancbonnet/Pandas-Cookbook-Second-Edition-OReilly/tree/master/Chapter01): Pandas Foundations
- [Chapter 2](https://github.com/blancbonnet/Pandas-Cookbook-Second-Edition-OReilly/tree/master/Chapter02): Essential DataFrame Operations
- [Chapter 3](https://github.com/blancbonnet/Pandas-Cookbook-Second-Edition-OReilly/tree/master/Chapter03): Creating and Persisting DataFrames
- [Chapter 4](https://github.com/blancbonnet/Pandas-Cookbook-Second-Edition-OReilly/tree/master/Chapter04): Beginning Data Analysis
- [Chepter 5](https://github.com/blancbonnet/Pandas-Cookbook-Second-Edition-OReilly/tree/master/Chapter05): Exploratory Data Analysis
- [Chapter 6](https://github.com/blancbonnet/Pandas-Cookbook-Second-Edition-OReilly/tree/master/Chapter06): Selecting Subsets of Data
- [Chapter 7](https://github.com/blancbonnet/Pandas-Cookbook-Second-Edition-OReilly/tree/master/Chapter07): Filtering Rows
- [Chapter 8](https://github.com/blancbonnet/Pandas-Cookbook-Second-Edition-OReilly/tree/master/Chapter08): Index Alignment
- [Chapter 9](https://github.com/blancbonnet/Pandas-Cookbook-Second-Edition-OReilly/tree/master/Chapter09): Grouping for Aggregation, Filtration, and Transformation
- [Chapter 10](https://github.com/blancbonnet/Pandas-Cookbook-Second-Edition-OReilly/tree/master/Chapter10): Restructuring Data Into A Tidy Form
- [Chapter 11](https://github.com/blancbonnet/Pandas-Cookbook-Second-Edition-OReilly/tree/master/Chapter11): Combining Pandas Objects
- [Chapter 12](https://github.com/blancbonnet/Pandas-Cookbook-Second-Edition-OReilly/tree/master/Chapter12): Time Series Analysis
- [Chapter 13](https://github.com/blancbonnet/Pandas-Cookbook-Second-Edition-OReilly/tree/master/Chapter13): Visualization With Matplotlib, Pandas, And Seaborn
- [Chapter 14](https://github.com/blancbonnet/Pandas-Cookbook-Second-Edition-OReilly/tree/master/Chapter14): Debugging And Testing Pandas

## Related Products
* [Artificial Intelligence with Python – Second Edition](https://www.packtpub.com/in/data/artificial-intelligence-with-python-second-edition)

* [Mastering Machine Learning Algorithms - Second Edition](https://www.packtpub.com/in/data/mastering-machine-learning-algorithms-second-edition)### Download a free PDF

 <i>If you have already purchased a print or Kindle version of this book, you can get a DRM-free PDF version at no cost.<br>Simply click on the link to claim your free PDF.</i>
<p align="center"> <a href="https://packt.link/free-ebook/9781839213106">https://packt.link/free-ebook/9781839213106 </a> </p>
