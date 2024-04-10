# Pipeline for Alpha and Beta Cell Stuctural Analysis using Soft X-ray Tomography
This repository describes analysis to use supervised machine learnine to classify vesicles from Alpha and Beta cells. Feature importances can be extracted from these machine learning models and then visualized using UMAP (Uniform Manifold Approximation and Projection). UMAP is also used on whole alpha and beta cells to visualize clusters of cell types. 

Contact email: kchang42@usc.edu

Laboratory: Kate White Lab at USC (https://www.katewhitelab.com/)

# Code Breakdown

- 3D Vesicle Metrics: Creating UMAP representation of vesicle data. Vesicle are colored by insulin/glucagon vesicle identity, which cell they originate from, and by vesicle feature values.
- Random Forests, XGBoost, Logistic Regression: Using these 3 models to predict whether a given group of vesicles from an alpha or beta cell is a glucagon vesicle or insulin vesicle. An application of this model is to predict the identity of an unknown cell. 
- UMAP of Primary Alpha and Beta: UMAP representation of whole cell metrics. 
