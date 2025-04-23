# Runge-Kutta methods for solving initial value problems for FE problems with MATLAB
Development stopped (was a free time student project) 💤

## Purpose
This code aimed to solve any **initial value problem (IVP)** of arbitraty order for **finite element (FE)** problems using a **Runge Kutta method (RKM)** spcified by a **Butcher tableau** or method name.

## Limitations
Currently, _only non-adaptive RKM_ are supported. Solution algorithms are currently only given for _explicit_ (not for _implicit_) problems. The latter will later be implemented using the **Newton-Raphson-algorithm** to solve the system of equations at every stage of the RKM.
