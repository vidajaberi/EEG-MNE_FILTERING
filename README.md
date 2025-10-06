# EEG-Preprocessing_MNE
# EEG Filtering & Resampling with MNE

This repository shows how to preprocess EEG data using **MNE-Python**.  
The notebook demonstrates basic steps such as band-pass filtering, notch filtering, re-referencing, and resampling.

---

## 📂 Files
- `filtering_resampling.ipynb` → Jupyter Notebook with the preprocessing code
- `README.md` → Project description (this file)

---

## ⚡ Steps in the Notebook
1. Load raw EEG data (supported formats: FIF, EDF, BDF, …)  
2. Apply band-pass filter (e.g., 1–40 Hz)  
3. Remove line noise with notch filter (50/60 Hz)  
4. Set average reference  
5. Resample the data (e.g., from 250 Hz to 128 Hz)  
6. Visualize raw signals and PSD plots  

---

## ▶️ How to Run
1. Install dependencies:
   ```bash
   pip install mne numpy scipy matplotlib
