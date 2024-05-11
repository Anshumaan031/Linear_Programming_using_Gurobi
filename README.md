# Linear programming and Gurobi

### Optimization solvers

Optimization solvers are computational tools or algorithms designed to find the best possible solution to an optimization problem. Optimization problems involve finding the optimal values of variables that satisfy certain constraints and either maximize or minimize an objective function.

There are various types of optimization problems, including linear programming, nonlinear programming, integer programming, mixed-integer programming, and more. Optimization solvers employ mathematical and algorithmic techniques to search through the feasible solutions and identify the one that best meets the specified criteria.

Optimization solvers are used in a wide range of fields, including engineering, economics, operations research, data science, machine learning, and many others. They help in making informed decisions, resource allocation, process improvement, and generally finding optimal solutions in complex systems.

### Linear Programming

Linear programming (LP) is a mathematical optimization technique used to find the best outcome in a mathematical model with linear relationships. It is widely used in various fields, including economics, engineering, logistics, and manufacturing, to optimize resource allocation and decision-making.

In an LP problem, you have:

Objective Function: This is a linear equation that you want to maximize or minimize. It represents the quantity you want to optimize, such as profit, cost, or efficiency.

Constraints: These are linear inequalities or equations that define the limitations or restrictions on the variables involved in the problem. Constraints represent real-world limitations on the resources available.

Variables: These are the decision variables that you can control or change within certain bounds to achieve the optimal solution. These variables are usually what you are trying to determine, such as quantities of different products to produce or investments to make.

The goal of linear programming is to find the values of the decision variables that maximize or minimize the objective function while satisfying all the constraints.

##Gurobi

Gurobi is a powerful commercial optimization solver that specializes in solving linear programming (LP) and mixed-integer programming (MIP) problems efficiently. Here's how Gurobi helps in solving LP problems:

High Performance: Gurobi is known for its high performance and efficiency in solving large-scale LP problems. It employs advanced algorithms and optimization techniques to find solutions quickly and accurately.

Modeling Flexibility: Gurobi provides an easy-to-use modeling interface in multiple programming languages (Python, MATLAB, Java, etc.). This allows users to define their LP problems in a natural and expressive way, making it easier to formulate and solve complex optimization problems.

Parallel Processing: Gurobi can take advantage of multi-core processors and distributed computing environments to further speed up the solution process for large and complex LP problems.

Advanced Features: Gurobi offers advanced features such as sensitivity analysis, solution warm-starting, and the ability to handle a wide range of LP problem types, including integer programming and quadratic programming.

Commercial Support: Gurobi offers commercial licenses and provides support, documentation, and updates to users, making it a reliable choice for businesses and organizations.

Overall, Gurobi is a valuable tool for solving linear programming problems efficiently and is widely used in various industries for optimization tasks ranging from supply chain management to financial planning.

## Basic and basic feasible solution

In linear programming (LP), basic solutions and basic feasible solutions are important concepts related to solving LP problems. These concepts are essential for understanding the geometry of the feasible region and for solving LP problems using the simplex method, which is one of the most widely used algorithms for LP.

### Basic Solution:

A basic solution is a specific solution to an LP problem where a subset of the decision variables takes on non-zero values, and the remaining variables are set to zero.

In an LP problem with 'n' decision variables, a basic solution corresponds to fixing 'n' variables and allowing 'n' other variables to be zero.

Basic solutions are typically found at the vertices (corners) of the feasible region, which is the set of all points that satisfy the constraints of the LP problem.

These solutions are crucial because they represent extreme points of the feasible region and are potential candidates for optimal solutions.

Basic solutions may or may not satisfy all the constraints of the LP problem; those that do are called basic feasible solutions.

### Basic Feasible Solution:

A basic feasible solution (BFS) is a basic solution that also satisfies all of the constraints of the LP problem, including both equality and inequality constraints.

In other words, a BFS is a basic solution that lies within the feasible region, meaning it doesn't violate any of the problem's constraints.

Basic feasible solutions are the primary interest when solving LP problems, as they are the candidates for optimal solutions.

The simplex method, which is a widely used algorithm for solving LP problems, starts at a basic feasible solution and iteratively moves to adjacent basic feasible solutions until an optimal solution is reached.

The BFSs are typically found at the vertices (corners) of the feasible region.


![Logo](https://www.google.com/url?sa=i&url=https%3A%2F%2Ftowardsdatascience.com%2Fcausal-inference-with-linear-regression-endogeneity-9d9492663bac&psig=AOvVaw2CGT5n3LS6DgzSIMGMDm60&ust=1693641866228000&source=images&cd=vfe&opi=89978449&ved=0CBAQjRxqFwoTCOD-vuj5iIEDFQAAAAAdAAAAABAE)



## Documentations

[Linear Programming](https://www.analyticsvidhya.com/blog/2017/02/lintroductory-guide-on-linear-programming-explained-in-simple-english/) 

[Python](https://www.python.org/doc/)

[Gurobi](https://www.gurobi.com/documentation/)


## Authors

- [@Anshumaan - <anshuphukan031@gmail.com>](https://github.com/Anshumaan031)
