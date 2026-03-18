# SPECTRA Skin-Pathology Evaluation via Convolutional Training and Recognition Algorithms
SPECTRA (Skin Pathology Evaluation via Convolutional Training and Recognition Algorithms) is a deep learning framework for automated skin lesion analysis. It leverages CNNs to classify malignant vs. benign lesions, aiming to improve early melanoma detection and reduce disparities in access to dermatologic care.


Dataset Structure:
This project expects the dataset to be organized as follows:

dataset/

  train/
  
    benign/
    
      image1.jpg
      image2.jpg
      ...
    malignant/
      image1.jpg
      image2.jpg
      ...

  test/
    benign/
    malignant/

Notes:

Images must be in .jpg, .jpeg, or .png format
Folder names must match exactly: benign, malignant
The model automatically assigns:
  benign → 0
  malignant → 1
