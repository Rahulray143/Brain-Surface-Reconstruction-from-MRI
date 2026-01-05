# Brain-Surface-Reconstruction-from-MRI
3D brain surface reconstruction from MRI using medical imaging tools for volume and mesh analysis.

# 3D Brain Surface Reconstruction from MRI Data 🧠

This project demonstrates the complete workflow of **3D brain surface reconstruction** starting from raw MRI slices to a final **3D mesh model**.

The pipeline includes preprocessing, masking, reconstruction, registration, and mesh visualization using standard **medical imaging tools**.

---

## 📌 Project Overview

- Input: MRI volume data (Axial and Sagittal slices)
- Output:
  - 3D reconstructed brain surface
  - Mesh file for surface and volume analysis
- Visualization and analysis performed using **ITK-SNAP, 3D Slicer, and MeshLab**

This project focuses on understanding the **end-to-end medical imaging pipeline** rather than automated AI-based segmentation.

---

## 🧠 Workflow Pipeline

1. **MRI Data Acquisition**
   - Axial and sagittal MRI slices used as input

2. **Preprocessing**
   - Noise handling and basic image preparation

3. **Masking**
   - Brain region isolated from background and non-brain tissues

4. **SRR (Super-Resolution Reconstruction)**
   - Improved spatial resolution of MRI volume

5. **dHCP Processing**
   - Structural consistency and refinement

6. **Registration**
   - Alignment of slices into a common spatial reference

7. **Brain Extraction**
   - Removal of non-brain components


8. **Mesh Generation**
   - Conversion of volume to surface mesh

9. **Visualization & Analysis**
    - Surface, volume, and structural analysis using MeshLab

---

## 🛠 Tools & Software Used

- **ITK-SNAP** – Masking and segmentation
- **3D Slicer** – Volume reconstruction and registration
- **MeshLab** – 3D surface visualization and mesh analysis

---

## 📊 Results

- Successfully reconstructed a **3D brain surface** from MRI volume data
- Generated a **mesh file** for:
  - Surface visualization
  - Volume estimation
  - Structural analysis

The images below show different views of the reconstructed brain surface.

---

## 📷 Sample Visualizations

(Add screenshots of MeshLab visualization here)

---

## 📌 Applications

- Medical image analysis
- Brain morphology study
- Neuroimaging visualization
- Preprocessing for further segmentation or ML tasks

---

## 🚀 Future Scope

- Region-wise brain segmentation
- Quantitative volume analysis
- Integration with machine learning models
- Automated MRI preprocessing pipeline

---

## 👤 Author

**Rahul Yadav**

