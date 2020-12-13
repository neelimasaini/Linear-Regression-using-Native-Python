# Linear-Regression-using-Native-Python

''' 
We will be building  - Linear Regression. But before you build a model, we need to have a method to extract the data and process it in your data frames and convert to numpy. 

About data set 

NASA data set, obtained from a series of aerodynamic and acoustic tests of two and three-dimensional airfoil blade 
sections conducted in an anechoic wind tunnel. The data set comprises different size NACA 0012 airfoils at various wind 
tunnel speeds and angles of attack. The span of the airfoil and the observer position were the same in all of the experiments. 
The data set has 6 attributes as given below. 
This problem has the following inputs:
(Attributes 1 to 5 form X_data) 
1. Frequency, in Hertzs. 
2. Angle of attack, in degrees. 
3. Chord length, in meters. 
4. Free-stream velocity, in meters per second. 
5. Suction side displacement thickness, in meters. 

The only output is (and Y_data): 
6. Scaled sound pressure level, in decibels. 

Now you will read a dataset for Machine Learning using pandas
filename = "airfoil_self_noise.dat.txt"

The file is tab separated file with no headers

We are using a specific function for reading the file with pandas and storing the data into dataframe.
After that we are converting it to numpy
Then use numpy to split the data into training and test set.
The training data is 80% of data, and the test data should haveve 20% data, which is sperated without using SKLEARN library.
'''
