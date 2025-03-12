# ReSynthAI: Physical-Aware Logic Resynthesis for Timing Optimization using AI


### Contest Introduction

With scaling and the slowdown in Moore’s law, EDA tools must work increasingly harder to achieve power, performance, and area (PPA) specifications.  Logic synthesis, a critical part of the design cycle typically does not contain physical information, and any timing optimization that is performed as a part of logic synthesis or immediately after logic synthesis is sub-optimal as it is unaware of the locations of cells, wire lengths, and parasitics. Further, netlist optimization that includes repairing timing and electrical violations is largely heuristic-based at all the stages of the flow, increasing the complexity of the challenge to generate designs with good quality results (QoR). 

Netlist optimization for fixing timing and electrical violations can include a variety of transformations, including logic gate sizing and Vt swaps, buffer insertions or removal, gate cloning, and logic restructuring. It is often challenging to decide which of the above netlist transformations or sequence of transformations must be applied and in what order for the best QoR. The problem is challenging due to (i) the non-convexity of the delay models, (ii) the discrete space of available logical equivalent gates in the library,  (iii) the number of near-critical paths, (iv) the tradeoff between power and timing, and (iv) the resource availability constraints which prevent the exploration of the complete design space.  

The contest aims to overcome these challenges through physically-aware logic resynthesis techniques and drive academic research in early-stage design optimizations for better post-placement QoR. In this context, the contest serves three purposes:

1. Explore the state-of-the-art algorithms for physical-aware resynthesis to drive academic research to generate scalable algorithms for gate sizing, gate cloning, buffer insertion or removal, Vt swapping, and logic restructuring using ML (supervised, unsupervised, or reinforcement learning-based techniques)
2. Lower the barrier to entry for non-EDA experts by converting traditional EDA problems to an ML-solvable problem through ML-friendly data representation formats.
3. Release benchmarks and create a contest leaderboard for physical-aware resynthesis and QoR improvement post-placement in a FinFET technology node with evaluation scripts to accelerate research.


### More information will be added soon
