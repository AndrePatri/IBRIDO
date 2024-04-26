## IBRIDO
<!-- <h2 align="center" style="text-decoration: none;"> <img src="https://img.shields.io/badge/License-GPLv2-purple.svg" alt="License">

![icon.svg](docs/images/logo.svg)

</h2> -->
A Software Ecosystem for Research in Reinforcement Learning-based Receding Horizon Control.

Main framework packages:
- [LRHControl](https://github.com/AndrePatri/LRHControl): Learning-based Receding Horizon Control exploiting Reinforcement Learning.
- [CoClusterBridge](https://github.com/AndrePatri/CoClusterBridge): tool for bridging a CPU-based control cluster with parallel simulation environments.
- [OmniRoboGym](https://github.com/AndrePatri/OmniRoboGym): wrapper on top of Omniverse Isaac Sim tailored to legged robotics control with learning techniques. 
- [SharsorIPCpp](https://github.com/AndrePatri/SharsorIPCpp): shared matrices built on top of POSIX-IPC and Eigen, shipped with python bindings and NumPy support.
- [RHCViz](https://github.com/AndrePatri/RHCViz): Ros-powered minimal tool to visualize Receding Horizon Control solutions on RViz in realtime.

Other relevant dependencies:
- [IsaacSim](https://developer.nvidia.com/isaac-sim): GPU-accelerated robotics simulator for AI.
- [horizon](https://github.com/ADVRHumanoids/horizon/tree/andrepatri_devel): a trajectory optimization tool, tailored to robotics and based on Casadi.

Container deployment utils: [ibrido-docker](https://github.com/AndrePatri/ibrido-docker).
