---
marp: true
theme: uncover
style: |
    :root {
    --color-background: #FFFFFF;
    --color-foreground: #8B2781;
    --color-highlight: #8B2781;
    --color-dimmed: #888888;
    }
    h1 {
      color: #51247A
    }
    h2 {
      color: #8B2781
    }
    h3 {
      color: #220033
    }
    section {
      font-size: 30px;
    }
paginate: true

---

# METR4202
## Robotics & Automation
### Week 1: Tutorial - Degrees of Freedom & Configuration Space

---

# A review of Grübler's Formula

$$
\begin{aligned}
\mathrm{dof} &= m(N - 1) - \sum_{i = 1}^{J}c_{i} \\
 &= m(N - 1 - J) + \sum_{i = 1}^{J}f_{i}
\end{aligned}
$$


---

# Definitions

**C-Space** (Configuration Space): The space of all configurations

**Degrees of freedom**: Dimension of the C-Space

**Task Space**: The space in which the robot's task is naturally expressed

**Workspace**: A specification of the reachable configurations of the end-effector

---

# Table of Joint Constraints
![width:800px](DOFConstraintTable.png)

---

# Exercise 1: Planar Mechanism
![width:800px](ex_1.png)

---

# Exercise 2: Spatial Mechanism
![width:800px](ex_2.png)

---

# Exercise 3: Upper-Limb Exoskeleton
![width:800px](ex_3.png)

---

# 2D Rotations as Matrices
![width:500px](2DRotationMatrix.png)
$$
R =
\begin{bmatrix}
\cos{(\theta)} & -\sin{(\theta)} \\
\sin{(\theta)} & \cos{(\theta)}
\end{bmatrix}
$$
<!-- ## Rotations in 3D
$$
R_x =
\begin{bmatrix}
\cos{(\theta)} & -\sin{(\theta)} \\
\sin{(\theta)} & \cos{(\theta)}
\end{bmatrix}
$$ -->
---

# The SO3 Group
![width:800px](SO3Group.png)