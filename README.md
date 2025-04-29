# Heart-Rate-Variability-Analysis
This project focuses on Heart Rate Variability (HRV) analysis using an AD8232 ECG module and Arduino Uno for ECG signal acquisition. The raw ECG data is transmitted to a computer for further processing and HRV computation using Python.
This project aims to analyze Heart Rate Variability (HRV) by acquiring ECG signals using an AD8232 module connected to an Arduino Uno. The ECG data is processed in Python to extract R-peaks and compute HRV metrics, offering insights into autonomic nervous system activity.
KEY FEATURES:

✅ ECG Signal Acquisition:

Real-time data collection from the AD8232 ECG module via Arduino.

Serial communication for seamless data transfer.

✅ Preprocessing & Filtering:

Bandpass Filtering (0.5–35 Hz) to remove noise.

Moving Average Smoothing for better peak detection.

Signal Centering to normalize baseline drift.

✅ R-Peak Detection & HRV Analysis:

Identifies R-peaks for heartbeat extraction.

Computes RR Intervals (time between successive R-peaks).

Time-Domain HRV Metrics (e.g., SDNN, RMSSD, pNN50).

Frequency-Domain HRV Analysis using FFT-based PSD estimation.

✅ Nonlinear HRV Analysis:

Poincaré Plot visualization with SD1 and SD2 metrics.

✅ Data Visualization:

ECG signal plots at various processing stages.

RR interval trends and histograms.

Frequency spectrum highlighting VLF, LF, and HF bands.

Poincaré plot for nonlinear HRV insights.

HARDWARE AND SOFTWARE REQUIREMENTS

Hardware- AD8232 ECG Module, Arduino UNO, Laptop
Software- Python (NumPy, SciPy, Matplotlib, Pandas, Welch PSD), Arduino IDE (for data acquisition)

 APPLICATIONS
 Biomedical Signal Processing Research
 HRV-Based Stress & Wellness Monitoring
 Autonomic Nervous System Analysis
 Wearable ECG & Remote Health Monitoring
