# WaveletHurstAnalysis
Analysis of wavelet spectra and Hurst exponents from SYM-H index data.
# Wavelet and Hurst Exponent Analysis

This project analyzes SYM-H index data to compute wavelet spectra and estimate Hurst exponents.

## Overview

- **Data Source**: SYM-H index data for the year 2015.
- **Methodology**:
  - Compute wavelet power spectra using the Morlet wavelet.
  - Estimate Hurst exponents from the spectra.
  - Filter results based on correlation coefficient thresholds.

## Usage

1. Ensure you have the SYM-H data file (`KyotoSymhYear2015.dat`) in the project directory.
2. Run the script:
   ```bash
   python WaveletHurstExponent.py
