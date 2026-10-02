# Audio Outputs

This folder contains selected audio outputs generated during the denoising experiments.

The outputs represent different stages of the audio processing workflow, including noisy audio, Spectral Gating results, and Wiener Filter results.

## Audio Files

| File | Description |
|---|---|
| `audio_noisy1.wav` | Noisy version of Audio 1 |
| `audio_noisy2.wav` | Noisy version of Audio 2 |
| `audio_sg1.wav` | Audio 1 after Spectral Gating |
| `audio_sg2.wav` | Audio 2 after Spectral Gating |
| `audio_wiener1.wav` | Audio 1 after Wiener Filter |
| `audio_wiener2.wav` | Audio 2 after Wiener Filter |

## Audio Characteristics

The audio data used in the experiment was standardized with:

- Sampling rate: **44,100 Hz**
- Duration: **46 seconds**
- Noise mixing level: **0.3**
- Noise type: **Wind noise**

## Processing Stages

The audio outputs represent the following processing stages:

### 1. Noisy Audio

The clean audio samples are combined with the noise sample using a noise mixing level of 0.3.

The resulting files are:

- `audio_noisy1.wav`
- `audio_noisy2.wav`

### 2. Spectral Gating

Spectral Gating is applied to reduce noise in the frequency domain.

The resulting files are:

- `audio_sg1.wav`
- `audio_sg2.wav`

### 3. Wiener Filter

Wiener Filter is applied as the second denoising approach for comparison.

The resulting files are:

- `audio_wiener1.wav`
- `audio_wiener2.wav`

## Purpose

These audio outputs allow the denoising results to be inspected directly in addition to the waveform, spectrogram, SNR, and MSE analysis.

The complete processing procedure and parameter experiments are available in:

[`KODE_PSD_KEL_10.ipynb`](../notebooks/KODE_PSD_KEL_10.ipynb)
