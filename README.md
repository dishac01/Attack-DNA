# Attack DNA: Global Cyber Threat Detection using Multi-Dataset Learning

## Overview

Attack DNA is a behavioral cybersecurity framework designed to detect cyber threats across heterogeneous intrusion detection datasets. Instead of relying on dataset-specific features, the framework converts network traffic into a unified behavioral representation called **Attack DNA**, enabling cross-dataset learning and scalable threat detection.

The project integrates multiple benchmark intrusion detection datasets and evaluates machine learning models to identify malicious network activity using standardized behavioral features.

## Problem Statement

Traditional Intrusion Detection Systems (IDS) often struggle with:

- Dataset-specific feature dependencies
- Poor cross-domain generalization
- Limited adaptability to evolving cyber threats
- Challenges in global threat intelligence sharing

Attack DNA addresses these issues by creating a common behavioral feature space that can be applied across multiple datasets and environments.

## Key Features

- Multi-dataset integration
- Behavioral feature standardization
- Cross-dataset intrusion detection
- Global threat analysis
- Random Forest and LSTM model evaluation
- Feature importance analysis
- Region-wise attack analysis
- Privacy-preserving behavioral abstraction

## Datasets Used

The framework integrates:

- CIC-IDS2017
- NSL-KDD
- UNSW-NB15
- TON-IoT

These datasets are transformed into a common behavioral representation to enable unified learning and evaluation. :contentReference[oaicite:0]{index=0}

## Attack DNA Features

The framework extracts and standardizes the following behavioral attributes:

| Feature | Description |
|----------|-------------|
| Duration | Connection duration |
| Packet Count | Total packets exchanged |
| Byte Count | Total bytes transmitted |
| Flow Rate | Traffic rate |
| Session Frequency | Frequency of communication sessions |
| Burstiness | Traffic fluctuation intensity |

These features collectively form the Attack DNA representation. :contentReference[oaicite:1]{index=1}

## Methodology

1. Dataset Collection
2. Feature Extraction
3. Attack DNA Representation
4. Data Preprocessing
5. Model Training
6. Evaluation & Global Analysis

### Models Evaluated

- Random Forest
- Long Short-Term Memory (LSTM)

## Results

| Model | Accuracy |
|---------|----------|
| Random Forest | 95.96% |
| LSTM | 70.19% |

The Random Forest classifier significantly outperformed the LSTM model for the proposed behavioral representation. :contentReference[oaicite:2]{index=2}

## Key Findings

- Behavioral standardization improves cross-dataset learning.
- Feature-based learning performs better than sequence-based learning for aggregated intrusion detection data.
- Packet count and byte count are among the most influential features for threat detection.
- Region-wise analysis provides insights into global cyber threat patterns. :contentReference[oaicite:3]{index=3}

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- TensorFlow / Keras
- Matplotlib
- Seaborn

## Future Scope

- Real-time intrusion detection
- SIEM integration (Splunk, Wazuh)
- Explainable AI (XAI)
- Transformer-based architectures
- SOC deployment and cloud-native environments :contentReference[oaicite:4]{index=4}

## Research Paper

**A Unified Behavioral Attack DNA Framework for Global Cyber Threat Detection Using Multi-Dataset Learning**

Authors:
- Deepta Chakravarty
- Mayukh Mondal
- Disha Chaudhury
- Dr. Lakshmi Dhevi B

## License

This project is intended for educational and research purposes.
