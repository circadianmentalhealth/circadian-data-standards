# Actigraphy & Wearable Sensor Data

## Purpose

This Document  provides standardised reporting guidelines for actigraphy-based sleep and circadian rhythm studies. It details device specifications, data collection methodologies, and processing techniques. Researchers using wearable sensor data should ensure all critical details are documented for reproducibility and transparency.

## Sections to Include

### Device Information

- **Brand & Model:** Specify the brand and model of the device used (e.g., ActiGraph GT9X, Fitbit Charge 4, Oura Ring).
- **Firmware Version:** Document the firmware version as updates may affect data processing.
- **Sensor Type:** Specify the type of sensors included (e.g., accelerometer, gyroscope, PPG for heart rate).

### Data Collection

- **Sampling Frequency:** Note the frequency of data recording (e.g., 30 Hz for raw accelerometer data, 1-minute epochs for activity counts).
  
- **Measurement Parameters:**
  Activity counts (if applicable) and computation method.
  Sleep-wake detection: Specify the algorithm or scoring method (e.g., Cole-Kripke, proprietary Fitbit algorithm).
  Light Exposure: If included, specify the spectral range and sensitivity of the sensor.
  Heart Rate Variability (HRV): If available, include details on derivation methods.

- **Study Protocol:**
  Total monitoring duration (e.g., 7 days, 24-hour monitoring).
  Specific instructions given to participants (e.g., wear on the non-dominant wrist, remove only during showering).

- **Data Format**
   Raw vs. Processed Data: Clearly separate and document raw sensor data and any processed data (e.g., sleep scoring outputs).
  File Types: Specify formats used (CSV, EDF, JSON, proprietary formats like AGD).

### Preprocessing & Quality Control

  Artifact Removal: Methods used to detect and correct artifacts (e.g., non-wear detection based on activity thresholds).
  Handling Missing Data: Strategies for handling missing or incomplete data (e.g., imputation methods, exclusion criteria).

### Metadata

  **Participant Compliance:** Adherence to wearing instructions, self-reported wear-time logs.
  **Environmental Context:** Additional data sources such as light exposure, temperature conditions, or subjective sleep diaries.
