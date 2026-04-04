# Machine-learning
My everyday learnings are documented here, totally self paced

DAY 01:

Machine learning bridges the gap between software-eng and data-eng
Uses algorithms to learn data in a manner.These people involve building ML learning and AI systems for scalability, maintaining and improving these existing systems.
Machine learning models are created based on real data to predict and act upon existing outcomes. 

Basic ML algorithms which i learnt: source (https://www.coursera.org/articles/machine-learning-algorithms)

Linear regression (LR):
LR is a supervised learning model( model is given inputs to learn unlicke unsupervised where models find patterns to learn)
which makes relationship with the values which fall into a continous range i.e x-inouts and y-outputs, forming a relationship line called regression line.
The algorithm takes a set of data points with known input and output values and finds the line that best fits those points.
It is done to understand how changes in input will affect the output. with the slope which is formed we can understand and predict the relationship between the variables

Code learnings: https://www.kaggle.com/code/lalithd13/linear-regression

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
DAY 02:

Learning python and essential libraries: All the code is documented here (https://www.kaggle.com/code/lalithd13/basic-libraries)
It was difficult to jump directly to programming, so will understand basic python and essential libraries.

1. Numpy: Python library for numerical computation, has ndarrays for faster calculations, mean median, mode, etc.
Ufunc performs operations on entire loop at once making it faster
-trignometric functions
-statistical functions (min, max)

Sparse matrix: used where most of the matrix elements are zero, for space efficiency we store only the non-zero elements with their row and coulmn indices storing them in triplets
csr_matrix: for fast row slicing, for good row access (compressed sparse row)
csc_matrix: for fast column slicing, for fast column access
coo_matrix: stores row,coulmn, and values in tripplets

Image processing with SciPy and numpy in python:
images are stored as pixel format in the form of matrix with each intensty and colour values.
we have to import imagesIO

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
DAY 03:

Pandas is used for reading and writing data from/to CSV files:
Data pre processing- handling missing values
Data cleaning- removing null or infinite values, remove duplicates
Transformation- Filter modify data
Visualization- plotting and depcting what is learnt

