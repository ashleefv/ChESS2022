5.0 MATLAB Live Script and Jupyter Notebook Tutorials
5.0.1 M0_HowToCreate.mlx & J0_HowToCreate.ipynb
M0_HowToCreate.mlx covers how to create MATLAB Live Scripts. J0_HowToCreate.ipynb covers how to use Google Colab to create Jupyter Notebooks.
5.1 Linear Equations
5.1.1 M1_MassBalance.mlx (separate solution file available)
●	Intended student use case: This file is designed as a homework problem. 
●	Numerical technique: Format mass balances as a linear algebraic system in matrix-vector form. Explore the Gauss elimination algorithm implementation.
●	ChemE application: Linear mass balances on a reaction/separation system with recycle. Material and energy balances (MEB)
●	Workshop activity: Explore a Live Script formatted as a homework assignment. Possibly solve the problem.
5.2 Nonlinear Equations
5.2.1 M2_NonlinearSystems.mlx (separate solution file available)
●	Intended student use case: This file contains three fully worked examples and a case study that requires students to input a single vector of initial guesses to solve the problem.
●	Numerical technique: Newton’s method, Picard’s method, and Newton-Raphson
●	ChemE application: Nonlinear mass balances on a reaction/separation system with recycle. Material and energy balances (MEB), reaction engineering
●	Workshop activity: Explore a Live Script formatted as a worked example and complete the Case Study. Reflect on how this might be modified for deployment in a class other than numerical methods.
5.2.2 M3_PipeNetwork.mlx & J3_PipeNetwork.ipynb
●	Intended student use case: This is a template for use in the in-class activity based a previous video lecture. Part a of the problem is done in class and parts b and c are homework.
●	Numerical technique: System of Non-linear equations 
●	ChemE application: Pipe flow networks. How fast does the fluid flow down each pipe segment. Fluids
●	Workshop activity: Save a copy of this template and recalculate the flowrates by replacing the constant friction factor with a friction factor that is a function of Reynolds number. Then discuss the difficulties you had in doing this task.
5.3 Ordinary Differential Equations (ODEs), Initial Value Problems
5.3.1 M4_NonisothermalPFR.mlx & J4_NonisothermalPFR.ipynb (separate solution files available)
●	Intended student use case: This file is designed to be used by students as a worked example/case study for part a and then as a homework problem or in-class exercise for part b and part c.
●	Numerical technique: This case study involves solving a system of first-order ODEs using a given set of initial conditions and the built-in MATLAB/Python ODE solver
●	ChemE application: This case study models the behavior of parallel reactions in a nonisothermal plug flow reactor (PFR). Reaction engineering
●	Workshop activity: Complete part b and part c of the problem.
5.3.2 M5_ParEstKinetics.mlx & J5_ParEstKinetics.ipynb (separate solution files available)
●	Intended student use case: This file is designed to be used by students as a worked example/case study for the first problem and then as a homework problem for the 2nd problem.
●	Numerical technique: parameter estimation using curve fitting built-in functions applied to a dynamic model involving multiple ODEs
●	ChemE application: fitting reaction rate constants to data for the kinetics of a fluid catalytic cracker. Reaction engineering, data analysis/lab
●	Workshop activity: Explore the worked example/case study for the first problem and then look at the solution file for the 2nd problem. How might you adapt this type of case study/worked example and then “your turn” problem for one of your classes?
5.3.3 M6_TankDrainage.mlx & J6_TankDrainage.ipynb
●	Intended student use case: This template is based on an example problem in Felder, Rousseau, and Bullard. Before the class the students watch a video lecture and then in class, they use this template to solve in-class lecture and homework problems.
●	Numerical technique: ODE solver with initial conditions
●	ChemE application: This is a simple mass balance on an unsteady-state well-mixed tank. Material and energy balances (MEB), controls
●	Workshop activity: modify the template to solve the problem in which the mass flowrate out of the tank is mdotOUT=4.77*m^0.5 in which m is the mass in the tank. Discuss the difficulties that you had in modifying this template.
5.4 ODEs, Boundary Value Problems
5.4.1 M7_StefanTubeDiffn.mlx & J7_StefanTubeDiffn.ipynb
●	Intended student use case: At Rowan this is the first example of a 2nd order ODE with split boundary values which requires a shooting technique to solve. The students first watch a video out of class and the solve this problem in class activity using this template.
●	Numerical technique: ODE solver with both a manual iteration and an automated iteration for determining the split boundary values.
●	ChemE application: This is the classic problem of evaporation of a pure liquid and resulting diffusion of a gas down a tube. The device is used to obtain gas-phase diffusion coefficients. Fluids, mass transfer
●	Workshop activity: modify this template to solve this problem with a linear temperature profile given at the end. Then discuss the difficulties you had in doing this task.
5.4.2 M8_LaminarPipe.mlx & J8_LaminarPipe.ipynb
●	Intended student use case: This is a template for use with a video lecture in a flipped class. In-class they solve the modified problem by replacing the constant viscosity and density with ones that vary with temperature.
●	Numerical technique: ODE solver with an automated iteration for determining the split boundary values.
●	ChemE application: Classic modeling of laminar pipe flow. The students compare their numerical solution with the analytical solution and then perform the calculation with a given temperature profile in which there is no analytical solution. Fluids
●	Workshop activity: modify this template to solve this problem with a linear temperature profile in which the pipe wall is at 45°C and the centerline (r=0) is at 25°C. The correlations for density and viscosity of water are given in the template. Discuss the difficulties that you had in modifying this template.
5.5 Partial Differential Equations
5.5.1 M9_HeatTransfer.mlx (separate solution file available)
●	Intended student use case: This is a worked example that students are asked to modify/manipulate to explore the behavior of the system.
●	Numerical technique: Method of lines, MATLAB built-in ode solver ode15s
●	ChemE application: Heat transfer
●	Workshop activity: Explore a fully worked example as an Interactive textbook or in-class activity. Manipulate the requested values (like a student).
