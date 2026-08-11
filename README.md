# Ordinary Differential Equations and Numerical Resolution

This repository contains all my practical work completed as part of the Ordinary Differential Equations course for my **Double Bachelor's Degree in Mathematics and Economics** at **Paris-Saclay University**

I present a synthesis of the different numerical methods explored for solving ODEs, as well as a final practical applied to epidemiology

 **Grades obtained :**
* **Graded practical assignment :** 19.5/20
* **Final course grade :** 17/20

---

##  Repository Content

### Practical 1 : Vector fields and integral curves
Introduction to the qualitative study of differential systems. Geometric visualization of trajectories and vector fields to understand the global behavior of solutions without needing an exact analytical expression.

<img width="1366" height="1095" alt="image" src="https://github.com/user-attachments/assets/d69aaada-199a-4d2d-9d13-90d1f8bdf6d3" />


### Practical 2 : Harmonic oscillator & Symplectic Euler Scheme
Numerical integration of Hamiltonian systems. Showing the advantage of the Symplectic Euler scheme over the classic explicit Euler method, particularly for the geometric conservation of physical energy and the long-term stability of closed orbits

<img width="1408" height="569" alt="image" src="https://github.com/user-attachments/assets/5cee10ae-240c-458f-878c-985b5304df00" />


### Practical 3 : Heat equation & Crank-Nicolson Scheme
Numerical treatment of parabolic Partial Differential Equations. Implementation of the implicit Crank-Nicolson scheme using the `scipy.sparse` library for an optimized and fast inversion of tridiagonal systems


<img width="1401" height="868" alt="image" src="https://github.com/user-attachments/assets/e7ae4924-68ff-4553-980a-bcda4a9079b0" />


### Graded Practical : Epidemiological Modeling (SEIR Model)
Modeling population dynamics to a disease spread with an extension of the classic SIR model. 
The population is divided into 4 components :
* **S** (Susceptible) : Healthy but vulnerable individuals
* **E** (Exposed) : Incubation period (infected, but not infectious yet)
* **I** (Infected) : Individuals capable of transmitting the pathogen
* **R** (Recovered) : Healed and immune individuals

<img width="1404" height="896" alt="image" src="https://github.com/user-attachments/assets/28e0df3e-6d63-416f-b23e-8ab120b26a7f" />


Numerical analysis of the non-linear ODE system using the `scipy.integrate.solve_ivp` solver to observe the behavior of the "epidemic peak" and the influence of various contagion parameters.

---

## Technologies and Libraries Used
* **Python**
* **NumPy** : Scientific computing, vector and matrix manipulation
* **SciPy** (`scipy.sparse`, `scipy.integrate.solve_ivp`) : Optimized resolution of sparse systems and numerical integration of initial value problems
* **Matplotlib** : Data visualization, plotting vector fields and dynamic integral curves.
