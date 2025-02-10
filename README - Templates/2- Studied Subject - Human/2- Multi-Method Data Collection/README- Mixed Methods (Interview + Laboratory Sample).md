# README: Mixed Methods (Survey + Device Tracker)

## General Information

- **Summary/Abstract**  
  Describe the purpose of the dataset and the devices used
  > for example: This dataset includes qualitative data from participant interviews alongside biological samples collected in a laboratory setting. The study explores relationships between subjective experiences and objective physiological markers related to sleep, circadian rhythms, and mental health.

- **Purpose/Objective**  
  Explain the purpose, aims, objective of your project and from this datasets.
  > For Example: The dataset was created to examine the correlation between self-reported behaviors, emotional states, and physiological biomarkers. It aims to bridge qualitative narratives with biological evidence for improved understanding of mental health and circadian research.

- **Title of Dataset**  
  Provide the dataset title
  > For example: "Interview and Laboratory Sample Dataset for Sleep and Mental Health, 2023"

- **Author(s)/Contributor(s)**
  [Name], [Affiliation], [Email]
  [Name], [Affiliation], [Email]

  The Corresponding author is: 

- **Date of Creation/Release** [YYYY-MM-DD]

- **Dataset Version** v1.0

- **DOI or Persistent Identifier** [Insert DOI or repository link if available]

- **Funding Information** This study was supported by [Funding Agency, Grant Number].

- **Acknowledgments**
  We acknowledge the contributions of [Institution, Participants, Collaborators]

---

## Dataset Overview

- **Dictionary Structure**

├── Interview_Data/  
│   ├── transcripts/        
│   │   ├── participant1_transcript.txt         
│   │   ├── participant2_transcript.txt        
│   ├── interview_metadata.json      
│    
├── Laboratory_Sample_Data/    
│   ├── raw_sample_data.csv    
│   ├── processed_biomarker_data.csv     
│      
├── Documentation/    
│   ├── Data_Dictionary.xlsx    
│   ├── README.md     


- **Dataset Description***

  Interview_Data/: Contains interview transcripts, audio recordings (if applicable), and metadata.
  Laboratory_Sample_Data/: Includes raw and processed data from biological samples (e.g., blood, saliva, hair cortisol).
  Documentation/: Metadata files describing variables, data dictionary, and study protocols.

- **Device Specifications**  
  - Name, model, and manufacturer of the device.  
  - Firmware or software versions used.

- **Data Format**  
  - Explain the structure of the files (e.g., CSV, JSON).  
  - Provide details on key variables (e.g., timestamps, light exposure).

- **Participant Instructions**  
  Describe how participants were instructed to use the device (e.g., "Wear on the non-dominant wrist for 14 days").

- **Data Dictionary**

| **Variable**     | **Description**                | **Type**     |  
|------------------|--------------------------------|--------------|  
| `participant_id` | Unique ID for participants     | Categorical  |  
| `age`            | Age in years                   | Numeric      |
| `step_count`     | Number of steps (by device)    | Integer     |

---
## Methodology

- **Ethical Approvals**
  This study was approved by [Institutional Review Board Name, Approval Number]. Participants provided informed consent.

- **Data Collection Timeline**

  Baseline Survey: Conducted on [Start Date].
  Wearable Device Tracking: Started on [Start Date] and continued for [X] days.
  Follow-up Surveys: Conducted on [Follow-up Dates] to capture changes over time.
  Final Data Collection Point: Concluded on [End Date].
  Integration Points: Survey data was re-collected at key intervals ([list intervals]) to align with wearable tracking periods.


- **Data Collection**  
  - Explain calibration processes.  
  - Describe sampling intervals (e.g., "Data recorded every 30 seconds").
  - Survey: Participants completed an online questionnaire using [Survey Platform].
  - Device Tracking: Wearable devices (e.g., Actigraphy, Fitbit, Garmin) recorded step count, heart rate, and sleep duration.

- **Data Processing**  
  - Detail preprocessing steps for raw data.  
  - Describe derived metrics (e.g., total sleep time, activity counts).
  - Survey Data: Checked for missing responses, validated against expected ranges.
  - Device Data: Time-synced with survey timestamps, noise reduction applied.
  - Data Integration: Matched based on participant ID and timestamp.

- **Data Analysis**

  Software used: Python (pandas, numpy), R (tidyverse), MATLAB.
  Analysis includes correlation tests, regression modeling, and clustering.

- **Ethical Considerations**  
  Highlight privacy safeguards for participant data.

  ----
  
## Usage and Access

- **Licence** 
  [Specify license, e.g., CC BY 4.0]


- **Usage Instructions**  
  Include guidelines for interpreting device data (e.g., "Activity levels are measured in arbitrary units").
  Load survey responses using Python (pandas.read_csv) or R (read.csv).
  Device tracker data can be processed using [specific libraries, e.g., ActiLife, FitBit API].
  Refer to Data_Dictionary.xlsx for variable descriptions.

- **Citing the Dataset**  
  Provide citation details.
  [Author(s)], [Year]. "Survey and Wearable Device Tracker Dataset for Sleep and Mental Health". [Repository/DOI].

- **Related Publications/Protocols**
  [Related research paper]
  [Study protocol link]
