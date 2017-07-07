# BreastCancerCell-Classification

The dataset is the Breast Cancer Wisconsin Dataset, downloaded from UC Irvine Machine Learning Repository (https://archive.ics.uci.edu/ml/datasets/breast+cancer+wisconsin+(original)).
Our goal is to develop a classification model that predicts whether a biopsied breast cell is benign (not harmful) or malignant (cancerous), given a set of attributes (features) about cells (observations). These features were generated from image analysis of fine needle aspiration of breast masses (https://en.wikipedia.org/wiki/Fine-needle_aspiration).
- Sample ID (code number)
- Clump thickness
- Uniformity of cell size
- Uniformity of cell shape
- Marginal adhesion
- Single epithelial cell size
- Number of bare nuclei
- Bland chromatin
- Number of normal nuclei
- Mitosis
- Classes, i.e. diagnosis

In this project, I first explored the dataset using Python pandas, numpy and matplotlib before comparing various binary classifiers with Scikit-learn. Then, I searched for the most important features using feature selection or recursive feature elimination. And finally, I optimized the hyperparameters of specific models (k-nearest neighbors, random forest and support vector machine using systematic and grid searches.
