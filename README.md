# A-proposed-video-super-resolution-reconstruction-strategy-using-wavelet-multi-scale-CNNs

# Wavelet Multi-Frame Super-Resolution

This repository contains project materials related to the paper:

**A Proposed Video Super-Resolution Reconstruction Strategy Using Wavelet Multi-Scale Convolutional Neural Networks**

The project focuses on reconstructing high-resolution video frames from low-resolution inputs using wavelet decomposition and convolutional neural networks. The main idea is to decompose low-resolution video frames into wavelet sub-bands, train CNN models to recover multi-scale frequency components, and then reconstruct high-resolution frames using inverse wavelet reconstruction.

## Related Publication

M. A. Elgohary, W. El-Shafai, F. E. Abd El-Samie, M. A. Mohamed, and E. H. Abdelhay,
“A proposed video super-resolution reconstruction strategy using wavelet multi-scale convolutional neural networks,”
*Journal of Optics*, 2024.
DOI: 10.1007/s12596-023-01236-4

## Project Overview

High-resolution images and video frames are important in many applications, including medical imaging, satellite imaging, surveillance, and computer vision. However, increasing image resolution using hardware sensors can be expensive or limited by physical constraints.

This project investigates a learning-based super-resolution approach that combines:

* Multi-frame super-resolution
* Wavelet transform
* Multi-scale frequency decomposition
* Convolutional neural networks
* Quantitative and qualitative image-quality evaluation

## Repository Contents

```text
notebooks/
```

Contains Jupyter notebooks used for deep learning experiments and implementation.

```text
presentation/
```

Contains the project presentation slides.

```text
paper/
```

Contains citation information and publication-related metadata.

```text
src/
```

Reserved for cleaned Python source code if the notebook implementation is later converted into reusable scripts.

```text
data/
```

Placeholder for dataset instructions. Large datasets should not be uploaded directly to GitHub.

```text
results/
```

Placeholder for sample results, figures, reconstructed frames, and evaluation outputs.

## Methods

The approach is based on applying wavelet decomposition to video frames to obtain multiple frequency sub-bands. Separate convolutional neural networks can then be trained to estimate or reconstruct these sub-band representations. Finally, inverse wavelet reconstruction is used to generate the final high-resolution output.

## Evaluation Metrics

The project considers common super-resolution evaluation metrics, including:

* PSNR
* SSIM
* NIQE
* BRISQUE
* Visual comparison of reconstructed frames

## Datasets

The project presentation refers to the DIV2K dataset and standard video test sequences such as City, Calendar, Foliage, and Walk. Large datasets are not included in this repository. Users should download datasets separately from their official sources.

## Citation

If you use this work or related materials, please cite:

```bibtex
@article{elgohary2024proposed,
  title={A proposed video super-resolution reconstruction strategy using wavelet multi-scale convolutional neural networks},
  author={Elgohary, M. A. and El-Shafai, Walid and Abd El-Samie, F. E. and Mohamed, M. A. and Abdelhay, E. H.},
  journal={Journal of Optics},
  year={2024},
  doi={10.1007/s12596-023-01236-4}
}
```

## Author

Mohamed Elgouhary
