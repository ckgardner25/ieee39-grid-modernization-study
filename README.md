# IEEE39-grid-modernization-study
IEEE 39-bus T&amp;D co-simulation in PSSE, PowerWorld, and OpenDSS; analyzed transient stability, OPF, and hosting capacity for a utility-scale hybrid Solar+BESS.

## Goals and Outline
The current project idea is centered around studying what happens when a thermal power generator is replaced with renewable power generation and battery storage, seeing how it affects the distribution and transmission system.  Starting with PSSE and possibly PowerWorld to remove a 250MW thermal generator with the IEEE 39-bus "New England" system and replace it with a solar/battery energy storage (PV+BSEE).  Seeing how that affects the system and research WECC inverter models to see the affected frequency response.

After that, use python with OpenDSS to do a 24-hour QSTS simulation on the system.  My goal is to find out the hosting capacity and see how Volt-VAR control can reduce voltage violations. Lastly, perform a N-1 Contingency and Optimal Power Flow study to find overloaded transmission lines or congestion to better understand transmission decisions that can affect system operation.
