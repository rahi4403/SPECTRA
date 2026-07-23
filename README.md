# 🛰️ SPECTRA: Space-Weather Payload Exposures & Calibrated Telemetry Risk Analyzer

**SPECTRA** is an advanced heliophysics diagnostic, machine learning, and orbital risk assessment platform designed to predict Single-Event Upsets (SEUs), sensor degradation, and subsystem criticalities for satellites operating in Low Earth Orbit (LEO) and Geostationary Orbit (GEO).

By integrating real-time space weather telemetry, Random Forest predictive modeling, material radiation shielding calculations, and Keplerian orbital mechanics, SPECTRA provides mission control operators with dynamic risk diagnostics and automated hardware countermeasure triggers.

---

## 🌟 Key Features

* **Machine Learning SEU Risk Engine:** Train-tested **Random Forest Regressor** trained on synthetic heliophysics telemetry (2,500 samples), achieving an **R² score of 0.9828** and **RMSE of 2.0519**.
* **Real-Time Space Weather Ingestion:** Dynamic hazard tracking based on Solar Flare Classifications (C1.0 to X10.0), CME velocities (300 to 2800 km/s), and proton flux density (100 to 10,000 pfu).
* **Hardware Material Radiation Attenuation:** Multi-layer material shielding decay calculations considering:
  * **Aluminum (Standard 6061)**
  * **Tantalum (High-Z Radiation Barrier)**
  * **Polyethylene (Hydrogen-Rich Protection)**
* **3D Sci-Fi Orbital & Atmospheric Render Engine:** Interactive 3D visualization rendering satellite trajectory tracks, atmospheric halos, and high-density spatial zones like the **South Atlantic Anomaly (SAA)**.
* **Subsystem Hardware Risk Matrix:** Granular diagnostic threat assessments for:
  * **Optical CMOS Sensors** (gate-oxide breakdown & soft errors)
  * **Flight Computer Cache (SRAM)** (bit-flips & latch-up sensitivity)
  * **RF Transceiver Avionics** (signal-to-noise degradation)
* **Preset Satellite Mission Profiles:** Quick-load profiles for the **ISS**, **Hubble Space Telescope (HST)**, **Starlink LEO Constellation**, and **GOES-16**.
* **Automated Incident Logging:** One-click generation and export of official `.txt` telemetry incident reports complete with mission metadata and timestamped protocols.

---

## 🛠️ Built With

* **Python 3.12+**
* **scikit-learn** (Random Forest Machine Learning Regressor)
* **Gradio & Plotly** (Interactive Cyber HUD Interface & 3D Visualizations)
* **NumPy & Pandas** (Telemetry Data Analytics & Orbital Math Processing)
* **ipywidgets & IPython** (Jupyter Interactive Notebook Support)

---

## 🚀 Getting Started

### 1. Try it on Google Colab
Run the complete interactive mission control dashboard directly in your browser:
👉 [Open SPECTRA on Google Colab](https://colab.research.google.com/github/rahi4403/SPECTRA/blob/main/SPECTRA.ipynb)

### 2. Run Locally

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/rahi4403/SPECTRA.git](https://github.com/rahi4403/SPECTRA.git)
   cd SPECTRA
