# EEG Preprocessing with MNE

This repository contains simple Jupyter Notebooks demonstrating **EEG preprocessing** using [MNE-Python](https://mne.tools).  
It is designed as a clean starting point for biomedical signal analysis and BCI research.

---

## 📂 Notebooks

- **`filtering_resampling.ipynb`**  
  Demonstrates how to:
  - Load raw EEG data
  - Apply band-pass filtering (e.g., 1–40 Hz)
  - Remove line noise with notch filter (50/60 Hz)
  - Set average reference
  - Resample the data (e.g., from 250 Hz to 128 Hz)
  - Visualize raw signals and PSD plots  

- **`creating_epoched_data.ipynb`**  
  Demonstrates how to:
  - Detect and extract events from raw EEG
  - Create epochs aligned to stimulus markers
  - Apply baseline correction
  - Visualize averaged responses (ERP/ERF)
  - Prepare data for classification or feature extraction  

---

## ▶️ How to Run

1. Install dependencies:
   ```bash
   pip install mne numpy scipy matplotlib
