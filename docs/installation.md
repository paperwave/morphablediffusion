
# Installation
The code was tested with CUDA 11.3, Python 3.9, and PyTorch 1.11.0.
## 1. Clone the repo

```bash
git clone https://github.com/xiyichen/morphablediffusion.git
cd morphablediffusion
```

## 2. Create environment and install necessary dependencies

Create a new `conda` [environment](https://www.anaconda.com/) with all dependencies: 
```bash
conda create -y --name morphable_diffusion python=3.9.2
pip install fvcore iopath torch==1.11.0+cu113 torchvision==0.12.0+cu113 torchaudio==0.11.0 --extra-index-url https://download.pytorch.org/whl/cu113
pip install --no-index --no-cache-dir pytorch3d -f https://dl.fbaipublicfiles.com/pytorch3d/packaging/wheels/py39_cu113_pyt1110/download.html
pip install -r requirements.txt
```
