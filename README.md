# EN3160 - Intensity Transformations & Spatial Filtering

**Assignment 01** | Computer Vision / Image Processing  
**Index:** 230563H  

---

## 📌 Overview
This repository contains the implementation and analysis for **EN3160 Assignment 01: Intensity Transformations and Spatial Neighborhood Filtering**. The project explores fundamental digital image processing techniques using Python, OpenCV, NumPy, and Matplotlib.

---

## 📁 Repository Structure
```
.
├── code_notebook.ipynb                                  # Main Jupyter Notebook with code, plots, and analysis
├── 230563H intensity transformations and spatial filtering.pdf # Exported assignment report (10 pages)
├── en3160_assignment_01.pdf                             # Assignment specification document
└── figures/                                             # Input images used for processing
```

---

## 🚀 Key Topics & Tasks Covered
1. **Intensity Transformations & Gamma Correction**
   - Power-law transformations, contrast stretching, and intensity slicing.
   - White matter and gray matter accentuation on brain MRI scans.
2. **Histogram Equalization & Matching**
   - Global histogram equalization.
   - Histogram matching / specification.
3. **Spatial Filtering & Neighborhood Processing**
   - Mean (box) filtering, Gaussian smoothing.
   - Median filtering for impulse (salt-and-pepper) noise reduction.
   - High-pass filtering (Laplacian) and unsharp masking / high-boost filtering.

---

## 🛠️ Requirements & Setup
To run the notebook locally:

```bash
# Clone the repository
git clone https://github.com/jaindusamaranayaka/EN3160-A01-Intensity-Transformations-and-Neighborhood-Filtering.git

# Navigate to the project directory
cd EN3160-A01-Intensity-Transformations-and-Neighborhood-Filtering

# Run Jupyter Notebook
jupyter notebook code_notebook.ipynb
```

**Dependencies:**
- Python 3.x
- `numpy`
- `opencv-python` (`cv2`)
- `matplotlib`
