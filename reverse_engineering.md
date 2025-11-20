# Reverse-Engineering Methodology (Conceptual Verification)

This document summarizes the conceptual reverse-engineering procedure used to map the VR game's mechanics to the proposed framework.

To ensure methodological transparency and reproducibility, we document the procedure used for the reverse-engineering conceptual verification through VR game. The conceptual reverse-engineering procedure in this research aligned with established software reverse engineering methodologies, including system decomposition and abstraction techniques (Chikofsky & Cross 1990; Tilley, 1998). These methods support identifying system functions, mapping operational behaviors, and aligning software components with higher-level conceptual models. We did aka mapping with our proposed framework and the VR game mechanics to theoretically verify the components with proper alignment. 
The conceptual reverse-engineering process followed these steps:


## Steps
The conceptual reverse-engineering process followed these steps:
1.	Expert Triangulation Meeting
Involves three authors from the project:
(a) The main framework designer “Muhammad Ahsan”.
(b) The VR game developer “Matheus Gonçalves”.
(c) A researcher with prior reverse-engineering experience, “Laura Coura”.
The meeting was conducted to trace game mechanics in the XR4Good lab at DECOM, UFOP.
2.	Functional Decomposition of the VR Game
•	Identified all available game components: navigation, tasks, interactions, environment cues, scoring, and system logs.
•	Segmented the game into input events, user actions, feedback mechanisms, and environmental interactions.

3.	Mapping Game Elements to Framework Components
Each game feature was aligned with framework layers:
•	Learning Analytics Model
•	Personalized Learning Layer
•	User Model (Student/Teacher)
•	Student Behavior Model
Example:
navigation patterns → cognitive load & spatial behavior mapping; 
object interactions → performance indicators; 
task completion → LA-derived metrics.
4.	Identification of Missing or Future Components
•	Any part of the framework that the current game did not implement was documented for future extensions (e.g., teacher dashboards, changing slides etc).
5.	Conceptual Verification
•	Verified that framework components could theoretically be operationalized in VR environments.
•	No empirical behavior or user data were used.
6.	Documentation and Open Sharing
•	The mapping matrix, analysis notes, and conceptual alignment diagram will be shared in the open repository to support reproducibility.


## References
- Chikofsky, E. J., & Cross, J. H. (1990). Reverse engineering and design recovery: A taxonomy. *IEEE Software*, 7(1), 13–17.
- Tilley, S. R. (1998). A Reverse‑Engineering Environment Framework. CMU/SEI Technical Report.
