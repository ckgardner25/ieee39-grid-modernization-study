# IEEE39-grid-modernization-study
IEEE 39-bus T&amp;D co-simulation in PSSE, PowerWorld, and OpenDSS; analyzed transient stability, OPF, and hosting capacity for a utility-scale hybrid Solar+BESS.

## Goals and Outline
As renewable energy becomes a larger part of modern power grids, maintaining system stability is becoming challenging. This design study focuses on the IEEE 39-Bus "New England" power system by replacing selected synchronous generators with photovoltaic (PV) generation and Battery Energy Storage Systems (BESS). The goal is to analyze how the system responds during both normal operating conditions and disturbances using transient stability simulations with WECC generic inverter models. I also plan to explore Direct Stability Assessment (DSA) methods, including the PEBS and UEPS techniques, if they can be implemented successfully within the scope of the project.

To complement the transmission study, OpenDSS and Python will be used to perform Quasi-Static Time Series (QSTS) simulations on a distribution feeder. These simulations will evaluate photovoltaic hosting capacity and investigate how Volt-VAR control and Static VAR Compensators (SVCs) can improve voltage regulation and overall system performance.
Finally, N-1 contingency analysis and Optimal Power Flow (OPF) studies will be performed to identify vulnerable areas of the power system, evaluate thermal overloads and congestion, and investigate engineering solutions that improve grid reliability and renewable energy integration.

