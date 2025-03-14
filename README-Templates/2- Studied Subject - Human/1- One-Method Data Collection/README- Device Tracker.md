# README: Device Tracker Dataset

# 1- Essential (Core) Metadata Elements  

## General Information

- **Title of Dataset**  
  Provide the dataset title (e.g., "Light Exposure and Sleep Activity Data").

- **Description**  
  Briefly describe the datasets

- **Author(s)/Contributor(s)**
  [Name], [Affiliation], [Email]
  [Name], [Affiliation], [Email]

  The Corresponding author is: [Author Name]

- **Date of Creation/Release** [YYYY-MM-DD]

- **DOI or Persistent Identifier** [Insert DOI or repository link if available]

## Dataset Overview

- **Data Format**:
  Describe the file formats of your data and provide instructions on how to access and open them, especially if you are using less common or non-open formats.
  
- **Data Dictionary**

| **Variable**     | **Description**                | **Type**     |  
|------------------|--------------------------------|--------------|  
| `participant_id` | Unique ID for participants     | Categorical  |  
| `age`            | Age in years                   | Numeric      |


## Methodology

- **Data Collection**  
  - Explain calibration processes.  
  - Describe sampling intervals (e.g., "Data recorded every 30 seconds").

- **Data Analysis** 
  Software used: Python (pandas, numpy), R (tidyverse), MATLAB.
  Analysis includes correlation tests, regression modeling, and clustering.

  
## Usage and Access

- **Licence** 
  [Specify license, e.g., CC BY 4.0]

- **Related Publications/Protocols**
  [Related research paper]
  [Study protocol link]
---

# 2- Extended Metadata Elements 

## General Information

- **Summary/Abstract**  
  Describe the purpose of the dataset and the devices used (e.g., "Actigraphy Data to Measure Sleep Patterns in Adults").

- **Purpose/Objective**  
  Explain how device data contributes to understanding circadian rhythms or mental health.

- **Dataset Version** v1.0
  
-  **Funding Information** This study was supported by [Funding Agency, Grant Number].

- **Acknowledgments**
  We acknowledge the contributions of [Institution, Participants, Collaborators]

## Dataset Overview

- **Dictionary Structure**

  ├── Device_Tracker_Data/       
  │   ├── raw_tracker_data.csv        
  │   ├── processed_tracker_data.csv        
  │       
  ├── Documentation/       
  │   ├── Data_Dictionary.xlsx      
  │   ├── README.md  

- **Device Specifications**  
  - Name, model, and manufacturer of the device.  
  - Firmware or software versions used.

- **Data Format**  
  - Explain the structure of the files (e.g., CSV, JSON).  
  - Provide details on key variables (e.g., timestamps, light exposure).

- **Participant Instructions**  
  Describe how participants were instructed to use the device (e.g., "Wear on the non-dominant wrist for 14 days").

## Methodology

- **Data Processing**  
  - Detail preprocessing steps for raw data.  
  - Describe derived metrics (e.g., total sleep time, activity counts).
  
- **Ethical Considerations**  
  Highlight privacy safeguards for participant data.

## Usage and Access

- **Usage Instructions**  
  Include guidelines for interpreting device data (e.g., "Activity levels are measured in arbitrary units").

- **Citing the Dataset**  
  Provide citation details.
