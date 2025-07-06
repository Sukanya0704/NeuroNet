# 🧠 EEG Seizure Detection using Deep Learning

This project focuses on detecting seizures from EEG signals using deep learning models like CNN, BiLSTM, and Attention mechanisms. The current model has been trained using `.npz` files that were converted from preprocessed EEG data (Kaggle dataset). We’re now working on extending the pipeline to handle raw `.edf` files, like those in the CHB-MIT dataset.

The process includes reading EEG signals, preprocessing them (like filtering, segmentation, and normalization), feeding them into deep learning models, and classifying whether a seizure is present. The trained model currently achieves around **96% training accuracy** and **92% validation accuracy**, and outputs like confusion matrices and training graphs help visualize its performance.

Some key features:
- End-to-end deep learning pipeline for seizure detection
- Automated EEG signal analysis
- Uses `.npz` files for training (for now)
- Includes performance plots and metrics
- Built with Python, NumPy, TensorFlow/Keras, and MNE

The model is still being improved and tested on real-world `.edf` EEG data. Future plans include making the pipeline more robust, handling noisy signals, and possibly building a small interface or dashboard to test EEG segments.

Thanks for checking this out!
