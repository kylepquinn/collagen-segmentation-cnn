# Collagen Segmentation CNN

This repository contains the trained convolutional neural network (CNN) for segmentation of collagen SHG images. The publication associated with this CNN can be found [here](https://doi.org/10.1002/jbio.202200191).

---

## Disclaimer

All files within this repository are property of:

> Kyle Quinn (kpquinn@uark.edu)
>
> Quantitative Tissue Diagnostics Laboratory (Quinn Lab)
>
> University of Arkansas
>
> Fayetteville, AR 72701

**_Use at your own risk and please properly reference these files if used in own analyses._**

---

## File List

- `collagen-cnn.onnx`

---

## Getting Started

To get started using these functions, download this repository and extract the .zip file. Add the files folder ('collagen-segmentation-cnn\files') to your path in MATLAB using the _Set Path_ wizard.

This repository contains a ".onnx" file. The [Open Neural Network Exchange](https://onnx.ai) is a neural network format that is compatible across multiple programming languages. For this particular application, the neural network was trained using PyTorch, but is primarily utilized in MATLAB. Please note if your language of choice supports ONNX files, or requires specific add-ons for ONNX support.

---

## Examples and Documentation

Within this repository, there are documentation markdown (.md) files that contain a MATLAB-like information about each function, which can be found in this root folder. The 'documentation' folder contains figures for the markdown files.

Additionally, there are live scripts (.mlx) within the 'examples' folder that provide examples on how to properly utilize the functions within this repository.

---
