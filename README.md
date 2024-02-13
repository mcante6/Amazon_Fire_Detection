# Amazon Rainforest Fire Detection

## Overview
This project utilizes machine learning and satellite imagery to detect fires in the Amazon rainforest. By analyzing datasets from NASA's FIRMS, Sentinel Hub, and Google Earth Engine, we aim to develop a predictive model that can identify fire-affected areas accurately and promptly, contributing to the efforts of environmental conservation and monitoring.

## Objective
The primary goal is to create an automated system capable of detecting fires in near-real-time within the Amazon rainforest. This system seeks to aid in the rapid response to these fires, potentially saving vast areas of the rainforest and preserving its biodiversity.

## Data Sources
- **NASA's FIRMS**: Provides near-real-time active fire data from MODIS and VIIRS instruments on board Terra, Aqua, and Suomi NPP satellites.
- **Sentinel Hub**: Part of the Copernicus program, offering high-resolution optical imagery suitable for monitoring vegetation and identifying burn scars.
- **Google Earth Engine**: A platform for analyzing petabytes of satellite imagery and geospatial datasets with planetary-scale analysis capabilities.

## Installation

### Prerequisites
Ensure you have Python 3.x installed, along with Jupyter Notebooks or JupyterLab to run the analysis notebooks.

### Clone the Repository
To get started with the project, clone this repository to your local machine:
```bash
git clone https://github.com/mcante6/Amazon_Fire_Detection.git
cd Amazon_Fire_Detection
```
## Usage
The project is structured as a Jupyter notebook which guides you through the data collection, preprocessing, model training, and evaluation steps.
```
jupyter notebook fire_detection_notebook.ipynb
```
## Model Development
We employ Convolutional Neural Networks (CNNs) to process and analyze satellite images for signs of fires. The model is trained on preprocessed images, using labels generated from FIRMS data for supervised learning.

## Training
Training details, including model architecture, loss function, and optimizer, are documented in the Jupyter notebook. The model is trained using a split of the dataset into training and validation sets to ensure generalizability.

## Evaluation
Model performance is evaluated using metrics such as accuracy, precision, recall, and F1 score on a separate test set.

## Results
Preliminary results show promising potential in using satellite imagery and machine learning for early fire detection in the Amazon rainforest. Further experiments and optimizations are ongoing to improve model accuracy and reliability.

## Contributing
Contributions to this project are welcome! Please refer to CONTRIBUTING.md for guidelines on how to make contributions.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
NASA's FIRMS for fire data.
Sentinel Hub for satellite imagery.
Google Earth Engine for data analysis tools.
Contributors who have invested their time in helping this project.
