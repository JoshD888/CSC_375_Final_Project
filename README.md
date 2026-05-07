# Diabetic Retinopathy Classification with CNNs

This project explores deep learning approaches for automated diabetic retinopathy (DR) grading using retinal fundus images. Multiple convolutional neural network (CNN) architectures were trained and evaluated on both small and large retinal imaging datasets to compare performance, generalization, and interpretability.

---

## Models Used

- ResNet50
- EfficientNetB0
- Transfer Learning Model (pretrained weights + fine-tuning)

---

## Features

- Image preprocessing and augmentation
- Transfer learning and fine-tuning
- Class imbalance handling with weighted loss
- Patient-level train/validation/test splitting
- Performance evaluation using:
  - Accuracy
  - Weighted F1-score
  - Confusion matrices
- Grad-CAM visualizations for model interpretability

---

## Datasets

- Messidor-2 retinal imaging dataset
- DDR diabetic retinopathy dataset

---

## Technologies

- Python
- TensorFlow / Keras
- Scikit-learn
- NumPy / Pandas
- Matplotlib / Seaborn

---

## Key Findings

- ResNet50 achieved the strongest overall performance across datasets.
- Larger datasets did not always improve results, highlighting the importance of data quality and class balance.
- Grad-CAM visualizations showed that high-performing models focused on clinically relevant retinal regions such as lesions and hemorrhages.

---

## Future Improvements

- More extensive hyperparameter tuning
- Additional retinal imaging datasets
- Advanced interpretability methods
- Improved handling of mid-grade DR classes

---

## Authors

Zach Swartz and Josh DeMontigny
