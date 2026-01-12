# Multi-Paradigm BCI Decoding: From Riemannian Geometry to EEGNet 🧠💻

### Project Overview
This project implements an end-to-end Brain-Computer Interface (BCI) pipeline to decode Motor Imagery (Left Hand vs. Right Hand) from EEG signals. 
Developed as part of my undergraduate research focus at **Washington University in St. Louis** (EE + PNP Double Major).

**Core Features:**
* **Preprocessing:** Artifact rejection using **Independent Component Analysis (ICA)**.
* **Feature Engineering:** Filter Bank Common Spatial Patterns (**FBCSP**) & Riemannian Geometry.
* **Deep Learning:** Implementation of **EEGNet** (PyTorch) for end-to-end classification.
* **Neuro-Interpretability:** Physiological validation using **ERD/ERS** time-frequency analysis.

---

### 📊 Key Results

#### 1. Performance Benchmark
Comparison of CSP, Riemannian, FBCSP, and EEGNet.
![Benchmark](Advanced BCI Pipeline.png)

#### 2. Neurophysiological Validation (ERD/ERS)
Time-frequency analysis showing distinct **Mu rhythm (8-12Hz) suppression** in the motor cortex, validating the biological basis of the decoding.
![ERD Analysis]([Neural Dynamics (ERD/ERS).png](https://github.com/cheezzyjayy/EEG-Motor-Imagery-Deep-Learning/blob/main/Neural%20Dynamics%20(ERD%3AERS).png))

#### 3. Spatial Patterns (Topomap)
Visualization of spatial filters learned by the model, highlighting activation in the C3/C4 sensorimotor areas.
![Topomap](Spatial CSP Patterns.png)

---

### 🛠️ Tech Stack
* **Language:** Python
* **Neuroscience Libs:** `MNE-Python`, `PyRiemann`
* **Deep Learning:** `PyTorch`
* **Data:** PhysioNet EEG Motor Imagery Dataset

### 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone [https://github.com/YourUsername/WashU-Motor-Imagery-Decoder.git](https://github.com/YourUsername/WashU-Motor-Imagery-Decoder.git)
