# 🧠 Neuroimaging Practice Repository

**Note:** This repository is part of an extension of the AI Leadership Training Program offered by [NeuroCogniAI](https://nc-ai.ca/). It is designed to help trainees and learners gain practical experience working with neuroimaging data using open-source tools.

This repository is a comprehensive resource for anyone interested in working with neuroimaging data, particularly structural MRI scans in NIfTI format. It includes everything you need to get started, from  datasets to runnable Jupyter notebooks and a `requirements.txt` file for setting up your environment.

---

## 🔍 What’s Included

### 🗂️ Datasets
A collection of practice-ready NIfTI MRI scans, sourced from reputable open-access datasets.

### 📓 Jupyter Notebooks
Reusable notebooks that demonstrate:

- How to load `.nii` or `.nii.gz` files using NiBabel
- Visualize brain volumes across axial, sagittal, and coronal planes
- Extract individual slices from any orientation
- Save selected or full sets of slices as `.jpg` or `.png` images
- Speed up processing using basic parallelization techniques

### 📦 Requirements
A `requirements.txt` file lists all necessary Python packages for a complete neuroimaging toolkit, including:

- nibabel
- numpy
- matplotlib
- opencv-python
- ipywidgets

---

## 📁 Repository Contents

This repository includes the following key files:

- `load_data.ipynb`: A starter notebook that loads `.nii` brain scans, shows individual slices, and prints scan metadata like shape and voxel info.
- `3D_view.ipynb`: An interactive tool that displays sagittal, coronal, and axial views side-by-side, each with a slider to scroll through the brain.
- `save_slides.ipynb`: Converts slices from a 3D brain volume into `.jpg` images using OpenCV, useful for creating datasets or quick visual inspection.

---

Link to Data: [https://nda.nih.gov/edit_collection.html?id=1151)](https://nda.nih.gov/edit_collection.html?id=1151)

---

# How to Set Up This Project Locally

This guide explains how to:

1. Download the project from GitHub
2. Set up a virtual environment
3. Install all required dependencies using `requirements.txt`

---

## Prerequisites

Before you begin, ensure you have the following installed:

| Tool                   | Purpose                         | How to Check                              |
| ---------------------- | ------------------------------- | ----------------------------------------- |
| Python (3.8 or higher) | Required to run the project     | `python --version` or `python3 --version` |
| pip                    | Python's package installer      | `pip --version`                           |
| Git                    | To clone the repository         | `git --version`                           |
| virtualenv (optional)  | To create isolated environments | `pip install virtualenv`                  |

You can install Python from: [https://www.python.org/downloads/](https://www.python.org/downloads/)

---

## Step 1: Download the Project

### Option A: Clone via Git (recommended)

```bash
git clone https://github.com/username/repository-name.git
```

Replace `username` and `repository-name` with the actual GitHub path.

### Option B: Download ZIP

1. Go to the GitHub repository page.
2. Click the "Code" button.
3. Select "Download ZIP".
4. Unzip the file on your computer.

---

## Step 2: Navigate into the Project Directory

```bash
cd repository-name
```

---

## Step 3: Create a Virtual Environment

### Option A: Using `venv` (built-in)

```bash
python -m venv venv
```

### Option B: Using `virtualenv`

```bash
virtualenv venv
```

This creates a folder called `venv` that contains an isolated Python environment.

---

## Step 4: Activate the Virtual Environment

### On Windows (Command Prompt)

```bash
venv\Scripts\activate
```

### On macOS/Linux

```bash
source venv/bin/activate
```

Once activated, your terminal prompt will show the name of the virtual environment.

---

## Step 5: Install Dependencies

Make sure you're inside the project directory where `requirements.txt` is located, then run:

```bash
pip install -r requirements.txt
```

This installs all required Python packages.

---

## Step 6: Run or Explore the Project

You can now run scripts, start notebooks, or launch apps. For example:

```bash
python app.py
```

Or:

```bash
jupyter notebook
```

---

## Step 7: Deactivate the Virtual Environment

When you're done working:

```bash
deactivate
```

This returns you to your system's global Python environment.

---

## Optional: Remove the Virtual Environment

If you want to delete the environment:

### macOS/Linux

```bash
rm -r venv
```

### Windows

```bash
rmdir /s venv
```

---

## Quick Setup Commands

```bash
git clone https://github.com/username/repository-name.git
cd repository-name
python -m venv venv
source venv/bin/activate    # Use venv\Scripts\activate on Windows
pip install -r requirements.txt
```

---





