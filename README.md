# Fundamentals of Experimental Physics: Data Analysis

This repository contains data analysis scripts and numerical evaluations developed for the "Fundamentals of Experimental Physics" course. The codebase focuses on processing raw experimental data, performing regression, and visualizing physical phenomena.

## 🛠️ Tech Stack
* **Python:** Jupyter Notebooks (`.ipynb`) for data manipulation and visualization.
* **MATLAB:** Scripts (`.m`) for numerical computing and AC/DC signal analysis.

## 📂 Experiments & Code Contents

Below is a guide to the files in this repository and the corresponding physics experiments they analyze:

### 1. Anomalous Hall Effect (AHE)
* `B2濺鍍實驗_異常霍爾效應.ipynb`
* **Description:** Python notebook used to analyze data from sputtered thin films, extracting the anomalous Hall coefficient and visualizing the Hall voltage dependence on the applied magnetic field.

### 2. AC Magnetic Susceptibility
* `B3交流磁化率第三部分.m` / `B3交流磁化率第四部份.ipynb` / `1008 Xray.txt`
* **Description:** A hybrid approach using MATLAB and Python to process alternating current (AC) magnetic susceptibility data. The scripts handle signal extraction and phase analysis to determine the dynamic magnetic response of the samples.

### 3. DC Magnetic Susceptibility
* `B4_DC_method.m` / `B4實驗_直流迴歸方法` (Commit)
* **Description:** MATLAB script implementing regression methods to evaluate direct current (DC) magnetic properties from experimental datasets.

---
*Note: Some inline comments and filenames within the source code are written in Traditional Chinese, as they were originally used for course reports. The core mathematical logic and variable structures remain standard.*
