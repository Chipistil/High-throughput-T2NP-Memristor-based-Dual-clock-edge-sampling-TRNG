## README: High-throughput T2NP Memristor-based TRNG

This repository hosts the source code and experimental datasets for our study on a **High-throughput T2NP Memristor-based Dual-clock-edge-sampling TRNG**. This project demonstrates the use of a memristor as a high-speed entropy source for secure true random number generation.

---

## 📂 Repository Structure

### 1. 📊 Data Conversion
Algorithms to transform physical memristor responses into digital data:
* `delay_time_conversion.txt`: Extraction of switching delays.
* `relaxation_time_conversion.txt`: Processing of filament relaxation times.
* `bitstream_conversion.txt`: Logic for final binary bitstream generation.

### 2. 🎲 TRNG Verification
Tools to evaluate the quality of generated sequences:
* **Security**: XOR encryption/decryption tests.
* **Entropy**: Shannon entropy and heatmap analysis.
* **Correlation**: Autocorrelation Function (ACF) analysis to ensure unpredictability.

### 3. 🔐 Image Encryption
Validation of TRNG performance in practical security applications:
* **Statistical**: Information entropy, histograms, and 3D pixel distribution.
* **Fidelity**: Quality assessment via MSE, PSNR, and SSIM.
* **Robustness**: Resistance against Salt-and-Pepper Noise (SPN) attacks.

### 4. 📋 NIST Test Results
Comprehensive **NIST SP800-22** statistical results across various parameters:
* **Hardware**: Comparison of different sampling circuits.
* **Amplitude**: Results for input pulses from **2.8V to 3.5V**.
* **Frequency**: Results for clock speeds from **1.5MHz to 2.5MHz**.

---

## 🚀 Quick Start
* **Review Logic**: All source code is provided in `.txt` format for easy viewing.
* **Benchmark**: Use the NIST datasets to compare performance across different voltage and frequency settings.
* **Application**: Implement the encryption scripts to verify the randomness in visual data protection.

---
*© 2026 | Powered by GitHub Pages*
