# 🛰️ SPECTRA: Solar Payload Exposure & Calibrated Telemetry Risk Engine

**SPECTRA** is an advanced heliophysics diagnostic and orbital risk assessment platform designed to predict Single-Event Upsets (SEUs), sensor degradation, and system criticalities for satellites operating in Low Earth Orbit (LEO) and Geostationary Orbit (GEO). 

By integrating real-time space weather parameters with Keplerian orbital propagation, SPECTRA provides mission control operators with dynamic risk modeling and automated hardware countermeasure triggers.

---

## 🌟 Key Features

* **Real-Time Space Weather Ingestion:** Dynamic risk scoring based on Solar Flare Classification ($C$, $M$, $X$-class), Coronal Mass Ejection (CME) velocity, and proton flux density ($>10\text{ MeV}$).
* **3D Orbital Trajectory & Anomaly Mapping:** Interactive 3D visualization rendering satellite tracks across orbital space, highlighting high-density radiation zones such as the **South Atlantic Anomaly (SAA)**.
* **Subsystem Hardware Risk Breakdown:** Granular diagnostic threat matrices for:
  * **Optical CMOS Sensors** (gate-oxide breakdown risk)
  * **SRAM Flight Computers** (soft bit-flips & latch-ups)
  * **RF Transceivers** (signal-to-noise degradation)
* **Automated Defensive Protocols:** Triggered hardware countermeasures (CMOS safe-mode locking, high-frequency SRAM memory scrubbing, and solar array vector re-orientation) when risk exceeds critical thresholds ($>70\%$).
* **Preset Satellite Mission Profiles:** Out-of-the-box configurations for the **International Space Station (ISS)**, **Hubble Space Telescope (HST)**, **Starlink LEO Constellation**, and **GOES-16**.
* **Automated Incident Logging:** One-click generation and export of official `.txt` telemetry incident reports.

---

## 🛠️ Built With

* **Python 3.10+**
* **Gradio / Plotly** (Interactive UI & 3D Web Graphics)
* **NumPy / Pandas** (Data Processing & Mathematical Modeling)
* **Astrodynamics & Heliophysics Frameworks**

---

## 🚀 Getting Started

### 1. Try it on Google Colab
You can run the full interactive notebook directly in your browser:
👉 [Open SPECTRA on Google Colab](https://colab.research.google.com/github/rahi4403/SPECTRA/blob/main/spectra.ipynb)

### 2. Run Locally

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/rahi4403/SPECTRA.git](https://github.com/rahi4403/SPECTRA.git)
   cd SPECTRA
