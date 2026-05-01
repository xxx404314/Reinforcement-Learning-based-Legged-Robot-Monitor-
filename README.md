● # Reinforcement-Learning-based-Legged-Robot-Monitor
  # 强化学习四足机器人监控系统

  ![Status](https://img.shields.io/badge/status-optimization%20stage-yellow)
  ![Platform](https://img.shields.io/badge/platform-Linux-blue)
  ![Python](https://img.shields.io/badge/python-3.10+-green)

  ---

  ## English

  ### Project Overview

  **Reinforcement-Learning-based-Legged-Robot-Monitor** is a high-performance
  control and deployment platform for 12-DOF quadruped robots, built with
  PySide6/Qt GUI framework and ROS2 communication.

  ### Features

  - Real-time state monitoring (joint position, velocity, torque, IMU)
  - Joint control panel with adjustable PID gains
  - Model configuration and RL policy loading
  - Data visualization with pyqtgraph (50Hz support)
  - Statistical analysis and FFT spectrum analysis
  - Keyboard-based motion control for rl_sim simulator
  - ROS2 topic communication (/joy, /cmd_vel, /imu)
  - Built-in Gazebo + rl_sim simulation launcher

  ### Keyboard Controls (rl_sim)

  | Key | Action |
  |-----|--------|
  | `0` | Stand mode |
  | `1` | RL motion mode |
  | `W/A/S/D` | Directional movement |
  | `R` | Reset |
  | `Space` | Stop |

  ### ⚠️  Project Status

  **This project is still in the optimization stage.** Some features may not be
  fully stable and are subject to change.

  📷 **Note:** The images shown in this project are for testing purposes only
  and do not represent final product quality.

  ---

  ## 中文

  ### 项目简介

  **强化学习四足机器人监控系统**是一款基于 PySide6/Qt GUI 框架和 ROS2
  通信的高性能 12 自由度四足机器人控制与部署平台。

  ### 功能特性

  - 实时状态监控（关节位置、速度、力矩、IMU）
  - 支持可调 PID 参数的关节控制面板
  - 机器人模型配置与强化学习策略加载
  - 基于 pyqtgraph 的数据可视化（支持 50Hz）
  - 统计分析、FFT 频谱分析、CSV 数据导出
  - 键盘控制 rl_sim 仿真器
  - ROS2 主题通信支持 (/joy, /cmd_vel, /imu)
  - 内置 Gazebo + rl_sim 仿真启动器

  ### 键盘控制 (rl_sim)

  | 按键 | 功能 |
  |------|------|
  | `0` | 站立模式 |
  | `1` | RL 运动模式 |
  | `W/A/S/D` | 方向移动 |
  | `R` | 复位 |
  | `空格` | 停止 |

  ### ⚠️  项目状态

  **本项目尚处于优化阶段**，部分功能可能尚未完全稳定，可能会有变更。

  📷 **注意：** 项目中展示的图片均为测试阶段使用，不代表最终产品质量。
