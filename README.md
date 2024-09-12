# Programming-Assignment-2

## NORMALIZATION PROBLEM: 
Normalization is one of the most basic preprocessing techniques in data analytics. This involves centering and scaling process. Centering means subtracting the data from the mean and scaling means dividing with its standard deviation. 

In Python, element-wise mean and element-wise standard deviation can be obtained by using .mean() and
.std() calls.

In this problem, create a random 5 x 5 ndarray and store it to variable X. Normalize X. Save your normalized ndarray as X_normalized.npy

** To solve, I used random.randint to generate random integers in a 5x5 matrix. I then coded the formula to Python and run it to the matix A. I then save it to 'X_normalized.npy'. **

## DIVISIBLE BY 3 PROBLEM:

Create the following 10 x 10 ndarray which are the squares of the first 100 positive integers.

From this ndarray, determine all the elements that are divisible by 3. Save the result as div_by_3.npy

**** I create a 10x10 array with squares of the first 100 integers and created an empty array to append elements to. I iterate every element in A and append them to B when they are divisible by 3 using the modulo operator. I then save it to 'div_by_3.npy' ****


