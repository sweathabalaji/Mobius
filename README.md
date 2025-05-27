# Möbius Strip Modeling and Analysis

This project models a Möbius strip using parametric equations, computes its surface area and edge length numerically, and visualizes it in 3D.

---

## 📐 Parametric Equation

The Möbius strip is defined by the following parametric equations:

x(u,v) = (R + v * cos(u/2)) * cos(u)
y(u,v) = (R + v * cos(u/2)) * sin(u)
z(u,v) = v * sin(u/2)


Where:
- `u ∈ [0, 2π]` (angle around the strip)
- `v ∈ [−w/2, w/2]` (across the strip width)
- `R` is the radius from the center to the middle of the strip
- `w` is the strip width

---

## 🧾 Features

- ✅ Generate a 3D mesh of the Möbius strip using NumPy  
- ✅ Compute surface area using numerical integration (double integral)  
- ✅ Compute total boundary (edge) length  
- ✅ Visualize the 3D strip using Matplotlib  
- ✅ Save plot as image (`mobius_strip_plot.png`)

---

## 🧑‍💻 How to Use

### 🔧 Requirements

- Python 3.x  
- `numpy`  
- `matplotlib`

Install dependencies:

```bash
pip install numpy matplotlib
python mobius_strip.py

---
### Output Example
Surface Area ≈ 2.5131  
Edge Length ≈ 12.6664
📷 The Möbius Strip plot will be saved as an image file.
