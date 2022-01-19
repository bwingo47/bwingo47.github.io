---
title: "Momentum-Aware Planning Synthesis for Dynamic Legged Locomotion"
permalink: /pub_summary/2021-3-momentum-aware-summary
citation: 'Z. Zhou, <b>B. Wingo (Q. Huang)</b>, N. Boyd, S. Hutchinson, and Y. Zhao, &quot;Momentum-Aware Planning Synthesis for Dynamic Legged Locomotion.&quot; <i>Proceedings of Dynamic Walking</i>, July, 2021.'
---

Dynamic motion generation for legged robots remains challenging due to the non-cyclic contact and highly nonlinear rigid body dynamics. Trajectory optimization (TO) with
embedded contact dynamics generates elegant motions, yet
solving the associated nonlinear program (NLP) is still computationally intractable. A Hierarchical gait→centroidal→wholebody pipeline is commonly employed to reduce the planning
complexity. However, additional constraints projecting wholebody information to the centroidal level are required to ensure
feasible solutions. In practice, these constraints are often
computationally expensive and difficult to define, especially
when involving angular momentum. On the contrary, some adopt a distributed approach, updating centroidal and
whole-body models in an alternating fashion. However, contact
sequences still need to be pre-specified, and results are only
shown for simple walking motions. We improve upon the
existing distributed framework by introducing a centroidal
optimization capable of discovering both contact sequences
and angular momentum trajectories. A new set of consensus
constraints is also formulated. Lastly, we evaluate different
acceleration techniques to improve the global convergence of
the proposed distributed optimization.