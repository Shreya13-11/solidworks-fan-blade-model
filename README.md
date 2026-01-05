# SolidWorks — Fan Blade Model

This repository contains a parametric 3D fan blade model designed in SolidWorks.  
The project focuses on understanding the fundamentals of fan blade geometry, constraint-driven design, and feature-based modeling workflows that are commonly used in turbomachinery, cooling systems, and ventilation applications.

This model is intended primarily for learning, experimentation, and documentation of the design process.  
No assembly is included — this repository contains a single part file.

---

## 🎯 Objectives

The primary learning goals of this model were:

- develop a fully-defined base sketch rather than relying on trial-and-error
- construct a smooth hub profile using revolve operations
- generate blade geometry using profiles, guide curves, and reference planes
- maintain surface continuity and curvature quality
- create geometry that can be easily edited and reused
- export the design in formats compatible with multiple CAD tools

By structuring the model parametrically, dimensions can be updated without rebuilding the geometry from scratch.

---

## 📐 Modeling Overview



### 1️⃣ Revolved Base (Hub)

A 2D sketch was created to define the hub profile and then revolved 360°.  
Key considerations included:

- appropriate proportions of length and diameter
- symmetry about the axis
- smooth rounded nose profile
- avoiding under-defined geometry

The hub acts as the foundation for positioning the blade.

---

### 2️⃣ Blade Definition and Shaping

The blade was constructed by sketching profiles on reference planes positioned along the hub.

Important design aspects:

- consistent blade thickness
- gradual twist and curvature
- transitions between sections that avoid sudden edges
- fully-constrained reference geometry

This approach allows the blade shape to evolve in a controlled and predictable way.

---

### 3️⃣ Refinement and Cleanup

Fillets and edge transitions were applied to:

- improve visual realism
- reduce stress concentrations conceptually
- mimic manufacturable geometry

Although this is not an engineering-validated model, it follows good modeling habits.

---

## 📁 Repository Structure

| Path | Description |
|------|-------------|
| `/models/fan_blade.SLDPRT` | Native SolidWorks part file |
| `/models/fan_blade.STEP`  | Neutral CAD export (for sharing and viewing) |
| `/images/preview.png`     | Static preview or rendering (optional) |

If SolidWorks is unavailable, the STEP file can be opened using Fusion 360, FreeCAD, Onshape, or other CAD viewers.

---

## ⚙️ Software Compatibility

This project has been created in SolidWorks 2023.

---

## 🚀 Possible Extensions

This model provides a foundation that can be expanded further:

- attach the blade to a hub or shaft assembly
- create motion animation showing rotational behavior
- run CFD simulations to study airflow qualitatively
- structural analysis to understand loading and deformation
- redesign experiments to compare different blade shapes

These improvements can transform the part into a more engineering-focused project.

---

## 📜 License and Usage

This repository is shared for educational and personal learning purposes.  
The model may be downloaded, modified, and reused with appropriate credit.

Commercial use is not intended.

---

## 🙌 Author

Created by **Shreya** as part of CAD learning and self-practice using SolidWorks.

Feedback and suggestions are welcome.






