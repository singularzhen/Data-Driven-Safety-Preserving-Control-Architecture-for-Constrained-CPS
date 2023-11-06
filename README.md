# Data-Driven-Safety-Preserving-Control-Architecture-for-Constrained-CPS

In this work, we propose a data-driven networked control architecture for unknown constrained linear cyber-physical systems subject to bounded disturbances capable of detecting and ensuring plant safety in the presence of cyber-attacks on the communication channels. To this end, first, by using data-driven forward reachability analysis, a passive anomaly detector that is local to the controller is designed to detect network attacks. Then, to ensure that intelligent and undetectable attacks will be detected before causing safety risks, a safety verification module, which is local to the plant, is designed based on an outer approximation of the one-step evolution set at each time step. This unit is in charge of activating the emergency controller whenever the control input is deemed unsafe or under the effect of cyber-attacks. Finally, an emergency controller is designed by exploiting a family of data-driven Robust One-Step Controllable (ROSC) Sets and dual-mode set-theoretic model predictive controller to safely confine the system into the closest robust control invariant region in a finite number of steps. Numerical simulations involving a two-tank water system is performed to clarify the proposed solution's capabilities.
