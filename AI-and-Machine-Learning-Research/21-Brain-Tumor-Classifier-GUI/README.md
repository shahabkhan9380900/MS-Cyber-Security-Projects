# Brain Tumor Classifier GUI

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

## Accuracy

This notebook is a **GUI/interface notebook** and does not contain its own executed evaluation results. Accuracy therefore is **not reported here** rather than being inferred from another notebook.

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
