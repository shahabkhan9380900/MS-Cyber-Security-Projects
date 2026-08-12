# Brain Tumor Unseen Ensemble 98 89

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
| CNN | 95.50% |
| RF | 96.25% |
| SVM | 97.88% |
| KNN | 97.38% |
| LR | 95.50% |
| Ensemble | 98.00% |

**Best reported test/validation result:** Ensemble — **98.00%**.

## Separate Unseen-Image Evaluation

| Model | Accuracy |
|---|---:|
| CNN | 88.89% |
| RF | 94.44% |
| SVM | 94.44% |
| KNN | 92.22% |
| LR | 95.56% |
| Ensemble | 98.89% |

**Unseen-image ensemble accuracy:** **98.89%**.

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
