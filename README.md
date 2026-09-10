# The Phantom Metric: Parameter-Free Galactic Kinematics & Lensing

This repository contains the Python verification scripts and datasets used to test **The Phantom Metric**—a topologically constrained geometric framework that models galactic anomalies (flat rotation curves and strong gravitational lensing) strictly via baryonic mass and macroscopic metric boundaries, eliminating the need for dark matter parameters.

## 📊 The Data & Results
The algorithms in this repository process raw observational data to predict kinematic and lensing behavior with **zero free parameters** and **zero localized curve-fitting**:

1. **Gravitational Lensing (SLACS Audit):**
   * Processes 100 strong elliptical lenses from the NASA/HST SLACS survey.
   * **Result:** Predicts the exact Einstein Ring Baryonic Boundary ($R_{BB}$) strictly from visible mass with an accuracy of **$R^2 = 0.9917$**.
2. **Galactic Kinematics (SPARC Audit):**
   * Processes 3,391 spatiotemporal data points across 175 Late-Type Galaxies (LTGs).
   * **Result:** Achieves an unfiltered global goodness-of-fit of **$R^2 = 0.9150$** using a strictly locked stellar mass-to-light ratio ($M/L = 0.46$).

## 🚀 How to Run the Code

### Prerequisites
Make sure you have Python 3.8+ installed along with the required data science libraries:
```bash
pip install numpy pandas matplotlib scipy