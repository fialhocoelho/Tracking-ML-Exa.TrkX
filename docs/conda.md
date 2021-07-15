## Install conda environment for GPU usage

**Warning**: It's recommended to use [CUDA driver version 10.2](https://developer.nvidia.com/cuda-10.2-download-archive) to preserve the compatibility with the pipeline dependencies. 


Create a environment with the correct dependencies:

```
conda create -n exatrkx-tracking -f environment.yml
conda activate exatrkx-tracking
```

You should be ready for the [Quickstart](https://hsf-reco-and-software-triggers.github.io/Tracking-ML-Exa.TrkX/pipelines/quickstart)!
