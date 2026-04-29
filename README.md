# 🧠 Multimodal BCI for TB Diagnosis

This repository integrates **EEG neural signals** and **Chest X-ray features** to create a Brain-Computer Interface (BCI) capable of cognitive-load-aware Tuberculosis diagnosis.

## 🚀 Overview
By fusing radiological signals with the radiologist's cognitive state (extracted via EEG), this system aims to improve diagnostic accuracy and identify clinician fatigue during X-ray review.

### Key Features:
- **EEG Processing:** 1D-CNN and CSP+LDA pipelines for feature extraction.
- **Image Integration:** CNN-based feature extraction from TB Chest X-rays.
- **Multimodal Fusion:** Deep learning architecture combining temporal (EEG) and spatial (Image) data.

## 📂 Project Structure
- `BCI_Integration.ipynb`: Multimodal fusion logic and deep learning architecture.
- `EEG_CSP_Pipeline.ipynb`: Detailed signal processing and Leave-One-Subject-Out (LOSO) validation.

## 📊 Results
- **Mean Accuracy:** ~61.82% (Cross-subject decoding)
- **Deep Fusion Gain:** Significant performance boost when combining modalities.

## 🛠️ Installation
```bash
pip install mne scikit-learn tensorflow matplotlib seaborn pandas numpy wfdb
