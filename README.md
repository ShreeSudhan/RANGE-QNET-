# RANGE-QNET: Neural Network and Reinforcement Learning Framework for FMCW Radar Range Prediction

## Project Overview

This repository contains the source code, implementation details, and dataset references for the PeerJ Computer Science paper entitled **"RANGE-QNET: Neural Network and Reinforcement Learning Framework for FMCW Radar Range Prediction."**

The proposed framework integrates conventional FMCW radar signal processing, Neural Networks (NN), and Q-learning (QL) to improve radar range prediction under noise and interference conditions. The repository provides the implementation used for the experimental evaluation presented in the paper together with links to the publicly available datasets employed in this study.

---

## Dataset Information

The proposed framework was evaluated using publicly available FMCW and mmWave radar datasets. The datasets are **not distributed** with this repository due to licensing restrictions. Users are requested to obtain the datasets from their original sources using the links provided below.

### 1. Learning to Detect Open Carry and Concealed Object with 77 GHz Radar

**Dataset Link**

https://ieee-dataport.org/documents/raw-adc-data-2d-mimo-mmwave-radar-carry-object-detection

**Reference**

X. Gao, H. Liu, S. Roy, G. Xing, A. Alansari, and Y. Luo, *Learning to Detect Open Carry and Concealed Object with 77 GHz Radar*, IEEE Journal of Selected Topics in Signal Processing, vol. 16, no. 4, pp. 791–803, 2022.

**DOI:** https://doi.org/10.1109/JSTSP.2022.3157670

---

### 2. RAMP-CNN: A Novel Neural Network for Enhanced Automotive Radar Object Recognition

**Dataset Link**

https://ieee-dataport.org/documents/raw-adc-data-77ghz-mmwave-radar-automotive-object-detection

**Reference**

X. Gao, G. Xing, S. Roy, and H. Liu, *RAMP-CNN: A Novel Neural Network for Enhanced Automotive Radar Object Recognition*, IEEE Sensors Journal, vol. 21, no. 4, pp. 5119–5131, 2021.

**DOI:** https://doi.org/10.1109/JSEN.2020.3034080

---

### 3. An MTI-Like Approach for Interference Mitigation in FMCW Radar Systems

**Dataset Link**

https://ieee-dataport.org/documents/raw-adc-data-fmcw-radar-77-ghz-interference

**Reference**

L. A. López-Valcárcel, M. García Sánchez, F. Fioranelli, and O. A. Krasnov, *An MTI-Like Approach for Interference Mitigation in FMCW Radar Systems*, IEEE Transactions on Aerospace and Electronic Systems, vol. 60, no. 2, pp. 1985–2000, 2024.

**DOI:** https://doi.org/10.1109/TAES.2023.3345263

---

### 4. Fully Convolutional Neural Networks for Automotive Radar Interference Mitigation

**Dataset Link**

https://github.com/ristea/arim

**Reference**

N. C. Ristea, A. Anghel, and R. T. Ionescu, *Fully Convolutional Neural Networks for Automotive Radar Interference Mitigation*, Proceedings of the IEEE 92nd Vehicular Technology Conference (VTC2020-Fall), 2020.

**DOI:** https://doi.org/10.1109/VTC2020-Fall49728.2020.9348610

---

## Code Information

The repository includes implementations for:

- FMCW radar signal generation and preprocessing
- Range FFT and Doppler FFT processing
- Range–Doppler map generation
- Feature extraction and normalization
- Neural Network-based radar range prediction
- Q-learning-based adaptive decision learning
- Performance evaluation and visualization

---

## Usage Instructions

1. Install Python 3.x.
2. Install the required Python packages listed below.
3. Download the public datasets from the links provided above.
4. Update the dataset paths in the source code.
5. Execute the Python scripts to reproduce the experimental results reported in the paper.

---

## Requirements

The implementation was developed and tested using **Python 3.x**.

Required Python packages:

- NumPy
- Pandas
- SciPy
- Matplotlib
- TensorFlow
- Scikit-learn
- h5py
- tqdm

The implementation includes an automatic dependency check that installs any missing packages before execution.

---

## Reproducibility

The datasets are publicly available and can be downloaded using the links provided above. All experiments reported in the paper can be reproduced using the source code included in this repository after configuring the dataset paths.

---

## Citation

If you use this repository, please cite:

**Rajyashree H., Govindarajan J.**

**RANGE-QNET: Neural Network and Reinforcement Learning Framework for FMCW Radar Range Prediction.**

PeerJ Computer Science.

---

## Contact

For questions regarding the implementation, please contact the corresponding author.
