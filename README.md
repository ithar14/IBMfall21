# IBM Quantum Challenge Fall 2021
Oct 27 — Nov 05

a series of exercises designed to showcase some of quantum computing's different industry applications using Qiskit's application modules: Finance, Nature, Machine Learning, and Optimization.

## Qiskit Finance - Optimizing your portfolio with quantum computers
Portfolio optimization is a crucial process for anyone who wants to maximize returns from their investments. In this challenge, you will learn some of the basic theory behind portfolio optimization and how to formulate the problem so it can be solved by quantum computers. During the process, you will learn about Qiskit's Finance application class and methods to solve the problem efficiently.

Problem: Solve a four-stock portfolio optimization problem with a goal to find out a combination of assets that will minimize the tradeoff between risk and return.

Level: Foundational
* Learn how to use the PortfolioOptimization() method in Qiskit's Finance module to convert the portfolio optimization into a quadratic program.

* Implement VQE to solve a four-stock portfolio optimization problem based on the instance created in challenge 1a.

* Solve the same problem using QAOA with three budgets and double weights for any of the assets in your portfolio.

## Qiskit Nature - Band gap calculation of OLED molecules
Quantum computers can be used for studying the electronic structure and dynamic properties of complex molecules and materials. With this challenge, you will use Qiskit to describe quantum computations of the “excited states” or high energy states, of industrial chemical compounds that could potentially be used in the fabrication of efficient organic light emitting diode (OLED) devices.

Problem: Define target molecules as an eletronic structure problem and apply quantum algorithms to estimate the correct bandgap between reduced molecular orbitals.

Level: Foundational
* Understanding the atomic orbitals (AO), molecular orbitals (MO) and how to reduce the number of orbitals using active space transformation.
* Calculating ground state energy of PSPCz molecule using NumPy and Variational Quantum Eigensolver (VQE).
* Calculating excited state energy of PSPCz module using quantum Equation-of-Motion (QEOM) algorithm.
* Running VQE on the cloud (simulator or real quantum system) using Qiskit Runtime.

## Qiskit Machine Learning - Image classification by QSVM
Machine learning is a technology that has attracted a significant amount of attention due to its high performance and versatility, and quantum computation has the potential to further enhance it. In this challenge, you will implement image classification models using one of the methods of quantum machine learning; Quantum Support Vector Machine (QSVM).

Problem: Implement 3-class image classifier with QSVM and achieve better accuracy with smaller feature map circuits.

Level: Intermediate

* QSVM for binary classification of MNIST: familiarize yourself with a typical workflow for QSVM and find the best combination of dimentions/feature maps.

* QSVM for 3-class classification of Fashion-MNIST

## Qiskit Optimization - Battery Revenue Optimization
Battery storage systems have provided a solution to flexibly integrate large-scale renewable energy in a power system. The performance of a battery decreases while it is used, so you need to consider the degradation of each battery for figuring out the optimal battery scheduling. In this challenge, you are asked to optimize the battery revenue using a quantum computer and find the lowest circuit cost and circuit depth.

Problem: Solve the battery revenue optimization problem with the lowest circuit cost and circuit depth. Achieve better accuracy with smaller circuits. You can receive a badge for solving all the challenge exercises up to 4b. In addition, you can obtain a score with ranking by solving the last exercise 4c in this challenge.

Level: Advanced
* Simple knapsack problem with QAOA: familiarize yourself with a typical knapsack problem and find the optimized solution with QAOA.

* Battery revenue optimization with Qiskit knapsack class: learn the battery revenue optimization problem and find the optimized solution with QAOA.

* Battery revenue optimization with your own quantum circuit: implement the battery revenue optimization problem to find the lowest circuit cost and circuit depth. Achieve better accuracy with smaller circuits. 
