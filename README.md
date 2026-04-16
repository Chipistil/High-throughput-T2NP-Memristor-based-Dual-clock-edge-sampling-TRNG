## README: High-Throughput T2NP Memristor-based TRNG

This repository hosts the source code and experimental datasets for our study on a **High-Throughput T2NP Memristor-based Dual-clock-edge-sampling TRNG**. This project demonstrates the use of a memristor as a high-speed entropy source for a high-throughput true random number generator.

---

## 📂 Repository Structure

### 1. 📊 Data Conversion
Code to transform memristor responses into digital data:
* `delay_time_conversion.txt`: Extraction of switching delay times.
* `relaxation_time_conversion.txt`: Extraction of switching relaxation times.
* `bitstream_conversion.txt`: Logic for final binary bitstream generation.

### 2. 🎲 TRNG Verification
Code to evaluate the quality of the generated sequences:
* **Ciphering**: XOR encryption/decryption tests.
* **Shannon Entropy**: Heatmap and Shannon entropy analysis.
* **Correlation**: Autocorrelation Function (ACF) analysis to ensure unpredictability.

### 3. 🔐 Dual-Image Encryption
Code to verify the TRNG performance in practical security applications:
* **Statistical**: Information entropy, color histograms, 3D pixel distributions and correlation coefficients.
* **Fidelity**: Quality assessment via MSE, PSNR, and SSIM.
* **Robustness**: Resistance against Salt-and-Pepper Noise (SPN) attacks.

### 4. 📋 NIST Test Results
Comprehensive **NIST SP800-22** statistical results across various parameters:
* **Hardware**: Comparison of different peripheral circuits.
* **Amplitude**: Results for input pulses from **2.8V to 3.5V**.
* **Frequency**: Results for clock frequency from **1.5MHz to 2.5MHz**.

---

## 🚀 Quick Start
* **Review Logic**: All source code is provided in `.txt` format for easy viewing.
* **Benchmark**: Use the NIST datasets to compare performance across different voltage and frequency settings.
* **Application**: Implement the encryption script and verify the image encryption effect.

---
*© 2026 | Powered by GitHub Pages*
