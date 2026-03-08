# ⚙️ Mechanical Design & Robotics Portfolio (Onshape)

This repository contains a collection of **mechanical CAD projects designed and assembled using Onshape**.

The projects focus on:

- CAD modeling
- Mechanical assemblies
- Gear mechanisms
- Robotics structures
- Motion simulation
- Robot kinematics

---

# 🧱 Basic CAD Practice

## Training Shape (Practice Design)

This shape was created as a training exercise to learn the basics of using Onshape.  
The purpose of this model is to practice **Extrude (Add)** and understand how to build simple 3D forms.

This design is for learning purposes only and is not intended as a final or functional model.

### Tools Used
- Extrude (Add)

### Measurement Tools Used
The dimensions of the shape were measured using a ruler to obtain approximate values for the length, width, and height, and these measurements were then entered into Onshape during the design process.

### Design Preview

<img width="495" height="566" src="https://github.com/user-attachments/assets/773dd6ba-e2d6-4e2d-845e-adb77788dae0" />

---

## Training Shape – Pen Holder Base

This model was created as a training exercise to learn the basics of 3D design using Onshape.

The purpose of this design was to practice using **Revolve** and **Extrude** to create a simple circular shape with a center hole.

This model is for learning purposes only and is not intended as a final or functional design.

### Usage
This design can be used as a simple desk pen holder to organize pens and small tools.

### Tools Used
- Revolve
- Extrude (Add)
- Extrude (Remove)

### Measurement Tools Used
The dimensions were measured using a ruler and then defined precisely in Onshape using the **Dimension tool**.

### Design Preview

<img width="827" height="458" src="https://github.com/user-attachments/assets/76405165-3f2a-4053-94db-2c854c30df7e" />

---

# 🧩 3D Printable Components

## Remote Control Mount

### Description
3D printable remote control mounting bracket designed using Onshape.

### Usage
This mounting bracket can be used to securely hold a remote control in a fixed position, helping to organize the workspace and keep the remote easily accessible.

### Tools Used
- Extrude (Add)
- Extrude (Remove)
- Fillet

### Measurement Tools Used
The dimensions were measured using a ruler and then defined in Onshape using the **Dimension tool**.

### Design Preview

<img width="466" height="551" src="https://github.com/user-attachments/assets/687a4252-3075-46d4-98b1-756ce19db594" />

![remote-control-mount](https://github.com/user-attachments/assets/f6e734f8-8ecc-4964-9ffc-8fda266c30b2)

---

## Servo Motor Mount (MG995)

### Description
3D printable servo motor mount designed using Onshape.

### Usage
This mount securely holds an **MG995 servo motor** for robotics projects, prototypes, and educational applications.

### Tools Used
- Extrude (Add)
- Extrude (Remove)
- Fillet

### Measurement Tools Used
Dimensions were measured manually and defined precisely in Onshape using the **Dimension tool**.

### Design Preview

<img width="632" height="395" src="https://github.com/user-attachments/assets/62b941f4-c5bf-4438-bea7-61f4ee3de026" />

---

# 🤖 Robotics Structures

## Two-Wheeled Robot Base

### Description
A lightweight two-wheeled robot base designed for educational robotics projects.

### Usage
This base acts as the main chassis for a two-wheel mobile robot and supports mounting:

- DC motors
- Wheels
- Battery
- Microcontroller

The robot uses **differential drive** for movement and turning.

### Material
PLA was selected due to its lightweight properties, ease of printing, and adequate strength.

### Design Preview

<img width="1874" height="949" src="https://github.com/user-attachments/assets/201b6af6-6c18-4640-9ee8-4071136e36dd" />

---

## Two-Wheel Robot Base (TT Motor)

A simple **2-wheel robot chassis** designed for **TT motors**.

### Features
- Supports TT DC motors
- Compatible with common robot wheels
- Lightweight and compact design
- Optimized for FDM 3D printing
- Suitable for Arduino / Raspberry Pi robotics projects

### Components
- 2 × TT Motors
- 2 × Robot Wheels
- 1 × Base Plate
- Motor Brackets

### Use Cases
- Line follower robot
- Obstacle avoidance robot
- DIY robotics projects
- Educational robotics kits

### Design Preview

<img width="650" height="428" src="https://github.com/user-attachments/assets/eb5e8407-6808-4a22-b92e-067cf2707831" />

---

# 🤖 Robot Arm Assembly (Onshape)

This project demonstrates the assembly of a robotic arm using **public CAD components in Onshape**.

### Concepts Practiced

- Mechanical assembly
- Joint configuration
- Revolute mate setup
- Robot kinematics simulation

### Robot Arm Preview

<img width="685" height="947" src="https://github.com/user-attachments/assets/238e8433-b595-4b30-9fed-52ccdbbf37ba" />

---

### Assembly Structure

1. Base del brazo y circuito  
2. Tapa circuito  
3. Eje Central  
4. Tapa Eje  
5. Engranaje1  
6. Engranaje2  
7. Barra1  
8. Barra2  
9. Brazo  
10. Antebrazo  
11. Base de la Garra  
12. Garra1  
13. Garra2

---

### Joint System

| Joint Area | Mate Type | Description |
|-------------|-------------|-------------|
| Base Structure | Fastened | Base covers fixed to the structure |
| Base Rotation | Revolute | Rotates entire robot arm |
| Shoulder Joint | Revolute | Connects base to first arm segment |
| Elbow Joint | Revolute | Enables arm bending |
| Intermediate Link | Cylindrical + Revolute | Rotation and sliding |
| Wrist Joint | Revolute | End-effector orientation |
| Gripper Mechanism | Gear Mate | Synchronizes gripper motion |

---

### Assembly View

<img width="865" height="1066" src="https://github.com/user-attachments/assets/f4b08773-cf58-4e96-b4ea-966cfa817f9d" />

---

### Robot Motion Demo

https://youtu.be/WXS4-cyEAZk?si=KpW7XBwalOi5TZQG

---

# ⚙️ Mechanical Mechanisms

## Shock Absorber – CAD Assembly

A fully modeled **shock absorber mechanism** assembled in Onshape.

### Assembly Mates

- Cylindrical Mate
- Slider Mate
- Screw Mate
- Fastened + Planar Mates

### Preview

<img width="419" height="970" src="https://github.com/user-attachments/assets/a61d219d-336a-4569-8ed0-cc17c0ec420c" />

https://github.com/user-attachments/assets/a11396f2-417d-4796-9009-76fdaf3534ad

---

# 📐 Robot Kinematics Analysis

## 3-DOF Robot Arm Forward Kinematics

Mathematical modeling and numerical analysis of a **3-DOF robotic arm**.

### Final End Effector Position

x ≈ 10.29 cm  
y ≈ 22.61 cm  
z ≈ 23.71 cm  

orientation φ = 40°

---

# ⚙️ Gear Systems

## Gear Transmission (1:18)

Multi-stage spur gear transmission designed to achieve **1:18 reduction ratio**.

| Gear | Teeth |
|-----|------|
| Gear 1 | 5 |
| Gear 2 | 10 |
| Gear 3 | 15 |
| Gear 4 | 90 |

### Gear System Preview

<img width="509" height="475" src="https://github.com/user-attachments/assets/d063f334-6512-446f-827b-d61efdc92e5d" />

https://github.com/user-attachments/assets/66878a9a-1ef6-4304-90d6-37ea9879dfc6

---

## Planetary Gear System

Planetary gear system demonstrating an **epicyclic gear train**.

### Components

1. Ring Gear  
2. Sun Gear  
3. Planet Gears  
4. Planet Carrier

### Preview

<img width="515" height="478" src="https://github.com/user-attachments/assets/c32f9d1e-5cb1-4889-af11-d114e0cf6ae6" />

---

### Assembly View

<img width="523" height="484" src="https://github.com/user-attachments/assets/5175bb4e-7621-46dc-8bfd-3e58b8e864ef" />

https://github.com/user-attachments/assets/2434c473-9d23-4ac5-aab9-bbf45c7bf304

---

# 🧠 Skills Demonstrated

- CAD Modeling (Onshape)
- Mechanical Assembly
- Robot Mechanisms
- Gear System Design
- Motion Constraints
- Robotics Kinematics
- 3D Printable Mechanical Design
