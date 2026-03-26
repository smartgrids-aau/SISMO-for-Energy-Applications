#	SISMO for Energy Applications
Slime Mold Algorithm  •  Bio-inspired Computing  •  Energy Networks  •  Optimization

The SISMO (SImulation of Slime MOlds) algorithm is an open-source, bio-inspired simulation tool implemented in NetLogo. Inspired by the foraging behavior of the slime mold Physarum polycephalum — which finds shortest paths between food sources through its self-organizing tubular network — SISMO has been successfully applied to transportation and power transmission network planning.  In a recent study, SISMO was adapted to generate a repair plan for the Carinthian power transmission network following a hypothetical electromagnetic pulse (EMP) attack. The results demonstrated that applying graph layout algorithms (Force Atlas, Force Atlas2, Yifan-Hu Proportional) as a preprocessing step significantly improved SISMO's ability to reconstruct realistic network topologies, with F1-scores improving from 0.36 (original geographic layout) to 0.43 (Yifan-Hu preprocessing).  This project invites students to identify a new energy-related application problem and investigate whether SISMO can be productively applied to it — extending the previous work and exploring the broader potential of bio-inspired algorithms in the energy domain.

## Research Questions
*	Which classes of energy network problems are well-suited to bio-inspired slime mold algorithms, and which are not?
*	How does the choice of graph preprocessing algorithm affect SISMO's accuracy and computational cost for energy network applications?
*	Under what conditions does SISMO offer advantages over classical network optimization methods?

## Tasks
*	Conduct a literature review of bio-inspired optimization algorithms and their applications in energy systems.
*	Identify a concrete energy application problem that can be modeled as a network optimization task (e.g., microgrid topology design, EV charging network placement, district heating network planning, smart meter rollout routing).
*	Adapt and configure SISMO for the selected application, including coordinate preprocessing and graph layout steps as needed.
*	Run simulations and evaluate results using appropriate metrics (precision, recall, F1-score, or problem-specific KPIs).
*	Compare SISMO's performance against at least one classical optimization baseline (e.g., minimum spanning tree, Dijkstra, genetic algorithm).
*	Document findings and provide recommendations for further development of SISMO in energy contexts.


## Reading List
*	Wogatai, K., Winkler, J., Elmenreich, W. "A Graph-Based Approach for Applying Biologically-Inspired Slime Mold Algorithms for Repairing a Power Transmission Network after an Electromagnetic Pulse Attack." 2nd International Conference on Power Systems and Electrical Technology (PSET), 2023.
*	Tero, A., Takagi, S., Saigusa, T. et al. "Rules for Biologically Inspired Adaptive Network Design." Science, 2010.
*	Elmenreich, W., de Meer, H. "Self-organizing networked systems for technical applications: A discussion on open issues." International Workshop on Self-Organizing Systems, Springer, 2008.
