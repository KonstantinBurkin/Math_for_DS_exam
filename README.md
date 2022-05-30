# Optimisation algorithms
  
## Introduction
My exam project for MSU course "The introduction course to math for data science", Fall 2021 - Spring 2022. 
The program of the course can be found [here](https://github.com/MSUcourses/Data-Analysis-with-Python/tree/main/Math) or [here](https://github.com/amkatrutsa/msu_intro_ds2021). Exam consists of 4 problems describing convergence of 4 iterative optimisation algorithms using the example of function minimisation. Optimisation algorithms include: Gradient descent, Heavy ball descent, Accelerated gradient descent, Newton's method.

## Assignment
Objective: Solve 4 problems using the example of the $f(x)$ function minimization.<br><br>
$$f(x)\ =\ ∣∣Ax−b∣∣^3_{2} $$  
m = 100, n = 10, np.random.seed(0);<br>
Generate matrix: A = np.random.randn(m, n).<br>
Generate matrix: b = np.random.randn(m).<br>
The initial approximation is the zero vector: $x_0$ = jax.numpy.zeros(n)
1. How many iterations does the gradient descent method with a constant step of  $α=10^{−4}$  take to achieve an accuracy in gradient norm less than $10^{−4} $ ?
2. How many iterations does the heavy ball method with a constant step of $α = 10^{-4}$ and coefficient $β = 0.5 $ take to achieve an accuracy in the gradient norm less than $10^{-4} $ ?
3. How many iterations does the accelerated gradient method with a constant step of $α = 3* 10^{-4} $ take to achieve an accuracy in gradient norm less than $10^{-4}$ ?
4. After how many iterations does Newton's method with a constant step of $α = 10^{-1} $ begins to stagnate, that is, the gradient norm stops changing? In your answer, indicate the number of iteration k such that the value of the gradient norm at the next iteration k+1 remains the same.<br>
What rate of convergence of Newton's method is observed in the norm of the gradient?
  
## Files:  
- **Optimisation_algorithms.ipynb** - The description of the problem, initial conditions, solution, and visual answer.
- **Optimisation_algorithms_supplementary.ipynb** - Additional code needed to convert the notebook to html.  
   
   
 Created by the end of March, 2022.
