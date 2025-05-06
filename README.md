# HTTP Payload Anomaly Detection - With_Attention_(Bahdanau)

## Project Overview

This project focuses on detecting anomalies in HTTP payloads using various machine learning architectures. The **With_Attention_(Bahdanau)** module implements the **Bahdanau Attention Mechanism** to enhance the performance of sequence-based models, particularly LSTM (Long Short-Term Memory), for detecting anomalies in HTTP payload data.

The model is trained on a dataset with HTTP payloads, and the **Bahdanau Attention** mechanism helps focus on important parts of the sequence, improving the model's ability to detect outliers or anomalies.

## Features

- **Bahdanau Attention Mechanism**: Improves the focus of the model on relevant input features, enhancing anomaly detection accuracy.
- **LSTM Encoder-Decoder Architecture**: Utilizes LSTM networks to process sequential data and detect anomalies in HTTP payloads.
- **Comparison with Other Architectures**: The project compares the performance of LSTM models with and without attention, as well as other architectures like Transformer.

## Requirements

- Python 3.6+
- TensorFlow 2.0+
- NumPy
- Pandas
- Scikit-learn
- Matplotlib (for visualization)
- Other libraries specified in `requirements.txt`

## Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/HTTP-Payload-Anomaly-Detection.git
cd HTTP-Payload-Anomaly-Detection



Data
Train_data.csv: Training dataset containing labeled HTTP payload data.

Test_data.csv: Test dataset for evaluating the model's performance.

The dataset is structured to include various features representing HTTP request attributes and payload information.
