# LPP Graphical Method MATLAB
MATLAB Code for solving LPP using graphical method and how to plot it

FOLLOW THE BELOW STEPS TO SOLVE ANY LPP HAVING TWO CONSTRAINTS

STEP 1
-> Take all the inputs and store them

STEP 2
-> SET the values of one variabel/ constraint
-> Write the constraints/function with respect of the SET variable
-> Plot the lines

STEP 3
->Find all the possible intersection points(i.e line 1 and 2, line 2 and 3,line 1 and 4 etc...)
->Make a function which filter outs the points which satisfies all the constraints given in the LPP

STEP 4
->Plot the Corner Points and then use convexhul function so that all the points are arreanged in a way they can form a proper polygon
->Plot the polygon(Feasible Region) using fill function
->Find the optimal value of the object function and points corresponding to them
->Plot the optimal point with different color
