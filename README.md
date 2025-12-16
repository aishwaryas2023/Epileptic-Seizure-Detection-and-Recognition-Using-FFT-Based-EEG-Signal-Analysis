# Epileptic Seizure Detection and Recognition Using FFT-Based EEG Signal Analysis

This project aims to explore and implement suitable machine learning algorithms using **MATLAB** to detect and classify epileptic seizures from EEG data. MATLAB provides powerful tools such as the **Signal Processing Toolbox**, **Classification Learner App**, and **Deep Learning Toolbox**, making it a strong platform for EEG-based ML tasks.


## Methodology

The epileptic seizure detection system follows the pipeline shown below.

### Data Acquisition
EEG signals are obtained from publicly available datasets such as:
- CHB-MIT EEG Dataset  
- Bonn EEG Dataset  

### Preprocessing
Raw EEG signals are cleaned using:
- Band-pass filtering to retain relevant EEG frequency bands  
- Notch filtering to remove power-line noise  
- Artifact removal techniques such as ICA and wavelet-based denoising  

### Feature Extraction
Meaningful features are extracted from the preprocessed signals, including:
- Time-domain features  
- Frequency-domain features (FFT, PSD)  
- Time–frequency features (DWT, wavelet entropy, Hjorth parameters)  

### Visualization
EEG signals, spectrograms, and seizure detection results are visualized using MATLAB plots.

EEG Data Acquisition
↓
Preprocessing
(Band-pass & Notch Filtering, Denoising)
↓
Signal Segmentation
↓
Feature Extraction
(Time, Frequency, Time–Frequency)
↓
Feature Selection
↓
Performance Evaluation

## Implementation Details

The project is implemented in MATLAB using EEG signal processing techniques.

### Steps Implemented
1. EEG data loading from CSV format  
2. FFT-based band-pass filtering (0.5–40 Hz)  
3. Signal segmentation (per sample)  
4. Frequency-domain feature extraction:
   - Mean frequency  
   - Peak frequency  
   - Band power  
5. Rule-based seizure detection using spectral thresholds  
6. Visualization of EEG signals and FFT spectra  
7. Export of extracted features to CSV file  


## Software Tools

### MATLAB
- Signal denoising and filtering  
- Time, frequency, and time–frequency analysis  
- EEG signal and spectrogram plotting  
- Machine learning model training and evaluation  


## Filters Used

- **Band-pass filter**: Retains clinically relevant EEG frequency bands  
- **Notch filter**: Removes power-line interference (50/60 Hz)  


## Dataset

The dataset used in this project is publicly available.  
Due to size and licensing constraints, the dataset is not included in this repository.


## Contributors

- Aishwarya S 
- Harini S
- Swetha CA 

---

## License

This project is licensed under the MIT License.
