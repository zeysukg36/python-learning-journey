# 🖼️ NumPy Image Processing Project

This module focuses on the mathematical foundations of digital images using **NumPy**. By treating images as multi-dimensional tensors, I implemented several core manipulation techniques.

### 🛠️ What's Inside?
- **Broadcasting:** Color inversion ($255 - img$) and brightness adjustments.
- **Grayscale Conversion:** Implemented via weighted dot products ($Y = 0.299R + 0.587G + 0.114B$).
- **Array Slicing:** Image cropping and flipping (horizontal/vertical) without using loops.
- **Channel Isolation:** Separating Red, Green, and Blue layers to analyze color distribution.
- **Clipping:** Managing pixel intensities with `np.clip` to prevent data overflow.

### 📂 Files
- `numpy_image_processing.ipynb`: The main notebook with code and visualizations.
- `sample.png`: The source image used for all matrix operations.

---
*Developed as part of my Python Learning Journey for technical recruitment preparation.*
