# 🌙 Low-Light Image Enhancement

A training-free low-light image enhancement framework that combines frequency decomposition, intuitionistic fuzzy illumination modelling, and graph-based texture refinement to improve image visibility while preserving structural details.

---

## 📖 Overview

Low-light image enhancement (LLIE) is an important task in computer vision that aims to improve the visibility and quality of images captured under poor lighting conditions. Unlike deep learning approaches that require large datasets and extensive GPU training, this project presents a training-free framework based on mathematical modelling and image processing techniques.

The proposed framework combines:

- Frequency decomposition
- Intuitionistic Fuzzy Sets (IFS)
- Hamacher T-Norm
- Spectral Graph Refinement
- SLIC Superpixels
- Guided Filtering
- LAB Color Calibration

to enhance illumination while preserving image structure and suppressing noise.

---

## ✨ Key Features

- Training-free image enhancement
- Frequency-aware illumination recovery
- Intuitionistic Fuzzy Set (IFS) modelling
- Graph-based texture refinement
- Adaptive sharpening
- Noise suppression
- Guided filtering
- LAB colour calibration
- Dynamic exposure correction

---

## 🏗️ Framework Pipeline

1. Non-Local Means Denoising
2. Base–Detail Decomposition
3. Intuitionistic Fuzzy Illumination Recovery
4. SLIC Superpixel Segmentation
5. Graph Spectral Texture Refinement
6. Guided Filtering
7. LAB Colour Calibration
8. Dynamic Range Anchoring

---

## 📊 Dataset

- LOL-v1 (Low-Light) Dataset

---

## 📈 Performance

| Metric | Value |
|---------|-------|
| PSNR | 16.56 dB |
| SSIM | 0.7185 |

---

## 🛠️ Technologies Used

- Python
- OpenCV
- NumPy
- SciPy
- Scikit-image
- Matplotlib
- Jupyter Notebook

---

## 📂 Repository Structure

```
Low-Light-Image-Enhancement/
│
├── image_enhancement.ipynb
├── README.md
├── requirements.txt
├── .gitignore
├── images/
└── paper/
```

---

## 🚀 How to Run

Clone the repository:

```bash
git clone https://github.com/Divya150107/Low-Light-Image-Enhancement.git
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```
image_enhancement.ipynb
```

Run all cells.

---

## 📷 Results

The proposed framework improves image visibility while preserving texture, reducing noise, and maintaining natural colour consistency. It demonstrates competitive structural similarity on the LOL-v1 benchmark dataset without requiring any model training.

---

## 🔮 Future Work

- GPU acceleration for graph construction
- Real-time image enhancement
- HDR image enhancement
- Video low-light enhancement
- Mobile and edge-device deployment

---

## 👩‍💻 Authors

- Divya Sree P
- Krithika A

**M.Sc. Data Science**  
Vellore Institute of Technology
