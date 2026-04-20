# Asservissement_Num-rique_RANDRIANJAKA_Jefferio_commande-par-backstepping-d-un-syst-me-non-lin-aire
# Backstepping Control for Nonlinear Systems

Implementation of a backstepping controller for a second-order nonlinear system using Python and SciPy.

## System
ẋ₁ = a·x₁² + x₂
ẋ₂ = b·x₁·x₂ + u

## Requirements

```bash
pip install numpy scipy sympy matplotlib
RUN
python backstepping_simulation.py

OUTPUT
Console: Control law and simulation status

Graphs: State trajectories, Lyapunov function, control signal

CSV file: backstepping_results.csv
Parameters (edit in code)
Parameter	Default
a, b	1.0, 0.5
k₁, k₂	5.0, 10.0
x₁(0), x₂(0)	1.0, 0.0
Simulation time	10 s
Key result
The Lyapunov function V₂ decreases exponentially → asymptotic stability ✓

Author
RANDRIANJAKA Jefferio 
