# Brain Tumor Unseen Ensemble 97 78

**MS/Research Portfolio Experiment — Brain Tumor MRI Classification**

This project contains a cleaned Jupyter notebook from an iterative brain-tumor MRI classification workflow. The task is binary classification of **Brain Tumor** versus **Healthy** MRI images using CNN and/or classical machine-learning models.

## Models / Techniques

- Convolutional Neural Network (CNN)
- Random Forest (RF)
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Logistic Regression (LR)
- Ensemble voting where implemented
- HOG/PCA/data augmentation where present in the original notebook

## Reported Test / Validation Accuracy

| Model | Accuracy |
|---|---:|
| CNN | 95.62% |
| RF | 96.12% |
| SVM | 97.50% |
| KNN | 97.38% |
| LR | 96.75% |
| Ensemble | 97.88% |

**Best reported test/validation result:** Ensemble — **97.88%**.

## Separate Unseen-Image Evaluation

| Model | Accuracy |
|---|---:|
| CNN | 94.44% |
| RF | 92.22% |
| SVM | 91.11% |
| KNN | 92.22% |
| LR | 90.00% |
| Ensemble | 97.78% |

**Unseen-image ensemble accuracy:** **97.78%**.

## Dataset

The dataset itself is **not included** in this repository. Update the local dataset paths in the notebook before running it.

## Running

```bash
pip install -r requirements.txt
jupyter notebook
```

Open the notebook in the `notebook/` folder and update dataset paths as needed.

## Notes on Results

The percentages above are transcribed from the executed outputs stored in the submitted notebook. Training accuracy is not presented as final model performance. Where a separate unseen-image evaluation exists, it is shown separately from the held-out test/validation result.

## Academic Context

**Student:** Shahab Khan  
**Program:** MS Cyber Security / research portfolio  

This repository is shared for educational and portfolio purposes.
