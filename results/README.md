# Evaluation Results

This folder contains the evaluation results from the comparison between **Spectral Gating** and **Wiener Filter**.

The methods are evaluated using two quantitative metrics:

- **Signal-to-Noise Ratio (SNR)** — measures the ratio between the desired signal and noise.
- **Mean Squared Error (MSE)** — measures the average squared difference between the original and processed signal.

The complete numerical results are available in:

[`Evaluasi_Denoising-2.xlsx`](./Evaluasi_Denoising-2.xlsx)

## Experimental Results

The evaluation results for the two audio samples are:

| Audio | Method | SNR (dB) | MSE |
|---|---|---:|---:|
| Audio 1 | Spectral Gating | 5.397269 | 0.001479 |
| Audio 1 | Wiener Filter | 4.113368 | 0.001987 |
| Audio 2 | Spectral Gating | 5.586927 | 0.001769 |
| Audio 2 | Wiener Filter | 5.131756 | 0.001964 |

## Result Summary

For both audio samples in this experiment:

- Spectral Gating produced a higher SNR than Wiener Filter.
- Spectral Gating produced a lower MSE than Wiener Filter.
- The evaluation table identifies **Spectral Gating** as the selected method for both audio samples based on the experimental results.

### Audio 1

Spectral Gating obtained:

- SNR: **5.397269 dB**
- MSE: **0.001479**

Wiener Filter obtained:

- SNR: **4.113368 dB**
- MSE: **0.001987**

### Audio 2

Spectral Gating obtained:

- SNR: **5.586927 dB**
- MSE: **0.001769**

Wiener Filter obtained:

- SNR: **5.131756 dB**
- MSE: **0.001964**

## Interpretation

Based on the evaluated samples, the experimental results show that Spectral Gating achieved higher SNR and lower MSE than Wiener Filter for both audio samples.

These results describe the performance observed in this experiment and should not be interpreted as a general conclusion that Spectral Gating will outperform Wiener Filter for all types of audio or noise conditions.

## Evaluation Source

The results were obtained from the experiments implemented in:

[`KODE_PSD_KEL_10.ipynb`](../notebooks/KODE_PSD_KEL_10.ipynb)
