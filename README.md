# MOTOR_Learn 电机学习仓库

> 是的，我可以正常工作！ / Yes, I can work normally!

本仓库用于学习和整理电机控制相关知识，包括直流电机、交流电机、步进电机和无刷直流电机，以及 PID、FOC、SVPWM 等控制算法。

This repository is for learning and organizing knowledge related to motor control, including DC motors, AC motors, stepper motors, and BLDC motors, along with control algorithms such as PID, FOC, and SVPWM.

---

## 目录 / Contents

- [电机类型 / Motor Types](#电机类型--motor-types)
- [控制算法 / Control Algorithms](#控制算法--control-algorithms)
- [快速开始 / Getting Started](#快速开始--getting-started)
- [贡献 / Contributing](#贡献--contributing)
- [许可证 / License](#许可证--license)

---

## 电机类型 / Motor Types

| 类型 / Type | 说明 / Description |
|---|---|
| 直流电机 DC Motor | 通过直流电源驱动，转速和转矩易于控制 / Driven by DC power, easy to control speed and torque |
| 交流电机 AC Motor | 包括感应电机和同步电机 / Includes induction motors and synchronous motors |
| 步进电机 Stepper Motor | 以固定步距角旋转，适合精确定位 / Rotates in fixed step angles, suitable for precise positioning |
| 无刷直流电机 BLDC Motor | 效率高、寿命长，广泛用于工业和消费电子 / High efficiency, long lifespan, widely used in industry and consumer electronics |

---

## 控制算法 / Control Algorithms

- **PID 控制** — 比例-积分-微分控制，是最经典的闭环控制算法。  
  Proportional-Integral-Derivative control, the most classic closed-loop control algorithm.

- **FOC（磁场定向控制）** — 通过分别控制磁通量和转矩分量来实现高性能电机控制。  
  Field-Oriented Control: achieves high-performance motor control by independently controlling flux and torque components.

- **SVPWM（空间矢量脉宽调制）** — 一种用于三相逆变器的高效 PWM 调制策略。  
  Space Vector Pulse Width Modulation: an efficient PWM strategy for three-phase inverters.

---

## 快速开始 / Getting Started

```bash
git clone https://github.com/OptimNan/MOTOR_Learn.git
cd MOTOR_Learn
```

---

## 贡献 / Contributing

欢迎提交 Issue 和 Pull Request 来完善本仓库的内容！  
Issues and Pull Requests are welcome to improve the content of this repository!

---

## 许可证 / License

本项目采用 [MIT 许可证](LICENSE)。  
This project is licensed under the [MIT License](LICENSE).

