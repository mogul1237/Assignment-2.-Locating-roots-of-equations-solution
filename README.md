# Assignment-2.-Locating-roots-of-equations-solution

Download Here: [Assignment 2. Locating roots of equations solution](https://jarviscodinghub.com/assignment/assignment-2-locating-roots-of-equations-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

Problem 1. (computer) (0 points – do not return)
Write a program which uses the bisection method for locating roots of equations. Use the
program to find the root of the following equation
9x
4 +18x
3 +38x
2 −57x+14 = 0
in the interval [0,1].
Problem 2. (computer) (3 points)
(a) Write a program which uses the Newton’s method for locating roots of equations. Use
the program to find the root of the following equation
x
3 −x−5 = 0
Use the initial point x0 = 0.57735. Limit your iterations to 50. Print out the results and
explain them.
(b) Construct a hybrid method which utilizes a combination of the bisection and Newton’s
algorithms to ensure global convergence. This algorithm takes a bisection step whenever
Newton’s algorithm would take the solution out of bounds. As input, this method needs
two numbers a1 and a2 which bracket the root and the starting point for the Newton’s
method x0 (this can, of course, be computed from the brackets, but for testing purposes
use the value x0 = 0.57735).
Hint: Modify your code from part (a) by inserting a condition to use bisection if Newton
is out of range.
1
Problem 3. (computer / Matlab) (3 points)
Basin of attraction. Consider the complex polynomial z
3 −1. Its roots are the three cube
roots of unity. Generate a picture showing the three basins of attraction in the square
region defined by −1 ≤ Real(z) ≤ 1 and −1 ≤ Imag(z) ≤ 1.
To do this, use a mesh of 1000×1000 pixels inside the square. The center point of each
pixel is used to start the iteration of Newton’s method. Assign a particular basin color to
each pixel if convergence to a root is obtained with a maximum of 100 iterations.
In order to limit the large number of iterations use a criterion for stopping the iteration
when it gets within a certain neighborhood of the root. The criterion for convergence is
to check both |zn+1 −zn| < ε and |z 3 n+1 −1| < ε with a small value such as ε = 10−12 as well as using a maximum number of steps. Hint: It is best to test your program and to get a crude picture with only a small number of pixels such as 10×10. Note: For this problem, it is permitted to use Matlab (solutions in other programming languages are of course also accepted).
