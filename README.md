## The IBRIDO framework
A software framework for research in Reinforcement Learning-Augmented Model Predictive Control. IBRIDO glues together several sibling packages:

| Package | Description |
| --- | --- |
| [AugMPC](https://github.com/AndrePatri/AugMPC) | RL-Augmented MPC for Non-Gaited Legged and Hybrid Locomotion |
| [AugMPCEnvs](https://github.com/AndrePatri/AugMPCEnvs) | World interfaces (Isaac Sim, MuJoCo, XBot2) and training environments implementations for AugMPC |
| [MPCHive](https://github.com/AndrePatri/MPCHive) | Parallel MPC cluster manager, based on a client-server architecture, for use with data-hungry applications |
| [EigenIPC](https://github.com/AndrePatri/EigenIPC) | Provides the shared-memory tensors and other primitives that all components use to exchange states, commands, references, and metadata |
| [MPCViz](https://github.com/AndrePatri/MPCViz) | Minimal RViz-based tool for visualizing MPC solutions in real-time |


The framework can be easily installed, configured and experimented with using [ibrido-containers](https://github.com/AndrePatri/ibrido-containers). 
