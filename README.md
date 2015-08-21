# LKH_TSP
A set of tools to solve TSP problems using the LKH solver

**What is LKH**

LKH is an effective implementation of the Lin-Kernighan heuristic for solving the Traveling Salesman Problem. The Lin-Kernighan solver (also called the Lin-Kernighan-Helsgaun solver) is among the most efficient solvers of the TSP and it is employing the concept of k-opt moves. An implementaton of this solver is found online following this link: 

http://www.akira.ruc.dk/~keld/research/LKH/ 

From this site you can download and compile the code following the relevant instructions. Considering that this process is done correctly, this repo provides simple tools to easily invoke this functionality. 

**Python interface**
Within *python* a python script called *InvokeLKH.py* interfaces a compiled version of the LKH TSP Solver and exports the solution in the form of a file. To run the script: 

    $ python InvokeLKH.py

**MATLAB interface**
Within *matlab* a matlab function called *LKH_TSP.m* interfaces a compiled version of the LKH TSP Solver and exports the solution to its output argument. The function syntax is: 

    TSPsolution = LKH_TSP(CostMatrix,pars_struct,fname_tsp,LKHdir,TSPLIBdir)

Feel free to use these simple functions which are released mostly to motivate those working on TSP to use the LKH solver. 

[Kostas Alexis](mailto:konstantinos.alexis@gmail.com)
