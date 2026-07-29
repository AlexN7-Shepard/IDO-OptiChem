# IDO-OptiChem
Projects related to Process & Chemical Engineering: Integration of Design and Operation

Public portfolio collecting past projects and ideas in process and chemical engineering. The repository reflects my interest in making simulations closer to reality by accounting for uncertainty, dynamic behavior, and the interaction between design and operation. Chemical engineering problems are often studied in a simplified way: a process is designed for a nominal steady state, and control considerations are added later. However, real systems are dynamic, uncertain, and often operate far from ideal assumptions.

This repository highlights work within the broader Integration of Design and Operation (IDO) perspective, where process design, operability, and control-related questions are considered together. I was introduced to IDO at the DBTA at TU Berlin : https://www.tu.berlin/dbta . 

## Why uncertainty matters
Real processes are affected by many sources of variability, both endogenous and exogenous. 
### Endogenous uncertainties : 
Arise from the system itself, such as fluctuations in reaction kinetics, heat transfer coefficients, thermodynamic properties, or catalyst deactivation over time. 
### Exogenous uncertainties : 
Come from the environment and operating context, including changes in feed composition, ambient conditions, energy availability, and market prices. Deterministic models are useful, but they often miss the practical complexity that makes real systems difficult to design and operate robustly. Relying only on nominal assumptions can lead to overly conservative worst-case margins that reduce profitability and efficiency. For that reason, several of the projects here explore how uncertainty can be represented more realistically in process models, and how simulation assumptions affect the quality of the conclusions drawn from them.

## Role of Stochastics and Optimization
Here, Optimization is used to identify experimental settings, operating conditions, or parameter choices that improve model quality and increase the information gained from a study. In this sense, it serves as a practical tool for designing more informative experiments and more reliable simulation-based investigations.

However, many process and chemical engineering problems are not deterministic. Uncertainty in parameters, disturbances, and operating conditions means that a single optimal solution is often not sufficient. For this reason, the repository also turns to stochastic optimization, which explicitly accounts for variability and evaluates performance across multiple possible scenarios rather than only one idealized operating point.

Within this framework, key methodologies include:

### Two-stage stochastic programming: 
Balancing “here-and-now” structural design decisions, such as reactor volume or heat exchanger area, with “wait-and-see” operational recourse actions, such as adjusting coolant temperatures or feed rates as uncertainties unfold.

### Chance-constrained and robust optimization: 
Ensuring that critical process constraints, such as maximum temperature limits or minimum purity requirements, are satisfied with a prescribed probability or under bounded uncertainty.

## Rules

No license is provided : the code is not available for redistribution or reuse.
