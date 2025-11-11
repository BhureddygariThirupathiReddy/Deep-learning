Reconstructing Old Photos Using Deep Learning
Restore and enhance aged, damaged, or low-quality historical photographs using advanced deep learning techniques.

Project Overview
This project leverages state-of-the-art neural networks for automated restoration of old photos. By combining face enhancement, scratch detection, and global image correction, it offers an efficient solution for both personal and institutional heritage preservation.

Motivation
Preserve cultural heritage: Restore historic images for museums, archives, and personal memorabilia.

Enhance documentation: Improve visual quality of records for researchers and historians.

Public engagement: Make history accessible through reconstructed images for exhibitions and online platforms.

Features
End-to-end automated restoration pipeline

Face enhancement using generative models

Scratch detection and removal

Support for high-resolution photos

Handles multiple types of damage (blur, noise, color fading, scratches, etc.)

Batch processing for large archives

System Requirements
Software

OS: Windows

Python ≥ 3.6

Framework: Google Colab (recommended for GPU access)

Libraries: Numpy, Pandas, Matplotlib, Seaborn, PyTorch, Keras, RetinaNet

Installation & Setup
Clone the repository

Install necessary Python packages (see requirements.txt)

(Optional) Set up Google Colab for GPU support

Usage
Upload your images to the input directory or follow instructions in the Jupyter/Colab notebook

Run the restoration pipeline (supports batch and single-image modes)

View before-and-after results with built-in visualization tools

Download restored images for archival or sharing

Methodology
Utilizes CNNs and GANs for restoration and enhancement

Scratch detection module isolates and corrects defects

Global restoration improves overall image quality and color fidelity

Face module uses generative priors for realistic facial reconstruction

Sample Results
Enhanced clarity and sharpness for faces

Restoration of faded colors, removal of scratches

Refined details across diverse historical photographs

Testing
Unit tests for internal logic and module integration

Test cases for blurry image restoration, face enhancement, and scratch removal

Results demonstrate reliable restoration across sample images

Future Scope
Integration of real-time restoration for social media and digital sharing

Enhanced colourization and texture restoration

Wider support for non-facial images (landscapes, documents, artifacts)

Applications in forensic analysis, historical research, entertainment, and gaming

References
GFPGAN

DeOldify, SRGAN/ESRGAN, UNet, Deep Image Prior methods
