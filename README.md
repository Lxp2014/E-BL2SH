# E-BL2SH
## Environment setup
- Python 3.8.13
- Pytorch 2.0.0
- NVIDIA GPU 4090 + CUDA 11.7
  
You can create a new [Anaconda](https://www.anaconda.com/products/individual) environment as follows.
<br>
Clone this repository.
```
git clone https://github.com/Lxp2014/E-BL2SH.git
```
Install the above dependencies.
```
cd EBL2SH
conda env create -f EBL2SH.yaml
```
Install the above dependencies.
```
cd EBL2SH
conda env create -f EBL2SH.yaml
```
## Dataset
[The datasets](https://drive.google.com/drive/folders/1cGjTEeurr6Ka4Tb5jTZDtB8IPlaBBuQG?usp=sharing) can be downloaded via Google Drive.

## Quick start
### Initialization
- Change the parent directory
```
cd EBL2SH
conda activate EBL2SH
```
### Test
- Test on BL2SHD-S
```
bash test_syn.sh
```
- Test on BL2SHD-Rsimple
```
