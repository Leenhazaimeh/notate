
# What is Jupyter Lab
# JupyterLab
JupyterLab is a next-generation web-based user interface for Project Jupyter.

The JupyterLab is used as a text editor for programming, as it provides the ability to deal with files with different extensions: json , images , cvs , pdf , and JupyterLab used cell system To separate the code and run each part separately .

## Keyboard shortcuts for JupyterLab :
~~~

 a : to add new cell above current cell

B : to add new cell below current cell

C : copy the cell
X : cut the cell

V : pest the cell

dd : delete the cell

z : undo

(+ z : redo )

m : change format of cell to markdown

y : change format of cell to code

shift + enter : to show the result of the cell 
~~~

you can either open jupyter lab in Vs or in browser using poetry add jupyter lab to download jupyter in our environment and then jupyter lab command to open jupyter lab in the browser

# Numpy Tutorial

NumPy : is the fundamental package for scientific computing in Python (Python library)

# Numpy Arrays:

1. rows are the first axis

2. columns are the second axis

3. the array function is used to convert th list of lists into an array

**Code Example**
(reading a csv file and converting the output list into an array) ?

>import csv with open("winequality-red.csv", 'r') as f: wines = list(csv.reader(f, delimiter=";")) import numpy as np wines = np.array(wines[1:], dtype=np.float)

# Alternative NumPy Array Creation Methods


1. Using np.zeros where are all elements are zeroes.

>import numpy as np empty_array = np.zeros((3,4))

2. Using numpy.random.rand. where each element is a random number

>np.random.rand(3,4)

### Reading files using NumPy 

* using numpy.genfromtxt function.

>wines = np.genfromtxt("winequality-red.csv", delimiter=";", skip_header=1)

### Indexing NumPy Arrays
>NumPy is zero-indexed, meaning that the index of the first row is 0, and the index of the first column is 0

**Exampele:**
 "wines[2,3]" ===> element positioned in the third row and the fourth column
### Slicing NumPy Arrays
using colon, selects elements up until the last index, without it being included.

wines[0:3,3]

We can extract an entire column wines[:,3] or an entire row wines[3,:]

We can choose the whole array using wines[:,:]

### Assigning Values To NumPy Arrays
wines[1,5] = 10

Arrays can either be single dimensional, two dimensional or multi dimensional
NumPy Data Types
using array-name.dtype
Data type can be any of the following:
float — numeric floating point data. int — integer data. string — character data. object — Python objects.

Data Type Conversions
array-name.astype(int)

