# UAV NOSE LANDING GEAR ASSEMBLY ✈️🛠️

## 1. Overview

The **UAV Nose Landing Gear Assembly** project focuses on designing a functional nose gear mechanism for an unmanned aerial vehicle, using only CAD‑based modelling and checks.
The work covers **part and assembly design, geometric compatibility, and installation space planning** for realistic integration into a UAV fuselage.
---

## 2. Aim 🎯

- Design a **nose landing gear assembly** that fits within a defined UAV nose volume and interfaces with the fuselage structure
- Model all key components in CAD from reference dimensions, ensuring **proper clearances and realistic joint behaviour**
- Prepare a clean **assembly and drawing package** suitable for manufacturing and documentation.

---

## 3. Tech Stack & Tools 🧰

### Software

- 3D CAD: **CATIA V5 (Part Design, Assembly Design, DMU Kinematics)**

### Core Skills

- 3D part modelling from 2D references and real component measurements. 
- Assembly constraints, motion definition, and clash detection within CATIA V5.
- 2D drawing creation with dimensions, GDT symbols, and BOM generation.

---

## 4. Architecture & Components 🧩

Typical components modelled in the nose gear assembly:

- **Main strut**  
  - Primary structural member connecting wheel to fuselage attachment points.
  - Designed with realistic profiles and mounting features for brackets and steering links.

- **Fork / wheel carrier**  
  - Holds the nose wheel and interfaces with the strut via a pivot or fixed joint.
  - Includes axle seats and clearance for tyre width.

- **Retracting mechanism interface**  
  - Mounting features for a future retraction actuator or linkage (modeled as reference interfaces in CAD).
  - Ensures there is sufficient volume for rotation into the fuselage bay.

- **Mounting brackets & fuselage lugs**  
  - Attachment lugs designed to connect the gear to the UAV nose structure. 
  - Hole patterns and fillets added with manufacturability and load paths in mind.

- **Wheel & axle**  
  - Simplified wheel geometry modelled to correct diameter and width, with an axle passing through the fork.

---

## 5. Modelling Workflow 🧱

1. **Define envelope & constraints**  
   - Set up a reference **installation space** representing the UAV nose volume. 
   - Fix key dimensions: wheel size, required ground clearance, and retracted position limits.

2. **Part modelling**  
   - Create CAD parts for strut, fork, wheel, brackets, and hardware using CATIA V5 Part Design.  
   - Use parametric dimensions for quick updates to lengths, offsets, and thicknesses.

3. **Assembly & motion check**  
   - Assemble all components with appropriate mates (revolute, fixed, sliding as needed) in Assembly Design. 
   - Use **DMU Kinematics** to define retraction motion and verify that the gear rotates or translates without clashes with the fuselage.

4. **Clearance & interference control**  
   - Run clash detection to ensure no interference between gear parts, wheel, and surrounding structure. 
   - Adjust bracket positions and link lengths in CAD to maintain safe clearances in extended and retracted positions.

5. **Detailing & documentation**  
   - Create **2D drawings** for all main parts with dimensions and GDT.[file:344]  
   - Generate an assembly drawing with section views, ballooned BOM, and basic installation information.

---

## 6. Key Features & CAD Highlights 🌟

- **Realistic integration**  
  - Geometry and interfaces designed to mirror real-world nose gear layouts, including structural lugs and actuator space.

- **Motion‑validated assembly**  
  - Retraction and extension motion checked directly in CATIA V5 using kinematic constraints and clash detection.

- **Manufacturing‑aware parts**  
  - Parts designed for machining and fabrication, with appropriate fillets, chamfers, and drilling features.

- **Documentation‑ready**  
  - Complete set of CAD files, 2D drawings, and BOM makes this project suitable for **portfolio presentation and manufacturing hand‑off**.

---

## 7. Possible Extensions 🚀

- Add a detailed **retraction actuator model** (e.g., electric or mechanical linkage) with its mounting brackets.
- Refine the fuselage cut‑outs and doors around the gear bay for a more aircraft‑like integration. 
- Produce simple **renders** of extended and retracted positions for portfolio slides and reports.
---

## 8. Author 👨‍💻

**Atharv Nitin Agashe**  
Mechanical Design Engineer · M.Sc. Mechatronics & Robotics  
- Email: `atharvagashe962001@gmail.com`
- LinkedIn: [www.linkedin.com/in/atharv-agashe9601](https://www.linkedin.com/in/atharv-agashe9601)
