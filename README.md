# PYCAD Model Zoo

Welcome to the **PYCAD Model Zoo**! This repository is dedicated to hosting various nnUNet models trained on different medical imaging datasets. Our goal is to provide the community with openly accessible model checkpoints and datasets to facilitate research, development, and experimentation in the field of medical imaging.

## Project Overview

The PYCAD Model Zoo is an ongoing initiative to make pre-trained nnUNet models and datasets publicly available. Each model in this repository is carefully trained and validated on high-quality datasets to support a wide range of medical imaging applications.

## Available Models

| Model Name                | Number of Cases | Validation Dice | Model Weights | Kaggle Dataset | Additional Resources |
|---------------------------|-----------------|-----------------|----------------|-----------------|----------------------|
| Vertebrae Segmentation    | 1089 CT Scans    | 0.88            | [![Model Weights](https://img.shields.io/badge/Model_Weights-Download-brightgreen)](https://github.com/pycadd/pycad-model-zoo/releases/download/v0.0.1/spine.zip) | [![Kaggle](https://img.shields.io/badge/Dataset-Kaggle-blue)](https://www.kaggle.com/datasets/pycadmk/spine-segmentation-from-ct-scans) | [![YouTube Video](https://img.shields.io/badge/YouTube-Video-red)](https://youtu.be/rZfngRIhEcQ?si=Z0V5ATb3E9tlq104) |
| Skull Segmentation        | 349 CT Scans     | 0.92            | [![Model Weights](https://img.shields.io/badge/Model_Weights-Download-brightgreen)](https://github.com/pycadd/pycad-model-zoo/releases/download/v0.0.2/skull.zip) | [![Kaggle](https://img.shields.io/badge/Dataset-Kaggle-blue)](https://www.kaggle.com/datasets/pycadmk/skull-segmentation-in-ct-scans) | None |
| cardiac segmentation, specifically the left ventricle, right ventricle, and myocardium  | 300 MRI Scans     | 0.96            | [![Model Weights](https://img.shields.io/badge/Model_Weights-Download-brightgreen)](https://github.com/pycadd/pycad-model-zoo/releases/download/v0.0.3/heart.zip) | [![Kaggle](https://img.shields.io/badge/Dataset-Kaggle-blue)](https://www.kaggle.com/datasets/pycadmk/cardiac-segmentation-in-mri) | None |
## How to Use

1. **Download the Model Weights**: You can download the pre-trained model weights from the table above. These weights can be directly used for inference in nnUNet-based workflows.

2. **Dataset Access**: The dataset used for training each model is available via the Kaggle link in the table above. You are encouraged to download and use these datasets to train your own models.

3. **Use in 3D Slicer**: We also provide a step-by-step guide on using these model weights in the nnUNet extension within 3D Slicer. To do so, follow the steps in [this video](https://youtu.be/Mq0R-DNXdXc?si=EPc_1G47YWq9MIPl).

## Contributions and Future Updates

This project is a work in progress, and we plan to add more models periodically. If you would like to contribute by training additional models or suggesting new datasets, feel free to open an issue.

## License

All datasets and model weights are provided under an open-source license. Check the `LICENSE` file for more details.

## Acknowledgments

We thank everyone who contributed to building these datasets and refining the models. Special thanks to the open-source community for providing resources and tools that make these projects possible.
