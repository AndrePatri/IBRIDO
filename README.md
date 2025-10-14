## IBRIDO
<!-- <h2 align="center" style="text-decoration: none;"> <img src="https://img.shields.io/badge/License-GPLv2-purple.svg" alt="License">

![icon.svg](docs/images/logo.svg)

</h2> -->
A Software Ecosystem for Research in Reinforcement Learning-based Model Predictive Control.

Main framework packages:
- [AugMPC](https://github.com/AndrePatri/AugMPC): Learning-based Receding Horizon Control with Reinforcement Learning and Model Predictive Control.
- [MPCHive](https://github.com/AndrePatri/MPCHive): tool for bridging a CPU-based control cluster with vectorized simulation environments.
- [AugMPCEnvs](https://github.com/AndrePatri/AugMPCEnvs): specific environment implementations for AugMPC package.
- [EigenIPC](https://github.com/AndrePatri/EigenIPC): shared matrices built on top of POSIX-IPC and Eigen, shipped with python bindings and NumPy support.
- [MPCViz](https://github.com/AndrePatri/MPCViz): Ros-powered minimal tool to visualize Receding Horizon Control solutions on RViz in realtime.

Other relevant dependencies:
- [IsaacSim](https://developer.nvidia.com/isaac-sim): GPU-accelerated robotics simulator for AI. Employed for training 
- [xbot2_mujoco](https://github.com/ADVRHumanoids/xbot2_mujoco) - optional: Mujoco simulator support for the XBot2 RT middleware. Used for validation before real-world deployment.
- [horizon](https://github.com/ADVRHumanoids/horizon/tree/andrepatri_devel): a Trajectory Optimization tool, tailored to robotics and based on Casadi. Backbone of the employed MPC controllers.

All the ecosystem can be easily installd and configured using [ibrido-containers](https://github.com/AndrePatri/ibrido-containers). 
