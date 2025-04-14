# Advanced Image Deblurring and Enhancement with GPU Acceleration

This project demonstrates advanced image processing techniques, specifically focusing on image **deblurring**, **enhancement**, and **text extraction**. The goal is to improve image quality using the **Wiener deconvolution** method and accelerate processing with **CUDA-based GPU optimization**. The final step involves using **Tesseract OCR** to extract textual content from the processed images.

---

## 🔍 Features

- **Deblurring using Wiener Deconvolution**
- **GPU-accelerated Sharpening Filter** using CUDA (via PyCUDA)
- **Text Extraction** from images using Tesseract OCR
- **Performance comparison** between CPU and GPU execution

---

## 🛠 Technologies Used

### 🐍 Python Libraries
- **NumPy** – for numerical operations and image data handling
- **OpenCV** – to read, manipulate, and display images
- **Matplotlib** – for visualizing images and results
- **PyCUDA** – to run custom CUDA kernels for GPU processing
- **Pytesseract** – for text extraction from processed images

### ⚙️ CUDA Toolkit
- Used to write and execute custom sharpening kernels on the GPU

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/image-enhancement-gpu.git
cd image-enhancement-gpu
```

### 2. Install Dependencies

Make sure you have Python 3.7+ installed. Then install required packages:

```bash
pip install numpy opencv-python matplotlib pycuda pytesseract
```

> **Note:** You also need the [CUDA Toolkit](https://developer.nvidia.com/cuda-toolkit) and [Tesseract OCR](https://github.com/tesseract-ocr/tesseract) installed on your system.

### 3. Run the Project

```bash
python main.py
```

---

## 📂 Project Structure

```text
├── main.py                   # Main script
├── deblur.py                # Wiener deconvolution logic
├── gpu_sharpen.cu           # CUDA kernel for image sharpening
├── ocr_extract.py           # Tesseract OCR integration
├── utils.py                 # Utility functions
├── images/                  # Input and sample images
├── results/                 # Output results
└── README.md
```

---

## 📊 Performance

We compare CPU vs GPU performance for the image sharpening step, showcasing the acceleration achieved via CUDA.

| Operation         | CPU Time | GPU Time |
|------------------|----------|----------|
| Sharpening Filter| ~X ms    | ~Y ms    |

> Replace X and Y with actual benchmark data after running tests.

---
## ✍️ Author

**Geeta Seshapalli**  
🔗 [LinkedIn](https://www.linkedin.com/in/geetaseshapalli)  
🐱 [GitHub](https://github.com/geeta-seshapalli)

## 🙌 Acknowledgements

- [PyCUDA Documentation](https://documen.tician.de/pycuda/)
- [Tesseract OCR GitHub](https://github.com/tesseract-ocr/tesseract)
- [OpenCV Docs](https://docs.opencv.org/)

> _If you find this repository helpful, please give it a ⭐️!_


