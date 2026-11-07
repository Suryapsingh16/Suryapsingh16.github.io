---
layout: default
title: Publications & Projects
---

[Home](./index.html) · [Research & Professional Interests](./interests.html)

# Publications & Projects

My research work has focused on applying signal processing and machine learning techniques to wireless communication problems, including carrier frequency offset estimation, automatic modulation classification, RF fingerprinting, and multimodal beam prediction.

## Publications

### 1. Hybrid Attention & SE-Net for CFO Estimation in MIMO-OFDM Backscatter Systems

**S. Singh, S. P. Singh, U. Satija, and S. Majhi**

*IEEE Communications Letters*

- Developed a hybrid deep learning architecture for carrier frequency offset (CFO) estimation in MIMO-OFDM ambient backscatter systems.
- Designed a dual-input architecture using magnitude and phase representations, with hierarchical feature extraction.
- Incorporated multi-head cross-attention to learn inter-feature dependencies and squeeze-and-excitation mechanisms for channel-wise feature recalibration.
- Evaluated the approach across modulation schemes from 16QAM to 2048QAM and 3GPP TDL channel models.
- Demonstrated accurate CFO estimation under multipath and Doppler effects while maintaining low model complexity (approximately 1.11 million parameters).

[Read Paper](#)

### 2. Automatic Modulation Classification in OTFS System

**S. P. Singh, M. Singh, and U. Satija**

*IEEE Wireless Communications Letters*

- Developed a self-operational neural network (SONN)-based automatic modulation classification framework for OTFS signals.
- Used dual-stream SONN stacks to extract hierarchical features from IQ samples and frequency-domain (FFT) representations.
- Investigated classification across nine modulation schemes: BPSK, QPSK, MSK, QAM, OOK, PAM, 4ASK, 8ASK, and 16ASK.
- Evaluated the framework in high-mobility delay-Doppler environments.
- Achieved over 91% classification accuracy at 15 dB SNR with approximately 483K parameters.

[Read Paper](#)

### 3. High-Mobility Emitter Identification Framework using RF Fingerprints in OTFS

**M. Singh, S. P. Singh, and U. Satija**

*IEEE Communications Letters*

- Developed a CNN-based emitter identification framework using IQ samples of OTFS-modulated signals.
- Designed a multi-layer CNN to learn discriminative RF fingerprints associated with transmitter-specific hardware impairments.
- Modeled high-mobility OTFS channels with transmitter nonlinearities using a Taylor polynomial-based system.
- Evaluated identification performance across different SNR conditions, from -5 dB to 15 dB, and multiple emitter configurations.
- Demonstrated improved classification performance and computational efficiency compared with conventional feature-based and transfer-learning approaches.

[Read Paper](#)

### 4. Operational Neural Network Based LoRa Device RF Fingerprint Identification

**S. P. Singh, A. Roy, and U. Satija**

*IEEE Wireless Communications and Networking Conference (WCNC), 2024*

- Developed LoRaSONN, a self-operational neural network framework for RF fingerprint-based identification of LoRa devices.
- Used spectrogram-based time-frequency representations of IQ signals to capture device-specific characteristics.
- Designed a nonlinear SONN architecture to improve generalization in large-scale device classification.
- Achieved 97% classification accuracy across 60 LoRa devices on the LoRa RF fingerprint identification dataset.
- Maintained low computational complexity with approximately 2.37 million parameters.

[Read Paper](#)

---

## Research Projects

### Vision-Position Based Beam Prediction Using Multimodal Sensor Data

**Research Intern — Wireless Communication Lab, UNSW Sydney**

*May 2024 – September 2024*

- Developed a multimodal sensor fusion framework combining image, GPS, and radar data for Vehicle-to-Infrastructure (V2I) beam prediction.
- Applied deep learning algorithms to identify the optimal three beams from a candidate set of 256 beams.
- Explored the use of contextual sensor information to reduce the need for exhaustive beam sweeping.

### MIMO-Based Physical Layer Modem Design for Satellite Communications

**R&D Engineer Trainee — QBit Labs Private Limited**

*June 2025 – Present*

- Working on MIMO-based physical-layer modem design for satellite communications.
- Developing MATLAB-based signal processing simulations involving OFDM, channel estimation, and synchronization.
- Implemented dynamic channel tracking mechanisms for time-varying multipath fading environments to improve demodulation accuracy and link reliability.
- Modeled fixed-point data generation to study quantization noise and tune bit-widths while balancing hardware resource requirements and bit error rate performance.
- Working toward collaboration on RTL implementation and real-time hardware deployment.
