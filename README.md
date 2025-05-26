Overview

This repository provides PyTorch implementations of the Conditional Convolutional Recurrent Neural Network (CCRNN) and ConvLSTM for multi-step plasma etching profile prediction. The models are designed to predict the temporal evolution of etching profiles under varying process conditions. The project supports end-to-end supervised training, model evaluation, and visual and quantitative comparison of prediction accuracy using metrics such as SSIM.

Data Description

DATA1: Contains sequential etch profile images and condition vectors for cross-section 1.

DATA2: Contains sequential etch profile images and condition vectors for cross-section 2.

Each dataset folder includes:


A sequence of .png images for each sample (named as xxxx_N.png).

An accompanying Excel file (.xlsx) with condition vectors for each sample.
