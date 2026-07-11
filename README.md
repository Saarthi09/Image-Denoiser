# 🖼️ Image Denoising Using Principal Component Analysis (PCA)

A Python application that demonstrates image denoising using **Principal Component Analysis (PCA)**. The program reconstructs a grayscale image using a reduced number of principal components, helping suppress noise while preserving the most significant image features.

---

## 📌 Overview

This project applies PCA to a grayscale image to reduce unwanted noise through dimensionality reduction. Instead of using all pixel information, the image is reconstructed from a limited number of principal components, producing a cleaner approximation of the original image.

The application displays the original and reconstructed images side by side for easy comparison.

---

## ✨ Features

- Load any grayscale-compatible image
- Automatic file path detection
- Image reconstruction using PCA
- Adjustable number of principal components
- Side-by-side visualization of original and reconstructed images
- Pixel value clipping to maintain valid image intensity

---

## 🛠️ Technologies Used

- Python 3
- NumPy
- Matplotlib
- Pillow (PIL)
- Scikit-learn (PCA)

---

## 📂 Project Structure

```
Image-denoising-using-Python/
│
├── main.py
├── sample_image.jpg
├── README.md
└── requirements.txt
```

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/Saarthi09/Image-denoising-using-Python.git
```

Navigate into the project:

```bash
cd Image-denoising-using-Python
```

Install the required libraries:

```bash
pip install numpy matplotlib pillow scikit-learn
```

---

## ▶️ Usage

Run the program:

```bash
python main.py
```

When prompted, enter the image filename:

```
Enter file name:
```

Example:

```
sample_image.jpg
```

The application will display:

- Original image
- PCA reconstructed image

---

## 🧠 How It Works

1. The selected image is loaded using Pillow.
2. The image is converted to grayscale.
3. The grayscale image is converted into a NumPy array.
4. Principal Component Analysis (PCA) is applied.
5. The image is reconstructed using a specified number of principal components.
6. The original and reconstructed images are displayed for comparison.

---

## ⚡ Customization

The reconstruction quality depends on the number of principal components.

Current setting:

```python
num_components = 50
```

Increasing this value:

- Better image quality
- Less compression
- Smaller denoising effect

Decreasing this value:

- Stronger dimensionality reduction
- More information removed
- Greater smoothing effect

---

## 📸 Example Output

| Original | PCA Reconstruction |
|----------|--------------------|
| *(Add screenshot here)* | *(Add screenshot here)* |

---

## 🚀 Future Improvements

- Support RGB images
- GUI built with Tkinter
- Save reconstructed images
- Compare different denoising techniques
- Interactive slider for selecting principal components
- Performance benchmarking

---

## 📚 Concepts Demonstrated

- Principal Component Analysis (PCA)
- Image processing
- Dimensionality reduction
- NumPy array manipulation
- Data visualization using Matplotlib

---

## 👨‍💻 Author

**Saarthi Basant**

GitHub: https://github.com/Saarthi09

---

## 📄 License

This project is licensed under the MIT License.
