# ROS2 Turtle Controller

This project is a ROS2 application built using Python (`rclpy`) to control the turtlesim simulator.

It demonstrates core ROS2 concepts including:
- Nodes
- Timers
- Publishers
- Service calls

---

## 📌 Features

- Custom ROS2 node (`turtle_controller`)
- Automatically moves turtle in a circular motion
- Uses `/turtle1/set_pen` service to change drawing color
- Basic ROS2 architecture using `rclpy`

---

## 🧠 What I Learned

- How ROS2 nodes are structured
- How to use timers and callbacks
- How to interact with services in ROS2
- How to build and run a ROS2 workspace

---

## ⚙️ Requirements

- Ubuntu 22.04
- ROS2 Humble
- Python 3

---

## 📦 Setup

### 1. Clone the repository
```bash
git clone https://github.com/HoganHuang/ros2-learning.git
cd ros2-learning# ROS2 Turtle Controller

## Python Environment (Optional)

This project can optionally use `uv` for Python environment management:

```bash
pip install uv
uv venv
source .venv/bin/activate
