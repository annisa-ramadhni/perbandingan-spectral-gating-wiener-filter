# Data

This folder contains documentation about the audio data used in the project **"Perbandingan Metode Spectral Gating dan Wiener Filter dalam Penghilangan Noise pada Sinyal Suara"**.

The project uses clean audio samples and noise data to evaluate and compare two denoising methods: **Spectral Gating** and **Wiener Filter**.

## Dataset Overview

The audio data used in the experiment has the following characteristics:

| Attribute | Description |
|---|---|
| Clean audio samples | 2 audio samples |
| Noise | Wind noise |
| Sampling rate | 44,100 Hz |
| Audio duration | 46 seconds |
| Noise mixing level | 0.3 |

The audio samples are standardized to the same duration and sampling rate before the denoising process.

## Data Processing

The audio data goes through the following processing pipeline:

1. Prepare the clean audio samples.
2. Add noise to the clean audio.
3. Perform preprocessing and standardization.
4. Apply Spectral Gating.
5. Apply Wiener Filter.
6. Test different parameters for both denoising methods.
7. Select parameters based on the highest SNR obtained during the experiments.
8. Evaluate the denoised audio using SNR and MSE.
9. Compare the results of Spectral Gating and Wiener Filter.

## Data Availability

Not all original source audio files are included in this repository because of file size and portfolio repository considerations.

The complete data processing and experimental procedure can be found in:

[`KODE_PSD_KEL_10.ipynb`](../notebooks/KODE_PSD_KEL_10.ipynb)

## Important Note

The repository contains selected audio outputs and documentation rather than the complete original dataset. Therefore, the repository is intended primarily to demonstrate the **data processing workflow, denoising methods, parameter testing, and evaluation results**.
