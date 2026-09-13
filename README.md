# 2D Truss Finite Element Analysis (FEM)

A Python-based solver for 2D truss structures using the Finite Element Method. This project computes nodal displacements, reaction forces, and provides visualization of the deformed shape with color-mapped displacement fields.

## 🎯 Problem Overview
- **Structure:** 3-node triangular truss
- **Material:** E = 1.0 × 10⁶ Pa, A = 0.01 m²
- **Boundary Conditions:** Node 1 fixed, Node 2 roller
- **Load:** -20 N downward at Node 3

## 🛠️ Skills & Tools Used
- **Languages:** Python
- **Libraries:** NumPy, Matplotlib
- **Concepts:** Finite Element Method, Structural Analysis, Linear Algebra, Modular Programming

## 📊 Key Results
| Node | X-Displacement (m) | Y-Displacement (m) |
|------|---------------------|---------------------|
| 2 | +5.0 × 10⁻⁴ | 0 |
| 3 | +2.5 × 10⁻⁴ | -8.66 × 10⁻⁴ |

*Equilibrium verified: Sum of vertical reactions = 20 N upward.*
