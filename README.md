# Lambda-cdm-model-simulator
# 🌌 ΛCDM Cosmology with Primordial Magnetic Field Evolution

**Author:** Purvasha Mathur  
**Institute:** IIT Jodhpur | BTech AI & Data Science (1st Year)  
**Project Domain:** Theoretical Cosmology, Numerical Physics, Python Simulation

---

## 📖 Overview

This project simulates the expansion of the Universe based on the standard **ΛCDM cosmological model**, and models the evolution of **primordial magnetic fields** as the Universe expands.

We numerically solve the **Friedmann equation** to compute the evolution of:
- The **scale factor** \( a(t) \)
- The **Hubble parameter** \( H(t) \)
- The **energy density components**: matter, radiation, dark energy
- The **cosmic magnetic field strength** \( B(t) \propto a^{-2} \)

---

## 🎯 Objectives

- Numerically solve the Friedmann equation for scale factor evolution.
- Visualize the dynamics of matter, radiation, and dark energy contributions.
- Explore how primordial magnetic fields decay with expansion.
- Relate physical models to data science skills (plotting, numerical computation).

---

## 🧮 Theoretical Background

### 🔹 Friedmann Equation (Flat Universe):

\[
H(t)^2 = H_0^2 \left( \Omega_r a^{-4} + \Omega_m a^{-3} + \Omega_\Lambda \right)
\]

Where:
- \( H(t) \): Hubble parameter at time \( t \)
- \( H_0 \): Present-day Hubble constant
- \( \Omega_r, \Omega_m, \Omega_\Lambda \): Fractional energy densities of radiation, matter, and dark energy
- \( a(t) \): Scale factor (normalized so \( a(t_0) = 1 \))

### 🔹 Primordial Magnetic Field Evolution

From flux conservation in an expanding Universe:

- Magnetic field strength scales as:
  
  \[
  B(t) \propto a(t)^{-2}
  \]

- Magnetic energy density scales as:

  \[
  \rho_B(t) \propto a(t)^{-4}
  \]

This behavior is similar to radiation and helps track early-Universe magnetogenesis.

---

## ❓ Research Questions & Answers

| Question | Answer |
|---------|--------|
| What drives expansion in ΛCDM? | Radiation, Matter, Dark Energy. Dominant at different epochs. |
| How does \( a(t) \) behave? | Grows slowly in early times, faster later (exponentially with dark energy). |
| How does \( B(t) \) evolve? | Decreases as \( a^{-2} \), due to conservation of magnetic flux. |
| Why simulate \( B(t) \)? | To understand cosmic magnetism, CMB effects, and early-universe physics. |

---

## 📊 Features

- ✅ Realistic ΛCDM model with adjustable parameters
- ✅ Solves scale factor numerically over cosmic time
- ✅ Plots the evolution of:
  - Scale factor \( a(t) \)
  - Hubble parameter \( H(t) \)
  - Density contributions: \( \Omega_r, \Omega_m, \Omega_\Lambda \)
  - Magnetic field strength \( B(t) \)
- ✅ All results visualized using `matplotlib`

---

## 🧰 Technologies Used

- **Python**
- `NumPy`
- `Matplotlib`
- `SciPy` (optional for integration)
- Jupyter / Google Colab

---

## 📁 File Structure

