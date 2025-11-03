# Image Processing and Analysis – Complete Digital Image Processing Pipeline

This repository presents a comprehensive implementation of a digital image processing pipeline using Python and OpenCV.  
The project demonstrates all key stages of image processing, from acquisition and noise simulation to segmentation and feature evaluation, on a real-world image.

## 🎯 Objective
To design, implement, and evaluate a complete digital image processing workflow that includes acquisition, preprocessing, filtering, segmentation, feature extraction, and result visualization.

## 🧠 Processing Pipeline
1. **Image Acquisition:** A real-world sunset image captured using a smartphone, chosen for its lighting contrast and gradient characteristics.
2. **Noise Modeling:** Artificial Gaussian and Salt-and-Pepper noise applied to simulate real-world distortions.
3. **Preprocessing and Enhancement:** Grayscale conversion, resizing, histogram equalization, and contrast stretching to enhance visibility.
4. **Filtering and Denoising:** Application and comparison of median and Gaussian filters, evaluated using PSNR and SSIM metrics.
5. **Segmentation:** Otsu’s thresholding and Canny edge detection to separate illuminated and dark regions and highlight boundaries.
6. **Feature Extraction:** Contour detection and centroid computation to analyze geometric and spatial properties of segmented regions.
7. **Result Visualization and Evaluation:** Visualization of each processing stage with analysis of performance, effectiveness, and possible improvements.

## 📊 Key Outcomes
- Improved image clarity and noise reduction through spatial filtering.  
- Accurate segmentation of bright and dark regions using Otsu’s thresholding.  
- Effective boundary detection via Canny edge detection.  
- Successful feature extraction demonstrating contour-based object localization.  
- End-to-end visualization showcasing the transformation from raw image to analyzed output.

## 📁 Repository Contents
| File | Description |
|------|--------------|
| `IPA code.ipynb` | Jupyter Notebook containing full implementation and outputs |
| `sunset.jpg` | Input image used for analysis |
| `results/` | (Optional) Folder containing generated output images |
| `report.pdf` | IEEE-formatted report summarizing the complete pipeline |

## ⚙️ How to Run
### In Google Colab
1. Open the notebook in Google Colab.  
2. Upload `sunset.jpg` when prompted (if not found).  
3. Run all cells sequentially.

### In Local Jupyter
1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/ImageProcessingPipeline.git
