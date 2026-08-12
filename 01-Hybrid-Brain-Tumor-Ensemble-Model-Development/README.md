# Hybrid Brain Tumor Ensemble Model Development

**MS Thesis Research Project — Brain MRI Classification**

This project contains the cleaned experimental notebook used to develop a binary Brain Tumor vs Healthy MRI classification system. The final saved-model pipeline combines deep features and handcrafted image features with classical machine-learning classifiers and weighted soft voting.

## Final Saved-Model Pipeline

- CNN classifier and CNN feature extractor
- Wavelet features
- HOG features
- Hybrid feature vector: Wavelet + HOG + CNN
- PCA dimensionality reduction
- Standard scaling
- Random Forest
- Support Vector Machine
- K-Nearest Neighbors
- Logistic Regression
- Accuracy-weighted soft-voting ensemble

## Reported Validation Results

The following results correspond to the models that were saved for the final identification application.

| Model | Validation Accuracy |
|---|---:|
| CNN | 94.78% |
| Random Forest | 95.98% |
| SVM | 93.15% |
| KNN | 97.07% |
| Logistic Regression | 92.07% |
| **Weighted Ensemble** | **97.50%** |

**Ensemble confusion matrix:** `[[402, 15], [8, 495]]` on 920 validation images.

## Separate Unseen Test Results

The final saved pipeline was also evaluated on a balanced set of **600 unseen MRI images** (300 Healthy, 300 Tumor).

| Model | Unseen Accuracy |
|---|---:|
| CNN | 91.67% |
| Random Forest | 90.67% |
| SVM | 90.83% |
| KNN | 89.67% |
| Logistic Regression | 88.83% |
| **Weighted Ensemble** | **97.17%** |

**Unseen ensemble confusion matrix:** `[[296, 4], [13, 287]]`.

## Dataset Size

The supplied thesis archive contained 4,600 main MRI images and 600 separate unseen test images. Raw datasets are not redistributed in this public GitHub-ready version; see `data/README.md`.

## Notes

The original notebook also contains exploratory comparisons involving alternative feature sets and architectures. Those results should be interpreted as experiments, while the tables above represent the saved hybrid pipeline used by the final application.

## Academic Context

**Student:** Shahab Khan  
**Program:** MS Cyber Security  
**Project type:** MS thesis / research implementation

This repository is for research, education, and portfolio presentation and is not a clinical diagnostic tool.
