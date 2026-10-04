<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=200&section=header&text=Safwan&fontSize=70&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Projects%20%26%20Tech%20Stack&descAlignY=58&descSize=22" alt="Header" />

</div>

## 🛠️ Tech stack

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Shell](https://img.shields.io/badge/Shell-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=for-the-badge&logo=cmake&logoColor=white)

**Robotics and simulation**

![ROS 2](https://img.shields.io/badge/ROS%202-22314E?style=for-the-badge&logo=ros&logoColor=white)
![Gazebo](https://img.shields.io/badge/Gazebo-FF6F00?style=for-the-badge)
![MoveIt 2](https://img.shields.io/badge/MoveIt%202-1E88E5?style=for-the-badge)
![Nav2](https://img.shields.io/badge/Nav2-5C2D91?style=for-the-badge)
![ros2_control](https://img.shields.io/badge/ros2__control-37474F?style=for-the-badge)
![RViz2](https://img.shields.io/badge/RViz2-546E7A?style=for-the-badge)
![URDF/Xacro](https://img.shields.io/badge/URDF%20%2F%20Xacro-6D4C41?style=for-the-badge)
![robot_localization](https://img.shields.io/badge/robot__localization%20(EKF)-00796B?style=for-the-badge)

**Machine learning, vision and data**

![YOLOv8](https://img.shields.io/badge/YOLOv8-111F68?style=for-the-badge)
![XGBoost](https://img.shields.io/badge/XGBoost-EB6C1F?style=for-the-badge)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge)
![Pygame](https://img.shields.io/badge/Pygame-2E7D32?style=for-the-badge)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)

---

## 🤖 Robotics

| Project | What it is | Stack |
| --- | --- | --- |
| [mecanum_wheel_bot](https://github.com/Safwanny/mecanum_wheel_bot) | Modular simulation and control package for a four-wheel mecanum platform. 44 movable joints (4 wheels plus 40 passive rollers), 360° LiDAR, IMU, front RGB camera, EKF-based localization, holonomic teleop. Part of a team-built mecanum robot where I design the mechanical and electronics parts; navigation with LiDAR and Nav2 works in mapped environments, and real hardware is coming step by step. | ROS 2 Jazzy, Gazebo Harmonic, ros2_control, robot_localization, URDF/Xacro, RViz |
| [6DOF_arm](https://github.com/Safwanny/6DOF_arm) | 6-DOF manipulator arm built from scratch and integrated with MoveIt 2. C++ API for named, joint and pose goals plus Cartesian paths, gripper control, and a custom `PoseCommand` interface. | ROS 2, MoveIt 2, C++, ros2_control, URDF/Xacro, RViz2 |
| [bumperbot](https://github.com/Safwanny/bumperbot) | Differential-drive mobile robot simulation with wheel velocity control and odometry feedback in RViz. Localization, mapping, planning and navigation are planned next. | ROS 2 Jazzy, Gazebo, ros2_control, RViz |
| [my_robot](https://github.com/Safwanny/my_robot) | ROS 2 packages to simulate and visualize a custom mobile robot with a camera, including a ROS–Gazebo bridge and keyboard teleop. | ROS 2, Gazebo, ros_gz_bridge, URDF/Xacro, RViz2 |

## 🧠 Control, simulation and signal processing

| Project | What it is | Stack |
| --- | --- | --- |
| [RL_Driving_Sim](https://github.com/Safwanny/RL_Driving_Sim) | 2D self-driving simulation with five distance sensors, a Gym-style `reset`/`step` API, a discrete action space, baseline agents, and manual driving with CSV data logging. Built to validate sensors and control before adding a DQN agent. | Python, Pygame, NumPy, pytest |
| [Hand-Tremor-Filtering](https://github.com/Safwanny/Hand-Tremor-Filtering) | Experiments with eight filters (Butterworth, Bessel, notch plus Butterworth, One-Euro, moving average, EMA, Savitzky–Golay, Kalman) to smooth trackpad input, with raw vs. filtered paths and frequency-spectrum views. | Python, Matplotlib |

## 👁️ Computer vision

| Project | What it is | Stack |
| --- | --- | --- |
| [Object-Detection](https://github.com/Safwanny/Object-Detection) | Object detection script with a camera test, using the pretrained YOLOv8m model. | Python, YOLOv8 |
| [Object-Tracking](https://github.com/Safwanny/Object-Tracking) | Object tracking project with a configurable tracker (`tracker.yaml`) and a drawing module. | Python |
| [Brain-Tumor-Classification](https://github.com/Safwanny/Brain-Tumor-Classification) | Classification of brain tumors from medical images, with a training script and evaluation notebooks. | Python, Jupyter |

## 📈 Machine learning

| Project | What it is | Stack |
| --- | --- | --- |
| [Battery-RUL-Prediction](https://github.com/Safwanny/Battery-RUL-Prediction) | Predicting the remaining useful life of batteries with ML. | Python |
| [MNIST-Digit-Classification](https://github.com/Safwanny/MNIST-Digit-Classification) | Neural network for recognizing handwritten digits. | Deep learning, Jupyter |
| [Calories-Burnt-Prediction](https://github.com/Safwanny/Calories-Burnt-Prediction) | Regression model predicting calories burnt during exercise. | XGBoost, Jupyter |
| [Vehicle-Price-Prediction](https://github.com/Safwanny/Vehicle-Price-Prediction) | Linear regression model for predicting vehicle prices. | Linear regression, Jupyter |
| [Iris-Flower-Classification](https://github.com/Safwanny/Iris-Flower-Classification) | Classifying two types of Iris flowers. | SVM, Jupyter |
| [Kyphosis-Detection](https://github.com/Safwanny/Kyphosis-Detection) | Detecting kyphosis with decision trees and a random forest classifier. | Decision trees, random forest, Jupyter |
| [Spam-Messages-Detection](https://github.com/Safwanny/Spam-Messages-Detection) | Detecting spam messages. | NLP, Jupyter |
| [Yelp-Review-Classification](https://github.com/Safwanny/Yelp-Review-Classification) | Classifying Yelp reviews as 1 or 5 stars. | NLP, Jupyter |

## 🏭 Industry work

- **Robert Bosch, Renningen:** bachelor thesis on agentic AI for troubleshooting LLM testbenches
- **Robert Bosch:** earlier internship on radar ECU testbenches

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,100:0f2027&height=100&section=footer" alt="Footer" />
</div>
