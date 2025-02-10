# EEG, PSG & Sleep Studies

## Purpose

This File describes electrophysiological data collected for sleep and circadian research. It includes details on EEG and PSG recordings, preprocessing steps, and metadata standards. Proper documentation ensures consistency across studies and enhances data reuse.

## Sections to Include

### Equipment & Settings
- **EEG/PSG Device Model:** Specify manufacturer and model (e.g., BrainVision ActiChamp, Natus Embla).
- **Channel Configuration:** Document the number and placement of electrodes (e.g., 10-20 system, frontal-central montages).
- **Sampling Rate:** List the recording frequency (e.g., 256 Hz, 512 Hz).
- **Reference Electrode:** Describe the referencing method (e.g., linked mastoids, Cz reference).

## Data Collection Protocol

- **Sleep Staging Criteria:** Guidelines followed (e.g., AASM, R&K).
- **Artifact Removal Methods:** Procedures for handling noise (e.g., Independent Component Analysis for eye blinks, high-pass filtering at 0.3 Hz).
- **Scoring Process:** Who performed the manual scoring and their qualifications.

## File Formats & Standards

- **BIDS Compatibility:** Whether the data follows the Brain Imaging Data Structure (BIDS) format.
- **File Types:** EEG (EDF, CSV), PSG (EDF, annotations).

## Data Preprocessing

- **Noise Filtering:** Specify methods (e.g., bandpass filtering 0.3–35 Hz).
- **Feature Extraction:** Describe extracted parameters (e.g., spectral power, sleep spindle detection).

## Metadata

- **Sleep Scoring Criteria:** Labeling of sleep stages (NREM, REM, wake) with timestamps.
- **Technician Notes:** Documenting any deviations from protocol, participant compliance.
