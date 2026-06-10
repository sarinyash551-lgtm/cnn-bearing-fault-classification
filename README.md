# CNN-Based Fault Classification Using Spectrograms on the CWRU Bearing Dataset

## Overview

This project implements a Convolutional Neural Network (CNN) for bearing fault classification using spectrogram representations of vibration signals from the Case Western Reserve University (CWRU) Bearing Dataset.

The objective is to automatically identify bearing conditions such as normal operation, inner-race faults, and outer-race faults by transforming vibration signals into spectrogram images and applying deep learning techniques for classification.

## Dataset

The project uses the Case Western Reserve University (CWRU) Bearing Dataset, a widely used benchmark dataset for machine condition monitoring and fault diagnosis.

Classes used:

* Normal Bearing Condition
* Inner Race Fault
* Outer Race Fault

## Methodology

1. Load vibration signal data from the CWRU dataset.
2. Convert signals into spectrogram representations.
3. Preprocess and organize images by fault category.
4. Train a Convolutional Neural Network (CNN).
5. Evaluate classification performance using test data.
6. Visualize results and model performance.

## Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Matplotlib
* Scikit-learn
* Signal Processing
* Deep Learning

## Project Structure

```text
cnn-bearing-fault-classification/
│
├── Yash_sarin-202480201.ipynb
├── Results_images/
├── report.pdf
├── requirements.txt
└── README.md
```

## Results

The trained CNN successfully classifies bearing conditions using spectrogram images derived from vibration signals.

Result visualizations and performance metrics are available in the `Results_images` folder.

## Future Improvements

* Multi-fault classification
* Real-time fault monitoring
* Transfer learning approaches
* Deployment for predictive maintenance systems

## Author

Yash Sarin

Department of Artificial Intelligence

Woosong University
