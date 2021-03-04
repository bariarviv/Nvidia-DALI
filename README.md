[![Documentation](https://img.shields.io/badge/Nvidia%20DALI-documentation-brightgreen.svg?longCache=true)](https://docs.nvidia.com/deeplearning/dali/user-guide/docs/index.html)

# Nvidia DALI

Deep learning applications require complex, multi-stage pre-processing data pipelines. Such data pipelines involve compute-intensive operations that are carried out on the CPU. For example, tasks such as: load data from disk, decode, crop, random resize, color and spatial augmentations and format conversions, are mainly carried out on the CPUs, limiting the performance and scalability of training and inference.

In addition, the deep learning frameworks have multiple data pre-processing implementations, resulting in challenges such as portability of training and inference workflows, and code maintainability.

NVIDIA DALI (R), NVIDIA’s Data Loading Library, is a collection of highly optimized building blocks, and an execution engine, to accelerate the pre-processing of the input data for deep learning applications. DALI provides both the performance and the flexibility to accelerate different data pipelines as one library. This library can then be easily integrated into different deep learning training and inference applications.

## Highlights
- Full data pipeline–accelerated from reading the disk to getting ready for training and inference.
- Flexibility through configurable graphs and custom operators.
- Support for image classification and segmentation workloads.
- Ease of integration through direct framework plugins and open source bindings.
- Portable training workflows with multiple input formats: JPEG, PNG (fallback to CPU), TIFF (fallback to CPU), BMP (fallback to CPU), raw formats, LMDB, RecordIO, TFRecord.
- Extensible for user-specific needs through open source license.

This library is open sourced and it is available in the NVIDIA GitHub repository: https://github.com/NVIDIA/DALI

## Files
1. Nvidia DALI_BariArviv.ipynb
2. Nvidia DALI_BariArviv.ppsx

The presentation contains: an explanation of Nvidia DALI, the installation process, connection to the server and a running example.
