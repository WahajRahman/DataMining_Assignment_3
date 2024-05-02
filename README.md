# DataMining_Assignment_3
Autoencoder-Based Anomaly Detection Report
1. Introduction
In this project, we implemented an autoencoder-based anomaly detection model using PyTorch. The goal is to detect anomalies in time-series data using a transformer-based autoencoder architecture.

2. Data Preprocessing
Loaded the dataset from CSV files (train.csv, test.csv, test_label.csv).
Preprocessed the data by standardizing the features using StandardScaler.
Handled missing values in the training data by replacing them with the mean of their respective columns.
3. Model Architecture
Implemented a simple autoencoder architecture using fully connected linear layers.
The encoder compresses the input data into a lower-dimensional latent space representation, while the decoder reconstructs the original input from this representation.
4. Training
Trained the autoencoder model using the training data.
Used a custom contrastive loss function to compute the reconstruction loss.
Applied data augmentation using geometric masking to introduce variability in the training data.
5. Evaluation
Evaluated the trained model on the test data to detect anomalies.
Calculated accuracy, precision, recall, and F1-score to assess the model's performance.
6. Results
The model achieved an accuracy of X%, precision of Y%, recall of Z%, and F1-score of W% on the test data.
Detected anomalies in the test data using the defined threshold.
7. Conclusion
The autoencoder-based anomaly detection model shows promise in identifying anomalies in time-series data.
Further optimization and fine-tuning of the model architecture and hyperparameters could potentially improve performance.
