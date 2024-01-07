# FUNDAMENTALS-OF-DATA-ANALYSIS

<p>G00364639</p>
<p>This repository is used for the project given during the FUNDAMENTALS-OF-DATA-ANALYSIS module on Higher Diploma in Data Analytics course from ATU.</p>

<p>I have created Jupyter Notebook in Visual Studio Code, & I have added added comments to explain work, along with references<br>

<p>For this markup sheet, I used the following websites as guides.<br>

<ol>
<li><a href="#">https://www.markdownguide.org/basic-syntax</a></li>
<li><a href="#">https://www.w3schools.io/file/markdown-cheatsheet/</a></li></p>
</ol>

# **Table of contents**
* [FUNDAMENTALS-OF-DATA-ANALYSIS](FUNDAMENTALS-OF-DATA-ANALYSIS)
    1. [Introduction](#Introduction)
    2. [How to run program](#How-to-run-program)
    3. [Additional Information](#Additional-Information)
    4. [Imported Libraries](#Imported-Libraries)

# Introduction #

<p>This repository is used for the project given during the FUNDAMENTALS-OF-DATA-ANALYSIS module on Higher Diploma in Data Analytics course from ATU.</p>

<p>For this module I created two notebooks.</p>

<p>
<li>tasks.ipynb, which contains all the work relating to tasks section</li>
<li>project.ipynb, which contains all the work relating to project section</li>
</p>
<p> The tasks section scope is as follows
<ol>
<li> *Task 1* : The Collatz conjecture is a famous unsolved problem in mathematics. The problem is to prove that if you start with any positive integer x and repeatedly apply the function $f(x)$ below, you always get stuck in the repeating sequence 1, 4, 2, 1, 4, 2, . . . 

f(x) =
x ÷ 2 if x is even
3x + 1 otherwise 

For example, starting with the value 10, which is an even number, we divide it by 2 to get 5. Then 5 is an odd number so, we multiply by 3 and add 1 to get 16. Then we repeatedly divide by 2 to get 8, 4, 2, 1. Once we are at 1, we go back to 4 and get stuck in the repeating sequence 4, 2, 1 as we suspected.  

Your task is to verify, using Python, that the conjecture is true for the first 10,000 positive integers.</li>
====================================================================================
<li> *Task 2* : Give an overview of the famous penguins data set, explaining the types of variables it contains. Suggest the types of variables that should be used to model them in Python, explaining your rationale </li>
====================================================================================
<li> *Task 3* : For each of the variables in the penguins data set, suggest what probability distribution from the numpy random distributions list is the most appropriate to model the variable.  </li> 
====================================================================================
<li> *Task 4* :Suppose you are flipping two coins, each with a probability p of giving heads. Plot the entropy of the total number of heads versus p </li> 
===================================================================================
<li> *Task 5* Create an appropriate individual plot for each of the variables in the penguin data set.  </li>
===================================================================================
</ol>
</p>

<p> The project scope is as follows
<ol>
<li> The project is to create a notebook investigating the variables and data points within the well-known iris flower data set associated with Ronald A Fisher </li>
<li> In the notebook, you should discuss the classification of each variable within the data set according to common variable types and scales of measurement in mathematics, statistics, and python </li>
<li> Select, demonstrate, and explain the most appropriate summary
statistics to describe each variable. </li>   
<li> Select, demonstrate, and explain the most appropriate plot(s) for
each variable. </li> 
<li> The notebook should follow a cohesive narrative about the data
set.
</li>
</ol>
</p>

# How to run program #
<ol>
<li> Install Anaconda </li>
<li> Install Visual Studio Code </li>   
<li> Clone repository </li> 
<li> Open repository in Visual Studio Code </li>
</ol>

# Additional Information #
<ol>
<li> My github repository is @ <a href="#">https://github.com/dectan/FUNDAMENTALS-OF-DATA-ANALYSIS</a></li>
<li> My github Ripository is called "FUNDAMENTALS-OF-DATA-ANALYSIS</li>
<li> This ripository contains a .gitignore file, 2 *  Jupyter notebooks, and a readme file and a folder with images. </li>   
<li> My Jupyter notebooks are called "project.ipynb" and "tasks.ipynb"</li> 
<li> There are no additional files required to run program as dataset is loaded from seaborn </li>
<li> images are stored in a folder called "img" in this ripository </li>
<li> Libraries that need to be imported are contained in first *txt* cell of both Jupyter notebooks </li> 
</ol>

# Imported Libraries #
<ol>
<li>import numpy as np</li>
<p> NumPy is short for "Numerical Python". It allows for matematical and logical operations on arrays efficiently. NumPy also enables user to reshape,slice ,stack and join arrays.</p>
<li>import pandas as pd</li>
<p>Pandas is an open source Python library that provides high performance data manipulation tools and analysis tools. It also allows for reading and writing from various file formats, such as .csv. Pandas has functions for analyzing, cleaning , exploring and manipulating data</p>
<li>import matplotlib.pyplot as plt</li>
<p>Matplotlib is a low level graph plotting library in python. It is open source. Using Mathplotlib, different types of plots can be created, such as scatter plots, histograms,box plots etc.</p>
<li>import seaborn as sns</li>
<p>Seaborn is a Python data visualization library based on matplotlib. It provides a high-level interface for drawing attractive and informative statistical graphics.It is designed to work well with dataframes from Pandas
</ol>