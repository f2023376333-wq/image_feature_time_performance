CV Assignment 1 - README
Student: Wardah Afzaal / F2023376333

Datasets : Fashion-MNIST (Keras), CIFAR-10 (Keras), and ADDITIONAL DATASET = SVHN
Subset   : 6000 stratified images per dataset, then stratified split: 4500 train / 1500 test (25% test)
Random seed: 42 (subset sampling, train/test split, classifiers)
Preprocessing: grayscale uint8, native resolution; scaling fit on training data only (inside sklearn pipelines)

Environment:
python                                    3.13.18
platform     Linux-6.6.159+-x86_64-with-glibc2.39
processor                                  x86_64
cpu_count                                       2
numpy                                       2.4.6
pandas                                      2.2.3
opencv                                     4.10.0
sklearn                                     1.6.1
pywt                                        1.8.0
xgboost                                     3.4.1

Required libraries: numpy, pandas, matplotlib, opencv-python (SIFT needs OpenCV >= 4.4), scikit-learn, scipy,
tensorflow or keras (dataset loading), PyWavelets (required), xgboost (optional), psutil (optional).

Reproduce: install the libraries; open the notebook; Run All (internet is needed on the first run to download the datasets).
Outputs are written to ./results/ (CSV files and PNG plots). Memory is reported in MiB (2^20 bytes) of float32 feature matrices.
Timing depends on hardware and system load; all reported numbers come from this notebook execution.
