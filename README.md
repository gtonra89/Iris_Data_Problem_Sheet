# Problem set: Jupyter, pyplot and numpy
These problems relate to [Jupyter](https://jupyter-notebook.readthedocs.io/en/latest/examples/Notebook/Notebook%20Basics.html), [numpy](https://docs.scipy.org/doc/numpy-dev/user/quickstart.html), and [pyplot](https://matplotlib.org/users/pyplot_tutorial.html).
We will use the famous [iris data set](https://en.wikipedia.org/wiki/Iris_flower_data_set).

## What is Jupyter ?
<a href = "http://jupyter.org/"><img src="https://cdn-images-1.medium.com/max/800/1*j4ji49J3lTTNUvSsNsg6LA.png"></a>
<br>
The Jupyter Notebook<br>
The notebook extends the console-based approach to interactive computing in a qualitatively new direction, providing a web-based application suitable for capturing the whole computation process: developing, documenting, and executing code, as well as communicating the results. The Jupyter notebook combines two components:

A web application: a browser-based tool for interactive authoring of documents which combine explanatory text, mathematics, computations and their rich media output.

Notebook documents: a representation of all content visible in the web application, including inputs and outputs of the computations, explanatory text, mathematics, images, and rich media representations of objects.

## What is pyplot and numpy ?
matplotlib is a plotting library for the Python programming language and its numerical mathematics extension NumPy. It provides an object-oriented API for embedding plots into applications using general-purpose GUI toolkits like Tkinter, wxPython, Qt, or GTK+

NumPy is a library for the Python programming language, adding support for large, multi-dimensional arrays and matrices, along with a large collection of high-level mathematical functions to operate on these arrays

## Problems Set out 
Below are the problems set out for this worksheet and in my jupyter notebook file found in the link <a href="https://github.com/gtonra89/Iris_Data_Problem_Sheet/blob/master/IrisProblem.ipynb">Here</a><br> is the execution of these problems with built in graphs and answers  

## 1. Get and load the data

Search online for Fisher's iris data set, find a copy of the data, download it and save it to your repository.
If it is not in CSV format, use whatever means (Excel, notepad++, visual studio code, python) to convert it to CSV and save the CSV version to your repository also.
Open your Jupyter notebook for this problem sheet, creating a new one if needed, and load the CSV file into a numpy array.


## 2. Write a note about the data set

In a markdown cell at the start of your notebook, write a short description of the iris data set, complete with references.


## 3. Create a simple plot

The dataset contains five variables: sepal length, sepal width, petal length, petal width, and species.
Use pyplot to create a scatter plot of sepal length on the x-axis versus sepal width on the y-axis.
Add axis labels and a title to the plot.


## 4. Create a more complex plot

Re-create the above plot, but this time plot the setosa data points in red, the versicolor data point in green, and the virginica data points in blue.
Setosa, versicolor, and virginica are the three possible values of the species variable.
Add a legend to the plot showing which species is in which colour.


## 5. Use seaborn

Use the [seaborn](http://seaborn.pydata.org/examples/scatterplot_matrix.html) library to create a scatterplot matrix of all five variables.


## 6. Fit a line

Fit a straight line to the variables petal length and petal width for the whole data set.
Plot the data points in a scatter plot with the best fit line shown.


## 7. Calculate the R-squared value

Calculate the R-squared value for your line above.


## 8. Fit another line

Use numpy to select only the data points where species is setosa.
Fit a straight line to the variables petal length and petal width.
Plot the data points in a scatter plot with the best fit line shown.


## 9. Calculate the R-squared value

Calculate the R-squared value for your line above.


## 10. Use gradient descent

Use gradient descent to approximate the best fit line for the petal length and petal width setosa values.
Compare the outputs to your calculations above.
