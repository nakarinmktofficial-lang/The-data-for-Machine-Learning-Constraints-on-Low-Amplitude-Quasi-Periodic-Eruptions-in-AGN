# Machine Learning Constraints on Low-Amplitude Quasi-Periodic Eruptions in AGN

This repository contains the Python code, Jupyter Notebooks, and observational data used in the paper: "Machine Learning Constraints on Low-Amplitude Quasi-Periodic Eruptions in AGN" (Under revision in *The Astronomical Journal*).

## Authors

* Nakarin Mankatwit
* Poemwai Chainakun (Corresponding Author)
* Wasutep Luangtip

## Repository Contents

### Jupyter Notebooks
* `Pipeline 1.ipynb`: Executes the complete Pipeline 1 workflow, including synthetic QPE light curve generation, Random Forest model training, and SHAP feature importance calculations.
* `Pipeline 2.ipynb`: Executes the complete Pipeline 2 workflow, including synthetic QPE light curve generation, ะhe construction of the CNN model, and the comprehensive training process.
* `Model deployment.ipynb`: Deploys the machine learning models trained in `Pipeline 1.ipynb` and `Pipeline 2.ipynb`, demonstrating their application on actual observational datasets.

### Trained model files
* `RF.pkl`: Contains the trained Random Forest classifier exported from `Pipeline 1.ipynb` for QPE detection.
* `CNN.pkl`: Contains the trained Convolutional Neural Network regressor exported from `Pipeline 2.ipynb` for peak time prediction.


