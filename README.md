# 🖼️ AI-Powered Image Upscaler

![Jupyter Notebook](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)
![Python](https://img.shields.io/badge/Python-3.8+-blue?style=for-the-badge&logo=python)
![Real-ESRGAN](https://img.shields.io/badge/Model-Real--ESRGAN-success?style=for-the-badge)

A Python-based AI image upscaler utilizing **Real-ESRGAN**, specifically optimized for enhancing and upscaling 2D anime art and illustrations without losing quality. 

## ✨ Features

- **High-Quality Upscaling:** Leverages the power of the Real-ESRGAN architecture to intelligently upscale images.
- **Anime & Illustration Optimized:** Specially tuned to handle the lines, colors, and textures typical in 2D anime and digital art.
- **Interactive Environment:** Fully contained within a Jupyter Notebook for easy step-by-step execution, visualization, and tweaking.
- **Accessible & Easy to Use:** Can be run locally or easily ported to cloud environments like Google Colab for free GPU acceleration.

## 🛠️ Prerequisites

To run this notebook locally, you will need:
- Python 3.8 or higher
- [Jupyter Notebook](https://jupyter.org/install) or JupyterLab
- A dedicated GPU (NVIDIA with CUDA support is highly recommended for faster processing)

## 🚀 Getting Started

1. **Clone the repository:**
   ```bash
   git clone https://github.com/owaiskhan2501000/AI-Powered-Image-Upscaler.git
   cd AI-Powered-Image-Upscaler
   ```

2. **Install the required dependencies:**
   *(Note: Adjust the installation commands based on the specific dependencies listed inside the notebook, typically PyTorch, OpenCV, and Real-ESRGAN)*
   ```bash
   pip install -r requirements.txt
   ```
   *If you are running this in Google Colab, the notebook likely contains the `!pip install` commands needed to set up the environment.*

3. **Launch Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```

4. **Run the Upscaler:**
   - Open the provided `.ipynb` file.
   - Run the setup cells to load the Real-ESRGAN model.
   - Provide the path to your input image (or upload it if using Colab).
   - Execute the upscaling cell and view/download your high-resolution output!

## 🧠 How it Works

This project uses [Real-ESRGAN](https://github.com/xinntao/Real-ESRGAN), an extension of ESRGAN (Enhanced Super-Resolution Generative Adversarial Networks). It is trained with pure synthetic data and is exceptionally good at restoring and upscaling low-resolution, noisy, or compressed images—making it perfect for digital illustrations and anime art.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/owaiskhan2501000/AI-Powered-Image-Upscaler/issues).

## 📝 License

This project is licensed under the [MIT License](LICENSE) - see the LICENSE file for details.
