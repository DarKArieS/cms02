
# To use something when you login:

### To use CMSSW:
```
source /cvmfs/cms.cern.ch/cmsset_default.sh
```
### To use ROOT6 in local:
```
source /ROOT6/bin/thisroot.sh
```
### To use CUDA for GPU supporting
```
export PATH=/usr/local/cuda-9.0/bin${PATH:+:${PATH}}

export LD_LIBRARY_PATH=/usr/local/cuda-9.0/lib64 ${LD_LIBRARY_PATH:+:${LD_LIBRARY_PATH}}
```

# cms03
installed sofware:
```
nvidia CUDA Toolkit 9.0
CuDNN 7.1
CernVM-FS
ROOT5
ROOT6

Python applications (both for python2 and python3):
numpy
pandas
matplotlib
SciPy
sklearn
tensorflow-gpu
keras
root_numpy
xgboost
```
