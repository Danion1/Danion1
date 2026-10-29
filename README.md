# Daniel Dos Santos Da Silva

**I take engineering projects from the first idea to a system that works.**

I'm a Computer Science student at Universidade Estácio de Sá, in Brazil, and I want to work as an engineer who owns a project from start to finish: defining what it must do, choosing the mechanism, running the calculations, designing parts that can really be manufactured, selecting components from their datasheets, writing the software and proving in simulation that it all works. Robotics is where I started; the same way of working applies to drones, motors, propulsion and whatever the next problem is.

Hardware costs money, so for now my projects are built and tested in simulation, but every one of them is designed to be built for real.

## How I take a project from start to finish

Each step below is something I did in my [robot arm](https://github.com/Danion1/robot-arm-moveit2):

1. **Requirements and concept**: what the machine must do, and the alternatives compared before choosing (serial arm vs. parallelogram).
2. **Engineering calculations**: loads, torques, stresses, masses and inertias (servos chosen by torque, plate thickness from a stress calculation at stall torque).
3. **Design for fabrication**: parametric CAD in code, with ISO hardware, datasheet hole patterns and printer clearances, ready to print and assemble.
4. **Software and control**: kinematics, motion planning and control (ROS 2, MoveIt 2, ros2_control).
5. **Simulation and verification**: physics simulation checked against hand calculations and the CAD itself; nothing is taken on trust.
6. **Documentation**: every decision with its alternatives and its reason, and honest limitations.

## Where I want to go

- 🦾 **Robots**: manipulators, mobile robots, legged robots, robot learning
- 🚁 **Drones and flight**: flight dynamics and flight control
- ⚙️ **Motors and actuators**: selection, sizing and control
- 🚀 **Propulsion**: from simulated propulsive landing to rocket engines
- 📈 **Control**: from PID to model predictive control and learning-based control

## Portfolio

| Project | What it exercises | Status |
|---|---|---|
| [**4-DOF robot arm with MoveIt 2**](https://github.com/Danion1/robot-arm-moveit2) | concept → calculations → printable CAD → ROS 2 → simulated pick and place | ✅ done in simulation, public |
| Differential-drive mobile robot | motor sizing from a torque calculation, electronics schematic in KiCad (ESP32, motor driver, IMU), ros2_control, Gazebo | done in simulation; being rebuilt before publishing |
| Low-cost arm with leader-follower teleoperation | own CAD, imitation learning (LeRobot) | next |
| Hexapod | legged kinematics and gait | planned |
| SLAM and autonomous navigation | Nav2, SLAM, MPC / MPPI | planned |
| Propulsion vehicle | aerodynamics, flight control (classical vs. MPC vs. learning), propulsive landing | planned |

<a href="https://github.com/Danion1/robot-arm-moveit2"><img src="https://raw.githubusercontent.com/Danion1/robot-arm-moveit2/main/midia/demo.gif" alt="Simulated pick and place: the arm picks a 20 mm cube in Gazebo and places it on the other side" width="480"></a>

## Tools so far

Design: CadQuery (code CAD) · Simulation: Gazebo, ROS 2, MoveIt 2 · Software: Python, Linux, Git and GitHub Actions · Next: C++, perception and building my first machine for real.

## Contact

📫 [danion.neros@gmail.com](mailto:danion.neros@gmail.com): open to engineering and robotics roles, freelance projects and research collaborations.

<details>
<summary>🇧🇷 Em português</summary>

Sou estudante de Ciência da Computação na Universidade Estácio de Sá e quero trabalhar como engenheiro que leva um projeto do começo ao fim: requisitos, mecanismo, cálculos, peças prontas para fabricar, escolha de componentes pelo datasheet, software e simulação que prova que tudo funciona. Comecei pela robótica; o mesmo jeito de trabalhar vale para drones, motores, propulsão e o que vier. Contato: [danion.neros@gmail.com](mailto:danion.neros@gmail.com).

</details>
