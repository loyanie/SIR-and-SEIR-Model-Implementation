# BMI 500: Homework 11

Name: Loyani Loyani

Program: CSI PhD

Department: Biomedical Informatics, Emory University

Contact: loyani.loyani@emory.edu

## HW 1: SIR and SEIR Model Implementation for Pandemic Spread 
The objective is to implement and analyze the susceptible-infectious-recovered (SIR) compartmental model to understand the dynamics of infectious disease spread.

### SIR model simulation
This plot simulates the SIR model over a period of 150 days with the following initial conditions
and parameters for a total population of N = 1000 individuals:

- Initial populations: S(0) = 999, I(0) = 1, R(0) = 0,
- Transmission rate: β = 0.3 × 10−3,
- Recovery rate: γ = 0.1.

![SIR model implementation](/images/sirdynamics1.png)

#### Pandemic Dynamics
- The susceptible population starts at 999 and decreases to approximately 59, while the final attack rate: 93.95%
- The infected population peaks at day 38 with 300 infected individuals (which is 30.06% of the total population) and then nearly reaches zero by day 150.
- The recovered population grows from 0 to approximately 940.47 and eventually reaches 94.05% of the total population

### SEIR Model with Births and Deaths
These plots simulate (susceptible-exposed-infectious-recovered (SEIR) Model the for both 365 and 1200 days with S(0) = 990, E(0) = 9, I(0) = 1, R(0) = 0, and parameters
β = 0.3 × 10−3, γ = 0.1, σ = 0.2, and μ = 0.01. Plot the compartment populations over time.

#### Pandemic Dynamics over 365 days
![SIR model implementation](/images/seir_365.png)

#### Pandemic Dynamics over 1200 days
![SIR model implementation](/images/seir_1200.png)
