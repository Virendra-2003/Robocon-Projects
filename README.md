Here’s a **README.md** draft tailored for your GitHub repo based on the design document you uploaded:

---

# 🤖 VIIT Robotics – Robocon 2024

This repository contains the **technical design details, CAD models, and implementation strategies** for the **Robocon 2024 competition** by the **Vishwakarma Institute of Information Technology (VIIT), Pune**.

Our project focuses on building two robots (**R1** and **R2**) that perform tasks such as **seedling picking & planting, paddy rice handling, and transferring to storage zones/silos**, in accordance with the Robocon 2024 problem statement.

---

## 📑 Table of Contents

* [Overview](#overview)
* [Robots](#robots)

  * [R1 – Seedling & Grain Transfer Bot](#r1--seedling--grain-transfer-bot)
  * [R2 – Seedling & Silo Transfer Bot](#r2--seedling--silo-transfer-bot)
* [Key Mechanisms](#key-mechanisms)
* [Mathematical Design](#mathematical-design)
* [CAD & Documentation](#cad--documentation)
* [Tech Stack](#tech-stack)
* [Contributors](#contributors)
* [License](#license)

---

## 📌 Overview

The design document covers the **complete mechanical and mathematical modeling** for the Robocon 2024 robots. Each mechanism is designed with manufacturing feasibility, CAD validation, and physics-based calculations.

---

## 🤖 Robots

### 🔹 R1 – Seedling & Grain Transfer Bot

* Picks seedlings using a **rack & pinion-based gripper**.
* Plants seedlings via a **gantry mechanism with dual grippers**.
* Picks **paddy rice and empty grains** using a **2-DOF servo-actuated gripper**.
* Transfers grains using a **BLDC belt drive + flywheel shooting system** with **PVC funneling**.
* Optimized for **long-range transfer (\~4m)** with calculated flywheel RPM (\~5464 rpm).

### 🔹 R2 – Seedling & Silo Transfer Bot

* Employs a **similar seedling planting mechanism** as R1.
* After planting, directly enters **Area 3** to transfer rice into **silos**.
* Uses a **lead screw mechanism** to elevate rice (545mm lift).
* Compact **retractable gripper** design to stay within **700mm³ frame** constraints.

---

## ⚙️ Key Mechanisms

* **Rack & Pinion Grippers** for seedlings.
* **Helical Gear Grippers** for rice picking.
* **Gantry Plate Actuation** with stepper motors.
* **BLDC Flywheel Shooter** for long-range transfers.
* **Lead Screw Elevation** for precise silo placement.

---

## 📐 Mathematical Design

* **Belt drive calculations** for linear actuation.
* **Projectile motion equations** for flywheel shooting velocity.
* **Helical gear kinematics** for gripper actuation.
* **Lead screw efficiency analysis** with friction considerations.

---

## 📂 CAD & Documentation

* CAD models (SolidWorks/AutoCAD) for all mechanisms.
* Physics-backed calculations for mechanism design.
* Detailed **Technical Design Document** included in this repo.

---

## 🛠️ Tech Stack

* **Mechanical CAD**: SolidWorks, AutoCAD
* **Electronics**: Stepper motors, Servo motors, BLDC motors, Pneumatics
* **Programming**: Arduino / Embedded C (for motor control & actuation)
* **Simulation**: MATLAB (for motion & trajectory validation)

---

## 👨‍💻 Contributors

* **VIIT Robotics Team – Robocon 2024**
* Students & mentors from **Vishwakarma Institute of Information Technology, Pune**

---

## 📜 License

This project is licensed under the **MIT License** – feel free to use, modify, and share with attribution.

---
