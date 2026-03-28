# ROBOTIC_LASER_WELDING_PROJECT
# Automated Offline Programming for Robotic Laser Welding

This repository contains the ongoing development of a graduation project focused on automated offline programming (OLP) for robotic laser welding systems.

# Project Overview

The main objective of this project is to develop a software framework that converts CAD-based welding paths into precise and executable robot trajectories.

Using STEP files exported from CAD environments (in our project, it is Autodesk Inventor), the system processes geometric data and generates trajectory information for industrial robotic applications.

The core workflow includes:

- CAD data import and processing
- Welding path extraction with different approaches
- Trajectory generation
- Preparation for simulation and robot execution

The implementation is based on **Python** and the **OpenCascade (pythonocc)** library.


# Current Status

This project is currently under active development.

The initial phase focuses on:

- Reading and parsing STEP files
- Extracting welding paths from CAD geometry
- Discretizing geometric features into trajectory points
- Generating basic robot motion data

Future work may/can include:

- Interactive welding path selection by a python screen 
- Digital twin integration and simulation
- Collision detection and reachability analysis
- Robot-specific code generation (probably KUKA)
- Machine learning-based trajectory optimization


## Academic Context

This project is conducted as a **senior (4th year) graduation project** in the Department of Electrical and Electronics Engineering at Hacettepe University.

The work is carried out under the supervision of **OTES Elektronik Sanayi ve Ticaret A.Ş.**, within an industrial collaboration framework.

##  Technologies Used

- Python
- OpenCascade (pythonocc)
- CAD (as STEP format)
- Robotics & trajectory planning concepts examined on articles and other industry 4.0 improvements

#  Future Vision

The long-term goal of this project is to build a scalable and intelligent system that:

- Automatically interprets complex CAD geometries
- Generates optimized, collision-free robot trajectories
- Integrates with digital twin environments
- Adapts to real-world conditions using data-driven approaches



