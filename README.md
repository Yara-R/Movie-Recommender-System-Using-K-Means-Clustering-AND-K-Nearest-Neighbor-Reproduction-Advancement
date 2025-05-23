# Movie Recommender System Using K-Means Clustering and K-Nearest Neighbor: Reproduction & Extension

<p align="center">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/Yara-R/Movie-Recommender-System-Using-K-Means-Clustering-AND-K-Nearest-Neighbor-Reproduction-Advancement">

  <a href="https://github.com/Yara-R/Movie-Recommender-System-Using-K-Means-Clustering-AND-K-Nearest-Neighbor-Reproduction-Advancement/commits/main/">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/Yara-R/Movie-Recommender-System-Using-K-Means-Clustering-AND-K-Nearest-Neighbor-Reproduction-Advancement">
  </a>

  <img alt="License" src="https://img.shields.io/badge/license-MIT-brightgreen">

</p>

# Movie Recommender System Using K-Means Clustering and K-Nearest Neighbor

This repository contains the implementation, reproduction, and extension of the article _"Movie Recommender System Using K-Means Clustering and K-Nearest Neighbor"_, developed as part of the final project for the Machine Learning course at CESAR School.

## 📚 Course Information

- **Institution**: CESAR School
- **Course**: Aprendizado de Máquina - 2025.1.

## 📄 Original Article

- Ahuja, M., Yadav, D., & Rajput, V. (2019). [Movie Recommender System Using K-Means Clustering and K-Nearest Neighbor](https://ieeexplore.ieee.org/abstract/document/8776969/references#references). *2019 3rd International Conference on Trends in Electronics and Informatics (ICOEI)*.

## 📊 Dataset

- [MovieLens 100k Dataset (Kaggle)](https://www.kaggle.com/datasets/prajitdatta/movielens-100k-dataset/data)

## ✅ Project Overview

This project is divided into two main stages:

### 1. 🔁 Reproduction of the Original Model
We faithfully reproduced the methodology proposed by Ahuja et al. (2019), which combines:
- **K-Means clustering** based on movie genres;
- **Collaborative filtering** using **Pearson correlation** for user similarity;
- **K-Nearest Neighbors (KNN)** for rating prediction.

We validated the implementation using the MovieLens 100k dataset and calculated the RMSE over a test set:
- 📌 **RMSE (Reproduced model):** 1.180  
- 📌 **RMSE reported in article:** 1.081  

### 2. 🚀 Extension with Supervised Learning
We extended the original pipeline by replacing the KNN-based predictor with supervised regression models:
- **TruncatedSVD + Linear Regression**
- **Multi-Layer Perceptron (MLP)**
- **XGBoost Regressor**

Each model was trained using engineered features derived from:
- Cluster-based user ratings;
- User-user similarity vectors.

🔎 **RMSE Comparison of Models:**
| Model                         | RMSE    |
|------------------------------|---------|
| Original (Article)           | 1.0816  |
| Reproduced (This work)       | 1.1801  |
| Improved KNN Reproduction    | 1.0923  |
| SVD + Linear Regression      | 1.0453  |
| MLP Regressor                | 1.0461  |
| XGBoost                      | 1.0418  |


## 📄 License

This project is licensed under the MIT License.

## 👥 Colaboradores

| [<img src="https://avatars.githubusercontent.com/u/116604134?v=4" width=115><br><sub>Diego Costa Arruda</sub>](https://github.com/Arrudadiego) | [<img src="https://avatars.githubusercontent.com/u/116359369?v=4" width=115><br><sub>Flávio Muniz</sub>](https://github.com/flavio-muniz) | [<img src="https://avatars.githubusercontent.com/u/00000003?v=4" width=115><br><sub>Henrique Roma</sub>](https://github.com/henriqueroma) |
| :---: | :---: | :---: |
| [<img src="https://avatars.githubusercontent.com/u/105346791?v=4" width=115><br><sub>João Lafetá</sub>](https://github.com/joaohlafeta) | [<img src="https://avatars.githubusercontent.com/u/83378430?v=4" width=115><br><sub>Rodrigo Dubeux</sub>](https://github.com/Cenafowzin) | [<img src="https://avatars.githubusercontent.com/u/103130662?v=4" width=115><br><sub>Yara Rodrigues</sub>](https://github.com/Yara-R) |
