# Data

This folder contains documentation about the audio data used in the project.

The project uses audio samples to compare Spectral Gating and Wiener Filter for noise reduction.

## Dataset Information

- Number of clean audio samples: 2
- Noise sample: Wind noise
- Sampling rate: 44,100 Hz
- Audio duration: 46 seconds
- Noise mixing level: 0.3

## Data Processing

The audio data is processed through the following stages:

1. Prepare the clean audio samples.
2. Add noise to the clean audio.
3. Apply Spectral Gating.
4. Apply Wiener Filter.
5. Evaluate the denoised audio using SNR and MSE.

The complete preprocessing, denoising, parameter testing, and evaluation process can be found in the main notebook:

[`KODE_PSD_KEL_10.ipynb`](../notebooks/KODE_PSD_KEL_10.ipynb)

> Not all original source audio files are included in this repository because of file size and portfolio repository considerations.
