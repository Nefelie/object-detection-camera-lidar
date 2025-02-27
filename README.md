# Autonomous Surface Vessel Perception System
## Project Overview
This project focuses on designing the perception system for an autonomous surface vessel, operating in challenging environments such as the Bering Sea with ice conditions. The system leverages simulation tools, ROS2 integration, and deep learning techniques to enhance obstacle detection and navigational safety.

See [Section 4.5 (Perception System)](https://drive.google.com/file/d/1tmE3nuYLzQt44lAovXXojBtq-xTOMeBq/view?usp=drive_link) in the Group Design Project report for individual contribution to the project. 
My individual [design journal summary](https://drive.google.com/file/d/1-nls2h1e8ZEGSb_KSZ9LLLsPyBMQE_hk/view?usp=drive_link) shows the design process of the perception system. 

![GDP7](https://github.com/user-attachments/assets/7cc6abdb-46e6-4259-9d47-dd7bb5a14a11)


## Features

- Simulated Environment: Developed using Gazebo to model real-world sea conditions, including waves and vessel dynamics.

- Sensor Modeling: Integrated LiDAR and stereo camera models within the ROS2 framework to simulate real-time perception.

- Vision-Based Obstacle Detection: Utilized Meta’s DINO Vision Transformer for feature extraction and attention map visualization.

- Deep Learning Pipeline: Implemented using PyTorch to analyze and interpret self-attention maps, improving model interpretability and performance in complex environments.

## Technologies Used

- Simulation: Gazebo

- Robot Framework: ROS2

- Vessel Dynamics: VRX Simulator

- Deep Learning: PyTorch

- Computer Vision: DINO (Vision Transformer by Meta)
