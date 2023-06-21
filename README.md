# Faulty-Products-Anomaly-Detection-using-Patchcore
This repository provides an implementation of image anomaly detection using `PatchCore` and `Anomalib`, along with the `MVTec-AD dataset`. The combination of PatchCore and Anomalib allows for efficient and accurate anomaly detection in images.

![image](https://github.com/Basel-anaya/Faulty-Products-Anomaly-Detection-using-Patchcore/assets/81964452/cd40118c-3b65-4230-8bda-272ba7c9f701)

* `original image`
* `ground-truth segmentation mask` (not used during training since unsupervised)
* `predicted anomaly map`
* `predicted segmentation mask` (thresholded anomaly map)

## Introduction
`Image anomaly detection` is the task of identifying anomalous regions or objects in images. `PatchCore` is a powerful deep learning framework for patch-based anomaly detection. Anomalib is a Python library that provides various tools and utilities for anomaly detection tasks. This project combines the strengths of PatchCore and Anomalib to achieve robust image anomaly detection.

![image](https://github.com/Basel-anaya/Faulty-Products-Anomaly-Detection-using-Patchcore/assets/81964452/3da099f7-d19d-4e33-9ecb-487472389e5e)

## Installation
To get started, follow these steps to install the necessary dependencies:

1- Clone this repository to your local machine.
2- Navigate to the project directory.

3- Create a new Python virtual environment:
```bash
python3 -m venv env
```
4- Activate the virtual environment:
```bash
source env/bin/activate
```
5- Install the required packages:
```bash
pip install -r requirements.txt
```

## Usage
Follow these steps to use PatchCore and Anomalib for image anomaly detection:

1. Preprocess the `MVTec-AD` dataset:
2. Download the `MVTec-AD` dataset from [here](https://www.mvtec.com/company/research/datasets/mvtec-ad/).
3. Preprocess the dataset using the provided scripts.
4. Open the `image_anomaly_detection.ipynb` notebook in Jupyter or any other compatible environment.
5. Run the notebook cells to execute the code step-by-step.
6. Feel free to explore the codebase and modify it according to your specific requirements.

## Dataset
This project uses the MVTec-AD dataset for image anomaly detection. The MVTec-AD dataset contains various object categories with both normal and anomalous images. It is widely used in the computer vision community for benchmarking anomaly detection algorithms.

* You can download the MVTec-AD dataset from [here](https://www.mvtec.com/company/research/datasets/mvtec-ad/) and follow the preprocessing steps mentioned in the Usage section.

## Results
The results of the image anomaly detection using PatchCore and Anomalib on the MVTec-AD dataset can be found in the notebook. The evaluation metrics, such as `accuracy`, `ROC` and `F1-score`, are provided for assessing the performance of the model.

![image](https://github.com/Basel-anaya/Faulty-Products-Anomaly-Detection-using-Patchcore/assets/81964452/7a09a08f-874a-4048-9712-0e9b8c4b8257)

## Contributing
Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License
This project is licensed under the [Apache 2.0 License](LICENSE).
