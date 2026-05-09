# UAV NOSE LANDING GEAR ASSEMBLY ✈️

## 1. Overview

The **UAV Nose Landing Gear Assembly** project focuses on designing a realistic, fully constrained landing gear system for an unmanned aerial vehicle in **CATIA V5**.  
The goal is to go beyond aesthetic modelling and build a kinematically correct, clash‑free assembly that can be analysed for motion, clearance, and manufacturability. 🛠️

---

## 2. Aim 🎯

- Design a **complete UAV nose landing gear assembly** in CATIA V5, reverse‑referencing a real landing gear as the baseline.  
- Validate **geometric compatibility, clearances, and retraction motion** using DMU Kinematics.  
- Apply **GD&T and tolerance thinking** to ensure that the design is realistic for manufacturing and assembly, not just for visualization.

---

## 3. Tech Stack & Tools 🧰

### Software & Modules

- **CATIA V5 (V5‑6R2018)**  
  - Part Design  
  - Assembly Design  
  - **DMU Kinematics** (for motion simulation and clash checks)

### Core Skills Used

- 3D part and assembly modelling from **2D reference drawings** and real‑component photos.  
- GD&T application for **fits, alignments, and clearances**.  
- DMU Kinematics setup, including joints, motion drivers, and limits.  
- Digital Mock‑Up (DMU) for **clash detection and motion envelope validation**.  

---

## 4. Components & Sub‑Assemblies 🧩

Typical elements modelled in this project include:

- **Strut assembly** – main shock‑absorbing member.  
- **Fork / wheel carrier** – interfaces with the nose wheel and axle.  
- **Nose wheel** – tyre + rim unit (simplified for CAD, dimensionally realistic).  
- **Mounting lugs / brackets** – interfaces between the gear and UAV fuselage structure.  
- **Actuation linkage** – simplified representation of retraction/extension mechanism (links, pivots).  
- **Fasteners & pins** – modelled as simplified hardware, enough for interference and clearance analysis.

Each component is parametrically defined where possible so dimensions can be tuned for different UAV sizes without rebuilding the model from scratch. 🔧

---

## 5. Modelling Workflow 🧱

1. **Reference collection**  
   - Study real nose landing gear images, reference drawings, and key dimensions for proportions and constraints.  

2. **Part modelling in CATIA V5**  
   - Create individual parts (strut, fork, wheel, brackets, pins) using Part Design.  
   - Apply basic GD&T where relevant: concentricity, perpendicularity, hole positions, etc.  

3. **Assembly construction**  
   - Assemble components with appropriate constraints (coincidence, offset, angle, axis alignment).  
   - Define realistic pivot points for steering and retraction motion.  

4. **DMU Kinematics setup**  
   - Convert assembly constraints to kinematic joints.  
   - Add motion drivers (e.g., rotation for retraction, steering angle).  
   - Limit motion ranges according to realistic mechanical stops.  

5. **Validation**  
   - Run **retraction and extension simulations**.  
   - Use **clash detection** to confirm no interference between gear, wheel, and fuselage mounting region during the whole motion. ✅  

---

## 6. Key Features & Engineering Highlights 🌟

- **Reverse‑engineered geometry**  
  - The landing gear is **reverse-referenced from a real UAV design**, which keeps proportions and interfaces realistic for an aerospace context.  

- **DMU Kinematics motion simulation**  
  - Full retraction motion simulated inside CATIA V5, verifying that the gear can fold and deploy without collisions.  
  - Kinematic joints and motions replicate real‑world hinge and actuator behaviour as closely as possible at this level.  

- **GD&T and tolerance awareness**  
  - Used GD&T principles to define how parts should align and fit in a real assembly:  
    - Coaxiality of strut and wheel fork  
    - Hole positions for brackets & pins  
    - Clearance around wheel for tyre deflection and steering angle  

- **Clash‑free digital mock‑up**  
  - DMU clash detection used to ensure **zero interference** between components during motion, avoiding late‑stage surprises in a physical prototype.  

- **Presentation‑ready**  
  - The project is structured and documented so that it can be presented in **academic reviews, portfolio presentations, and interviews** as a clear example of aerospace‑adjacent mechanical design. 🎓

---

## 7. Possible Extensions 🚀

- Add **shock absorber internals** (spring, damper) and perform a basic kinematic or static load analysis.  
- Integrate with a **UAV fuselage model** to study installation space, access for maintenance, and structural load paths.  
- Export key components to FEA software to study **stress in brackets, axles, and strut** under landing loads.  

---

## 8. Author 👨‍💻

**Atharv Nitin Agashe**  
Mechanical Design Engineer · M.Sc. Mechatronics & Robotics  
- Email: `atharvagashe962001@gmail.com`  
- LinkedIn: [www.linkedin.com/in/atharv-agashe9601](https://www.linkedin.com/in/atharv-agashe9601)
