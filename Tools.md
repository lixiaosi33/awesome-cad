- [http://pytorch.org](http://pytorch.org)
```bash
export CMAKE_PREFIX_PATH=[anaconda root directory]

# Install basic dependencies
conda install numpy pyyaml mkl setuptools cmake gcc cffi

# Add LAPACK support for the GPU
conda install -c soumith magma-cuda80 # or magma-cuda75 if CUDA 7.5
```
