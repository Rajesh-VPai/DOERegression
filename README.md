# DOERegression
Java DOE Regression Package to generate the Equation of the Experiments
DOE Regression is a simple regressing Mathematical Software. It takes the DOE Matrix, the Level Mapping File and the Equation Files as inputs and creates the internal data structures. It then tries to regresss the values of the unknowns (m and c in the equations y=mx+c) where x represents the mapped Level Value.
DOE Regression solves the Simultaneous equations using 10th Grade Algebra. This avoids Noise affecting the values of m and c. It computes m and c for all the rows in the DOE Matrix (ROWSDOE). Thus multiple values of m and c can be computed.
It also solves unknowns more than 2 by using the Gaussian elimination.
It computes the Inverse of the Matrix in the matrix equation 
A*X=B with the solution :X=Ainverse*B where Matrix B is the Results Array for 1 factor (Column). This method however introduces Numerical Noise(tagged in RED).

# Packages
DOESimulator is divided into 2 packages:
    1) DOERegression
    2) Java Calculus (JSD)

# RUNNING THE PROGRAMS
Using Netbeans 8.2, 
    1) Open DOERegression.java. 
    2) Right Click
    3) Select Run File
