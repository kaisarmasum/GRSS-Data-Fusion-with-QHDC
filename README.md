# 🌊 QuantumHDC for Flood Mapping (NASA BEYOND Challenge 2024)

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
   - Map feature vectors into quantum-inspired HD space
3. **Encoding & Superposition**:
   - Class-based HD vectors accumulated via binding
4. **Similarity Matching**:
   - Associative memory retrieves most similar class vector

### 🧪 Example Architecture

```
Track 1 (SAR) ───┐               ┌─> Class Vector 1
                 ├─> HDC Fusion ─┼
Track 2 (Optical)┘               └─> Class Vector 3
```

---

## 🧪 Results

| Model                     | Accuracy | Domain         |
|--------------------------|----------|----------------|
| Track 1 (SAR) Only       | 85–90%   | Binary         |
| Track 2 (Optical) Only   | 88–92%   | Binary         |
| Dual-Input Quantum HDC   | **94–98%** | Binary    |

---

## 📁 Repository Contents

| File                                | Description                                  |
|-------------------------------------|----------------------------------------------|
| `Track1.ipynb`                      | HDC modeling using Track 1 SAR data          |
| `Track 2.ipynb`                     | HDC modeling using Track 2 optical data      |
| `Multimodal_DualInputQuantumHDC.ipynb` | Joint SAR + Optical fusion model         |

---

## 🧑‍💻 Contributors

## 🧑‍💻 Contributors

| Name | 🎓 Affiliation | 🔗 Google Scholar |
|------|----------------|-------------------|
| Abu Kaisar Mohammad Masum| University of Louisiana at Lafayette | [🔗]([https://scholar.google.com/citations?user=B194MGYAAAAJ&hl=en]) |
| Mehran Shoushtari Moghadam | Case Western Reserve University | [🔗]([(https://scholar.google.com/citations?user=1TsiuPcAAAAJ&hl=en)]) |
| Sercan Aygun | University of Louisiana at Lafayette | [🔗]([https://scholar.google.com/citations?user=9CMxwUQAAAAJ&hl=en]) |
| M. Hassan Najafi| Case Western Reserve University | [🔗]([https://scholar.google.com/citations?user=vIc-83QAAAAJ&hl=en]) |


---

## 🚀 Getting Started

### 1. Run Notebooks

Open each track's notebook or the dual-input fusion notebook:

```bash
jupyter notebook Track1.ipynb
jupyter notebook Track\ 2.ipynb
jupyter notebook Multimodal_DualInputQuantumHDC.ipynb
```

---

## 🔑 Key Technologies

- [Qiskit AerSimulator](https://qiskit.org/)
- [Hyperdimensional Computing (HDC)](https://ieeexplore.ieee.org/document/8959495)
- Sobol sequence-based projection
- Quantum-inspired learning
- SAR and optical data fusion

---

## 📜 Citation

If you use this work, please cite:

```
TBA
```
# GRSS-Data-Fusion
# 7/14/2025
