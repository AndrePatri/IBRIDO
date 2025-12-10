## The IBRIDO framework
A software framework for research in Reinforcement Learning-Augmented Model Predictive Control. IBRIDO glues together several sibling packages:

| Package | Description |
| --- | --- |
| [AugMPC](https://github.com/AndrePatri/AugMPC) | RL-Augmented MPC for Non-Gaited Legged and Hybrid Locomotion |
| [AugMPCEnvs]() | World interfaces (Isaac Sim, MuJoCo, XBot2) and training environments implementations for AugMPC |
| [MPCHive]() | Parallel MPC cluster manager, based on a client-server architecture, for use with data-hungry applications |
| [EigenIPC]() | Provides the shared-memory tensors and other primitives that all components use to exchange states, commands, references, and metadata. |
| [MPCViz]() | RViz-based MPC visualization client that consumes AugMPC/MPCHive topics to render horizon nodes, contacts, and references. |


The framework can be easily installed, configured and experimented with using [ibrido-containers](https://github.com/AndrePatri/ibrido-containers). 

Main framework packages:
- [AugMPC](): 
- [MPCHive](https://github.com/AndrePatri/MPCHive): Python tool for synchronizing and parallelizing clusters of CPU-based MPCs.
- [AugMPCEnvs](https://github.com/AndrePatri/AugMPCEnvs): world interface implementations for AugMPC package.
- [EigenIPC](https://github.com/AndrePatri/EigenIPC): shared matrices built on top of POSIX-IPC and Eigen, shipped with python bindings and NumPy support.
- [MPCViz](https://github.com/AndrePatri/MPCViz): ros-powered minimal tool to visualize MPC solutions and other db data on RViz in realtime.
