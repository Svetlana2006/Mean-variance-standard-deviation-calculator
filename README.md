# Mean-variance-standard-deviation-calculator

This is my project to create a Mean-variance-deviation calculator

Tasks completed in the above project:- 
1) In mean_var_std.py, a function named calculate() is created that uses Numpy to output the mean, variance, standard deviation, max, min, and the sum of the rows, columns, and elements in a 3 x 3 matrix.
2) The function's input is taken to be a list containing 9 digits. The function should convert the list into a 3 x 3 Numpy array, and then return a dictionary containing the mean, variance, standard deviation, max, min, and sum along both axes and for the flattened matrix.
3) If a list containing less than 9 elements is passed into the function, it should raise a ValueError exception with the message: "List must contain nine numbers." The values in the returned dictionary should be lists and not Numpy arrays.


Steps taken to complete this project:-
1) Check Input Length: First, it was checked if the input list contains exactly 9 elements. If not, a ValueError was raised.
2) Convert the List to a 3x3 NumPy Array: Then the input list is converted into a 3x3 NumPy array using np.array() and reshape()
3) Calculate the Required Statistics: For each of the statistics (mean, variance, standard deviation, max, min, sum), I computed them along the rows (axis=0), along the columns (axis=1), and for the flattened array (using axis=None).

