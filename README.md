# Introduction to Markov Chains (Linear Algebra Mini-Project)

## Project Overview
This repository contains the research paper, presentation, and source code developed for the mini-project in the **Linear Algebra and its Applications (UE18CS203)** course. 

The project explores **Markov Chains**, which are mathematical systems that undergo transitions from one state to another according to specific probabilistic rules. The core focus is on the "Markov Property"—the principle that a stochastic process is "memory-less," meaning the probability of transitioning to any particular state depends solely on the current state, not the sequence of events that preceded it.

## Key Concepts Explored
* **Discrete-Time Markov Chains:** Modeling events that happen in distinct, countable steps.
* **Transition (Stochastic) Matrices:** Constructing square matrices where rows/columns represent probability vectors of transitioning between states.
* **State Vectors:** Calculating the probability of the system being in a particular state after *n* transitions ($S_n = S_0P^n$).
* **Steady-State Convergence:** Utilizing eigenvalues and eigenvectors to find the long-term equilibrium of a system where probabilities settle into a constant state.

## Real-World Applications Analyzed
The report breaks down the application of matrix mathematics to several real-world scenarios:
1. **Weather Forecasting:** Predicting sunny vs. rainy days using simple 2x2 transition matrices.
2. **Voting Behavior:** Estimating vote shifts between political parties (e.g., Congress, BJP, and Rest) over successive elections.
3. **Financial Market Trends:** Using historical data to predict the probability of Bull, Bear, or Stagnant markets converging over time.
4. **Population Dynamics:** Modeling migration between cities and suburbs to calculate the exact population distribution when net movement reaches zero.

## 🛠️ Tools & Technologies Used
* **Scilab:** Used for advanced matrix computations, including calculating eigenvalues/eigenvectors and performing Gaussian elimination.
* **Python (NumPy, Pandas, Matplotlib):** Used to iterate transition matrices and plot the convergence of probabilities to visualize steady states.

## 📂 Repository Structure
* `LA_PES1201801580.pdf`: The comprehensive final project report detailing all mathematical proofs, theories, and application examples.
* `LINEAR ALGEBRA MINI PROJECT PPT.pdf`: The slide deck used for project presentation.
* `city.sce`: A Scilab script implementing Gaussian elimination to solve the steady-state vector $Ax = 0$ for the city/suburb population movement example.
* `transition2.jpg`: State transition diagrams used in the report.

## Team Members
* Anup N. (PES1201800283)
* K. Sreesh Reddy (PES1201801580)
