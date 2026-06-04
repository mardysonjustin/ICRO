User Manual

========================================

1. OVERVIEW
   ========================================

The framework is designed to enhance low-quality images using a deep learning-based image enhancement pipeline. The framework processes user-selected images and generates enhanced output images with metrics scores.

========================================
2. SYSTEM REQUIREMENTS
======================
Hardware:
* At least 8GB RAM
* Dedicated GPU with at least 4GB VRAM

Operating System:

* Windows 10 or Windows 11

Required Software:

* Python 3.10 or newer
* Pip Package Manager

Required Libraries:

* numpy
* pandas
* opencv-python
* torch
* torchvision
* pillow
* matplotlib
* scikit-image
* lpips
* ultralytics
* thop

========================================
3. INSTALLATION
===============

Step 1:
Open Command Prompt.

Step 2:
Navigate to the project directory.

Example:

cd C:\Users\Admin\Documents\ICRO_Project

Step 3:
Install all required libraries.

pip install numpy pandas opencv-python torch torchvision pillow matplotlib scikit-image lpips ultralytics thop

========================================
4. PROJECT FILES
================

Ensure the following files are present:

ICRO_Project
│
├── ICRO.ipynb
├── frcnnval.ipynb
├── checkpoints
│   └── best_model.pth
├── weights
│   └── best.pt
├── input_images
└── output_images

Note:
The trained model files must remain in their designated folders. Moving or renaming these files may cause the system to fail.

========================================
5. RUNNING IT
=====================

Method 1: Jupyter Notebook

1. Open Command Prompt.
2. Navigate to the project folder.
3. Launch Jupyter Notebook.

jupyter notebook

4. Open ICRO.ipynb.
5. Execute all notebook cells from top to bottom.
6. When prompted, select the image(s) for enhancement.
7. Wait for processing to complete.
8. Enhanced images will be saved automatically.

========================================
6. USING THE SYSTEM
===================

Step 1:
Prepare the image(s) to be enhanced.

Step 2:
File expolorer will pop up, choose the image to be processed.

Step 3:
Click Upload on the file explorer.

Step 4:
Wait until processing is completed.

Step 5:
View the enhanced images/outputs in the output folder.

========================================
7. OUTPUT
=========

The system generates:

* Enhanced image files
* Performance metrics
* Visual comparison results

Output files are stored in the designated output directory.

========================================
8. TROUBLESHOOTING
==================

Problem:
ModuleNotFoundError

Solution:
Install missing packages using:

pip install <package_name>

Problem:
Model file not found

Solution:
Verify that all .pth and .pt files are present in their correct folders.

Problem:
Program closes unexpectedly

Solution:
Check the Command Prompt window for error messages and verify all dependencies are installed.

Problem:
CUDA or GPU error

Solution:
Run the system using CPU mode or install the correct version of PyTorch for your GPU.

========================================
9. AUTHORS
==========

Developed as part of an undergraduate thesis project.

Agres,Zyrach Adrian A.
Guernaldo, Mardyson Justin D.
Lejano, Nathaniel O.
