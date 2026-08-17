# The Phantom Metric: Parameter-Free Galactic Kinematics & Lensing

This repository contains the Python verification scripts and datasets used to test **The Phantom Metric**—a discrete geometric framework that models galactic anomalies (flat rotation curves and strong gravitational lensing) strictly via baryonic mass and spatial topology, eliminating the need for Dark Matter parameters.

## 📊 The Data & Results
The algorithms in this repository process raw observational data to predict kinematic and lensing behavior with **zero free parameters** and **zero localized curve-fitting**:

1. **Gravitational Lensing (SLACS Audit):**
   * Processes 100 strong elliptical lenses from the NASA/HST SLACS survey.
   * **Result:** Predicts the Einstein Ring Bounding Box ($R_{BB}$) strictly from visible mass with an accuracy of **R² = 0.9917**.
2. **Galactic Kinematics (SPARC Audit):**
   * Processes 3,391 spatiotemporal data points across 175 Late-Type Galaxies (LTGs).
   * **Result:** Achieves an unfiltered global goodness-of-fit of **R² = 0.9150** using a strictly locked stellar mass-to-light ratio ($M/L = 0.46$).

## 🚀 How to Run the Code

### Prerequisites
Make sure you have Python 3.8+ installed along with the required data science libraries:
```bash
pip install numpy pandas matplotlib scipy

Execution
Run the specific audit scripts directly from your terminal.

For the Lensing Audit (SLACS):
python SLACS_Phantom_Metric_Lensing.py
Outputs the statistical R² validation and generates figure3_lensing_audit.png.

For the Kinematics Audit (SPARC Global):
python SPARC_Global_Audit.py
Outputs the consolidated R² variance for all 175 galaxies and generates figure2_global_audit_ml046.png.

For the Single Galaxy Benchmark (NGC 2403):
python NGC2403_Benchmark.py
Outputs the single rotation curve fit and generates figure1_ngc2403_locked.png.

📄 Documentation
The full theoretical framework, mathematical derivations (including the formulation of the Topological Latency function and the Information-Theoretic Bounding Box), and the pre-print paper can be found at:

Zenodo Repository: https://doi.org/10.5281/zenodo.21920452

🤝 Open Science
True science is transparent. You are encouraged to download the datasets, run the Python scripts, manipulate the code, and verify the predictive power of this metric yourself.