# 🌊 QuantumHDC for Flood Mapping (NASA BEYOND Challenge 2025) - Team tML-ECT - FINALIST

🚀 Welcome to our solution for the **NASA BEYOND Challenge: Novel Computing Architectures for Flood Analysis**, where we tackle flood rapid mapping using **Hyperdimensional Computing (HDC)** and **Quantum Simulation**.

This project was submitted as part of the [2024 IEEE GRSS Data Fusion Contest](https://ieee-dataport.org/competitions/2024-ieee-grss-data-fusion-contest-flood-rapid-mapping) in partnership with NASA’s [BEYOND Challenge](https://www.nasa-beyond-challenge.org/).

---

## 🔍 Challenge Overview

> **Goal**: Develop flood mapping models using unconventional hardware/software platforms.

We explore **Quantum HDC (Hyperdimensional Computing)** using the **IBM Qiskit AerSimulator**, with a focus on SAR and optical satellite data fusion.

---

## 📦 Dataset

- 📥 Download from: [IEEE DataPort Flood Mapping Dataset](https://ieee-dataport.org/competitions/2024-ieee-grss-data-fusion-contest-flood-rapid-mapping)
- 🛰️ Tracks:
  - **Track 1**: SAR images (6 bands)
  - **Track 2**: Optical images (12 bands)

---

## 🧠 Methodology: Quantum HDC

We propose a **Dual-Input Quantum HDC Model** using:
- Feature transformation via Sobol-based or random HD vectors
- Quantum simulation with IBM Qiskit AerSimulator
- Joint prediction from both SAR and optical modalities

### ⚙️ Processing Flow

1. **Preprocessing**:
   - Reshape (C, H, W) → (H×W, C)
2. **Quantum Projection**:
   - Map feature vectors into quantum HD space
3. **Encoding & Superposition**:
   - Class-based HD vectors accumulated via binding
4. **Similarity Matching**:
   - Associative memory retrieves most similar class vector

## 🧩 Proposed Method: Dual-Input QuantumHDC

The proposed architecture jointly processes SAR and optical data streams using quantum projection and hyperdimensional encoding. Each input is reshaped, projected, and fused to produce final predictions via an output layer.

```text
Track 1 (SAR) Data ───► Reshape ───► Quantum Projection ─┐
                                                         │
                                                         ▼
                                                  ┌─────────────┐
                                                  │             │
Track 2 (Optical) Data ─► Reshape ─► Quantum Projection ─┘
                                                  │
                                                  ▼
                                          Averaging & Fusion
                                                  │
                                                  ▼
                                             Output Layer
                                                  │
                                                  ▼
                                           Joint Prediction
```


## 🧪 Results

## 📊 Results — Track 2: Optical Data

> Quantum Simulator: IBM Qiskit AerSimulator

| **Method**                    | **Run Time (s)** | **Accuracy (%)** | **F1-Score (%)** | **Precision (%)** | **Recall (%)** | **Iteration** |
|------------------------------|------------------|------------------|------------------|-------------------|----------------|---------------|
| LR                           | 8.537            | 82.8             | 80.5             | 83.0              | 82.8           | 1000          |
| MLP                          | 1185.913         | 91.8             | 91.5             | 91.7              | 91.8           | 500           |
| SVM                          | 194.009          | 41.2             | 44.4             | 55.6              | 41.2           | 1000          |
| RF                           | 1308.201         | 95.6             | 95.5             | 95.6              | 95.6           | –             |
| HDC-Sobol (D=1024)           | **0.039**        | **96.2**         | **96.2**         | **96.2**          | **96.2**       | 3             |
| Quantum-HDC_8qubit (D=1024)  | **0.049**        | **96.5**         | **96.4**         | **96.4**          | **96.5**       | 3             |


---

## 📁 Repository Contents

| File                                | Description                                  |
|-------------------------------------|----------------------------------------------|
| `Track1.ipynb`                      | HDC modeling using Track 1 SAR data          |
| `Track 2.ipynb`                     | HDC modeling using Track 2 optical data      |
| `Multimodal_DualInputQuantumHDC.ipynb` | Joint SAR + Optical fusion model         |

---

## 🧑‍💻 Contributors

| Name | 🎓 Affiliation | 🔗 Google Scholar |
|------|----------------|-------------------|
| Abu Kaisar Mohammad Masum| University of Louisiana at Lafayette | [🔗](https://scholar.google.com/citations?user=B194MGYAAAAJ&hl=en) |
| Mehran Shoushtari Moghadam | Case Western Reserve University | [🔗](https://scholar.google.com/citations?user=1TsiuPcAAAAJ&hl=en) |
| Sercan Aygun | University of Louisiana at Lafayette | [🔗](https://scholar.google.com/citations?user=9CMxwUQAAAAJ&hl=en) |
| M. Hassan Najafi| Case Western Reserve University | [🔗](https://scholar.google.com/citations?user=vIc-83QAAAAJ&hl=en) |


---

## 🚀 Getting Started

### 1. Run Notebooks

Open each track's notebook or the dual-input fusion notebook:

```bash
jupyter notebook Track1.ipynb
jupyter notebook Track2.ipynb
jupyter notebook Multimodal_DualInputQuantumHDC.ipynb
```

---

## 🔑 Key Technologies

- [Qiskit AerSimulator](https://qiskit.org/)
- [Hyperdimensional Computing (HDC)](https://arxiv.org/abs/2311.10778)
- Sobol sequence-based projection
- QuantumHDC learning
- SAR and optical data fusion

---

## 📜 Citation

If you use this work, please cite:

```
TBA
```
## Create date: 07/14/2025, Update: 09/12/2025 (Finalist Info. Added)
