# SPECTRA Skin-Pathology Evaluation via Convolutional Training and Recognition Algorithms
SPECTRA (Skin Pathology Evaluation via Convolutional Training and Recognition Algorithms) is a deep learning framework for automated skin lesion analysis. It leverages CNNs to classify malignant vs. benign lesions, aiming to improve early melanoma detection and reduce disparities in access to dermatologic care.

Dataset Used:
https://www.kaggle.com/datasets/fanconic/skin-cancer-malignant-vs-benign/data

Dataset Structure:
## Dataset Structure

```
dataset/
├── train/
│   ├── benign/
│   │   ├── image1.jpg
│   │   ├── image2.jpg
│   │   └── ...
│   ├── malignant/
│   │   ├── image1.jpg
│   │   ├── image2.jpg
│   │   └── ...
│
├── test/
│   ├── benign/
│   │   ├── image1.jpg
│   │   └── ...
│   ├── malignant/
│   │   ├── image1.jpg
│   │   └── ...
```

### Notes
- Folder names must be exactly: `benign` and `malignant`
- Supported image formats: `.jpg`, `.jpeg`, `.png`
- Labels are inferred automatically:
  - `benign` → 0
  - `malignant` → 1


