# 🚗 Single-Cylinder Engine – CAD & FEA Analysis

This repository contains the design and **Finite Element Analysis (FEA)** files for a **Single-Cylinder Engine**. The project includes the **CAD model**, and several types of **structural**, **thermal**, and **vibration analyses** performed using **ANSYS Workbench** to evaluate the engine's performance and durability under various operating conditions.
## 🧩 Components in the Model

The single-cylinder engine design consists of the following main components:
- **Upper Case**
- **Piston**
- **Crankshaft**
- **Cylinder Head**
- **Connecting Rod**
- **Lower Case**

## ⚙️ Tools & Technologies

- **CAD Software**: SolidWorks
- **Simulation Platform**: ANSYS Workbench
- **Analysis Types**:
  - Static Structural Analysis
  - Transient Structural Analysis
  - Modal Analysis
  - Random Vibration Analysis
  - Steady-State Thermal Analysis

## 🔍 Analysis Summary

### 1. **Static Structural Analysis**
- Purpose: To evaluate the stress distribution, deformation, and potential failure points under static loads.
- Observations: The engine block and crankshaft are subject to significant stresses at certain contact points.
- Output: Von Mises stress, displacement, and strain distribution.

### 2. **Transient Structural Analysis**
- Purpose: To study the time-varying loads and dynamic behavior of the engine components under operational conditions.
- Observations: Investigated how the engine parts respond to dynamic loads during operation, focusing on displacement and stress over time.
- Output: Time-based stress and displacement response plots.

### 3. **Modal Analysis**
- Purpose: To identify the natural frequencies and mode shapes of the engine components.
- Observations: First few modes identified, important for avoiding resonance during operation.
- Output: Frequency response plots and mode shapes.

### 4. **Random Vibration Analysis**
- Purpose: To simulate the engine's response to random dynamic loads, such as road irregularities or vibrations during operation.
- Observations: Peak acceleration and displacement response of key components.
- Output: Power spectral density and vibration response plots.

### 5. **Steady-State Thermal Analysis**
- Purpose: To evaluate the temperature distribution and thermal stresses within the engine during normal operation.
- Observations: Engine components show significant thermal gradients, especially near the cylinder head and piston.
- Output: Temperature contours and thermal stress distribution.

## 📊 Results

All analysis results, including stress, deformation, thermal distribution, and vibration response plots, are available in the `/Results` folder. Detailed reports and insights on each analysis are also included.

## 📌 How to Use

1. Clone the repository to your local machine.
2. Open the CAD model in SolidWorks (2021 or later).
3. Open the ANSYS Workbench project files.
4. Navigate to the respective analysis systems (Static Structural, Transient Structural, Modal, Random Vibration, Steady-State Thermal).
5. Re-run simulations or modify the geometry as required.
