# Deep Learning Techniques for Digital Cardiac Auscultation (IEEE BSN 2025 Tutorial)

## Installation Requirements

### Recommended Tools & Software
- **uv** (preferred) *or* **conda**
- **ffmpeg 7**
- **Python 3.13**

---

## Instructions

### 1. Install `uv` (Recommended)

`uv` is a fast Python package installer and resolver. Choose **one** of the following methods:
```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```
Consult https://docs.astral.sh/uv/getting-started/installation/#standalone-installer for alternative methods of installation.

### 2. Create and activate venv
In the directory of this repo run:
```
uv venv
source ./venv/bin/activate
```

### 3. Run workshop notebook
```
jupyter-lab
```
Open the file TutorialBSN25.ipynb inside `jupyter-lab`.

### Errors with torchcodec
Torchcoded may have some problems due to dependecies with ffmpeg7.
Install ffmpeg7 following https://github.com/oop7/ffmpeg-install-guide

