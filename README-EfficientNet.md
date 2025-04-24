
# COMP9517 Project EfficientNet Setup Guide

This guide will help you set up the environment and run the `EfficientNet.ipynb` notebook.

## Requirements

All necessary Python packages are listed in the `requirements.txt` file.

### 1. Create and activate a virtual environment (optional but recommended)
```bash
python -m venv venv
# On macOS/Linux
source venv/bin/activate
# On Windows
venv\Scripts\activate
```

**Best to use colab**

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Launch Jupyter Notebook
```bash
jupyter notebook
```

### 4. Open `EfficientNet.ipynb` and run all cells.

---

## Colab set up
```python
!pip install pillow matplotlib numpy pandas scikit-learn timm torch torchvision tqdm
```

- Make sure you have Python 3.8+ and `pip` installed.

