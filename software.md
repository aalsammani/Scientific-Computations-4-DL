# Software Installation Guide

This guide covers the installation of all software needed for MTSC 821.

---

## 📦 Python Environment

### Option 1: Anaconda (Recommended)

Anaconda provides a complete scientific Python environment.

1. **Download Anaconda:**
   - Visit: https://www.anaconda.com/download
   - Download the appropriate version for your OS

2. **Install Anaconda:**
   - Windows: Run the installer, use default settings
   - macOS: Run the .pkg installer
   - Linux: Run `bash Anaconda3-xxxx-Linux-x86_64.sh`

3. **Create Course Environment:**
   ```bash
   conda create -n mtsc821 python=3.10
   conda activate mtsc821
   conda install numpy scipy matplotlib jupyter pandas scikit-learn
   pip install torch cvxpy
   ```

### Option 2: pip with venv

For a lighter installation:

```bash
# Create virtual environment
python -m venv mtsc821-env

# Activate (Linux/macOS)
source mtsc821-env/bin/activate

# Activate (Windows)
mtsc821-env\Scripts\activate

# Install packages
pip install -r requirements.txt
```

---

## 📓 Jupyter

### Jupyter Lab (Recommended)

```bash
# Install
pip install jupyterlab

# Launch
jupyter lab
```

### Jupyter Notebook (Classic)

```bash
# Install
pip install notebook

# Launch
jupyter notebook
```

### VS Code Integration

1. Install VS Code: https://code.visualstudio.com/
2. Install Python extension
3. Install Jupyter extension
4. Open `.ipynb` files directly in VS Code

---

## 📐 LaTeX

### Windows: MiKTeX

1. Download: https://miktex.org/download
2. Run installer
3. Choose "Install missing packages on-the-fly"

### macOS: MacTeX

1. Download: https://www.tug.org/mactex/
2. Run the installer package

### Linux: TeX Live

```bash
# Ubuntu/Debian
sudo apt-get install texlive-full

# Fedora
sudo dnf install texlive-scheme-full
```

### LaTeX Editors

- **TeXstudio** (Recommended): https://www.texstudio.org/
- **Overleaf** (Online): https://www.overleaf.com/
- **VS Code** with LaTeX Workshop extension

---

## 🔢 MATLAB (Optional)

1. Check if DSU provides MATLAB licenses
2. Download from: https://www.mathworks.com/
3. Required Toolboxes:
   - Optimization Toolbox
   - Statistics and Machine Learning Toolbox

### GNU Octave (Free Alternative)

```bash
# Ubuntu/Debian
sudo apt-get install octave

# macOS (with Homebrew)
brew install octave

# Windows: Download from https://www.gnu.org/software/octave/
```

---

## ✅ Verification

Run this Python script to verify your installation:

```python
# verify_installation.py

import sys
print(f"Python version: {sys.version}")

# Core packages
import numpy as np
print(f"NumPy version: {np.__version__}")

import scipy
print(f"SciPy version: {scipy.__version__}")

import matplotlib
print(f"Matplotlib version: {matplotlib.__version__}")

# Optional packages
try:
    import torch
    print(f"PyTorch version: {torch.__version__}")
except ImportError:
    print("PyTorch not installed (optional)")

try:
    import cvxpy
    print(f"CVXPY version: {cvxpy.__version__}")
except ImportError:
    print("CVXPY not installed (optional)")

print("\n✅ All required packages installed successfully!")
```

---

## 🆘 Troubleshooting

### Common Issues

**Issue:** `pip install` fails with permission error
**Solution:** Use `pip install --user package_name` or use virtual environment

**Issue:** Jupyter kernel not found
**Solution:** 
```bash
python -m ipykernel install --user --name=mtsc821
```

**Issue:** PyTorch CUDA not working
**Solution:** Install CUDA-enabled version:
```bash
pip install torch --index-url https://download.pytorch.org/whl/cu118
```

### Getting Help

- Course office hours
- Stack Overflow (tag questions appropriately)
- Package documentation
- Open an issue on the course repository

---

*Last updated: January 2026*
