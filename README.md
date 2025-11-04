# Deep Learning Techniques for Digital Cardiac Auscultation (IEEE BSN 2025 Tutorial)

## Installation Requirements

### Recommended Tools & Software
- **uv** (preferred) *or* **conda**
- **ffmpeg 7**
- **Python 3.13**

---

## Instructions

### 1. Install `uv` (Recommended)

`uv` is a fast Python package installer and resolver. **It is the recommended package mananger for this tutorial. Stability on conda or poet is not guaranteed.**
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

Alternatively (but not recommended), if you *really* prefer conda you can run:

```
conda create -n tutorial python=3.13 -y
conda activate tutorial 
pip install -r requirements.txt
```
### 3. Run workshop notebook
```
jupyter-lab
```
Open the file TutorialBSN25.ipynb inside `jupyter-lab`.

### Errors with torchcodec
`torchcodec` may have some problems due to dependecies with ffmpeg7.
Install ffmpeg7 following https://github.com/oop7/ffmpeg-install-guide.

