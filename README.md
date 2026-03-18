# SPECTRA Skin-Pathology Evaluation via Convolutional Training and Recognition Algorithms
SPECTRA (Skin Pathology Evaluation via Convolutional Training and Recognition Algorithms) is a deep learning framework for automated skin lesion analysis. It leverages CNNs to classify malignant vs. benign lesions, aiming to improve early melanoma detection and reduce disparities in access to dermatologic care.

## Dataset

This project is based on datasets from the ISIC (International Skin Imaging Collaboration) Archive.

Primary dataset:
- https://challenge2020.isic-archive.com/

Official archive:
- https://www.isic-archive.com/

DOI reference:
- https://doi.org/10.34970/2020-ds01

Note: The Kaggle dataset used in this project is derived from these ISIC sources.


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


