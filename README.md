# ICRO Image Enhancement Framework

A deep learning-based image enhancement framework designed to improve low-quality images and generate enhanced outputs with corresponding image quality metrics.

---

## Overview

The ICRO Image Enhancement Framework processes user-selected images through an image enhancement pipeline and produces:

* Enhanced image outputs
* Image quality metrics
* Visual comparison results

---

## System Requirements

### Hardware

| Component | Requirement                           |
| --------- | ------------------------------------- |
| RAM       | Minimum 8 GB                          |
| GPU       | Dedicated GPU with at least 4 GB VRAM |

### Operating System

* Windows 10
* Windows 11

### Software

* Python 3.10 or newer
* Pip Package Manager

### Required Libraries

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

---

## Installation

### Step 1: Open Command Prompt

Press **Win + R**, type:

```bash
cmd
```

and press **Enter**.

### Step 2: Navigate to the Project Directory

Example:

```bash
cd C:\Users\Admin\Documents\ICRO_Project
```

### Step 3: Install Required Libraries

Run the install_packages.exe file to install all the necessary libraries and packages.
---

## Project Structure

```text
ICRO_Project/
│
├── ICRO.ipynb
├── frcnnval.ipynb
├── checkpoints/
│   └── best_model.pth
├── weights/
│   └── best.pt
├── input_images/
└── output_images/
```

> **Important:**
> The trained model files must remain in their designated folders. Moving, renaming, or deleting these files may cause the framework to fail.

---

## Running the Framework

### Method 1: Jupyter Notebook

1. Open Command Prompt.
2. Navigate to the project folder.

```bash
cd C:\Users\Admin\Documents\ICRO_Project
```

3. Launch Jupyter Notebook.

```bash
jupyter notebook
```

4. Open `ICRO.ipynb`.
5. Run all notebook cells from top to bottom.
6. Select the image(s) when prompted.
7. Wait for processing to finish.
8. Enhanced outputs will be generated automatically.

---

## Using the Framework

### Step 1

Prepare the image(s) to be enhanced.

### Step 2

A file explorer window will appear.

Select the image to be processed.

### Step 3

Click **Upload**.

### Step 4

Wait for the enhancement process to complete.

### Step 5

View the generated outputs inside the `output_images` folder.

---

## Output

The framework generates:

* Enhanced image files
* Performance metrics
* Visual comparison results

All outputs are saved automatically in the designated output directory.

---

## Troubleshooting

### ModuleNotFoundError

**Cause:** Missing Python package.

**Solution:**

```bash
pip install <package_name>
```

---

### Model File Not Found

**Cause:** Missing or misplaced model files.

**Solution:**

Verify that all `.pth` and `.pt` files are present in their correct directories.

---

### Program Closes Unexpectedly

**Cause:** Runtime error or missing dependency.

**Solution:**

* Check the Command Prompt output for error messages.
* Verify that all required libraries are installed.

---

### CUDA or GPU Error

**Cause:** GPU driver, CUDA, or PyTorch compatibility issue.

**Solution:**

* Run the framework using CPU mode.
* Install the appropriate version of PyTorch compatible with your CUDA version.

---

## Authors

Developed as part of an undergraduate thesis project.

**Researchers**

* Agres, Zyrach Adrian A.
* Guernaldo, Mardyson Justin D.
* Lejano, Nathaniel O.

---

## License

This project is intended for academic and research purposes.
