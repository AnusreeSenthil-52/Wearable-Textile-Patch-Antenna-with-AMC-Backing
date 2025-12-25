# Wearable-Textile-Patch-Antenna-with-AMC-Backing

A compact and flexible **wearable microstrip patch antenna** designed for **body-centric wireless communication** applications. The antenna operates at **1.95 GHz** and uses a **textile substrate** with **Artificial Magnetic Conductor (AMC) backing** to improve gain, reduce back radiation, and minimize human body effects. The design is simulated, optimized, and experimentally validated.

## 🛠️ Tools & Software Used

* **CST Studio Suite** – Antenna modeling and EM simulation
* **Vector Network Analyzer (VNA)** – Experimental validation
* **Copper tape / conductive fabric** – Radiating patch
* **Foam + AMC layer** – Backing structure

## 🧠 Working Principle

* A **textile microstrip patch antenna** is designed using standard antenna equations.
* The antenna is fed using a **50 Ω microstrip inset feed** for impedance matching.
* **AMC backing** reflects electromagnetic waves in-phase, reducing back radiation toward the human body.
* Performance metrics analyzed:
  * Return Loss (S11 < −10 dB)
  * VSWR (< 2)
  * Gain & radiation patterns (2D & 3D)
* Fabricated antenna results closely match simulation outputs.

## 📊 Performance Summary

* **Resonant Frequency:** 1.95 GHz
* **VSWR:** < 2 at operating band
* **Peak Gain:** ~7.6 dBi (with AMC)
* **Improved performance** compared to antenna without AMC backing

## 📁 Files Included

* `Wearable_Antenna.cst` – CST Simulation file
* `Results.ppt` – Fabricated Antenna and CST Simulation results

## 💡 Applications

* Biomedical & healthcare monitoring (WBAN)
* Smart wearable devices
* Military & defense communication
* Sports and fitness tracking
* Neural and brain signal monitoring

## 🚀 Future Improvements

* SAR analysis with human body phantom
* Multiband or dual-band wearable antenna
* Fully embroidered or washable textile antenna
* Integration with IoT-based wearable sensors
