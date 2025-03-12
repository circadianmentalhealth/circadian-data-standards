# README: Mixed Methods (Survey + Device Tracker)

# 1- Essential (Core) Metadata Elements  

## General Information

- **Title of Dataset**  
  Provide the dataset title
  > For example: "Survey and Wearable Device Tracker Dataset for Sleep and Mental Health, 2023"

- **Author(s)/Contributor(s)**
  [Name], [Affiliation], [Email]
  [Name], [Affiliation], [Email]

  The Corresponding author is: 

- **Date of Creation/Release** [YYYY-MM-DD]

- **DOI or Persistent Identifier** [Insert DOI or repository link if available]

## Dataset Overview

- **Data Format**  
  Describe the file formats of your data and provide instructions on how to access and open them, especially if you are using less common or non-open formats.
  
- **Device Specifications**  
  - Name, model, and manufacturer of the device.  
  - Firmware or software versions used.

- **Survey Details**  
  - Name and version of the survey instrument used (e.g., "Pittsburgh Sleep Quality Index, v2").
  - Description of survey structure (e.g., number of questions, type of response scales).
  - Validation references for the survey tool.

- **Participant Instructions**  
  Describe how participants were instructed to use the device (e.g., "Wear on the non-dominant wrist for 14 days").

- **Data Dictionary**

| **Variable**     | **Description**                | **Type**     |  
|------------------|--------------------------------|--------------|  
| `participant_id` | Unique ID for participants     | Categorical  |  
| `age`            | Age in years                   | Numeric      |
| `step_count`     | Number of steps (by device)    | Integer     |


## Methodology

- **Data Collection Timeline**
  Baseline Survey: Conducted on [Start Date].
  Wearable Device Tracking: Started on [Start Date] and continued for [X] days.
  Follow-up Surveys: Conducted on [Follow-up Dates] to capture changes over time.
  Final Data Collection Point: Concluded on [End Date].
  Integration Points: Survey data was re-collected at key intervals ([list intervals]) to align with wearable tracking periods.

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
  Describe the purpose of the dataset and the devices used
  > for example: This dataset includes both self-reported survey responses and objective data collected through wearable device trackers. The study investigates the relationship between subjective and objective measures of sleep, physical activity, and mental health outcomes.

- **Purpose/Objective**  
  Explain the purpose, aims, objective of your project and from this datasets.
  > For Example: The dataset was created to examine the correlation between self-reported behaviors and physiological data collected via wearable devices. It aims to improve the accuracy of self-reported measures and enhance research in circadian rhythms and mental health.

- **Dataset Version** v1.0

- **Funding Information** This study was supported by [Funding Agency, Grant Number].

- **Acknowledgments**
  We acknowledge the contributions of [Institution, Participants, Collaborators]


## Dataset Overview

- **Dictionary Structure**

  ├── Survey_Data/          
  │   ├── survey_responses.csv          
  │   ├── survey_metadata.json         
  │    
  ├── Device_Tracker_Data/       
  │   ├── raw_tracker_data.csv        
  │   ├── processed_tracker_data.csv        
  │       
  ├── Documentation/       
  │   ├── Data_Dictionary.xlsx      
  │   ├── README.md         

- **Dataset Description***
  Survey_Data/: Contains survey responses in CSV format with metadata.
  Device_Tracker_Data/: Includes raw and processed data from wearable devices.
  Documentation/: Metadata files describing variables, data dictionary, and study protocols.

- **Data Format**  
  - Explain the structure of the files (e.g., CSV, JSON).  
  - Provide details on key variables (e.g., timestamps, light exposure).

## Methodology

- **Ethical Approvals**
  This study was approved by [Institutional Review Board Name, Approval Number]. Participants provided informed consent.

- **Data Processing**  
  - Detail preprocessing steps for raw data.  
  - Describe derived metrics (e.g., total sleep time, activity counts).
  - Survey Data: Checked for missing responses, validated against expected ranges.
  - Device Data: Time-synced with survey timestamps, noise reduction applied.
  - Data Integration: Matched based on participant ID and timestamp.

- **Ethical Considerations**  
  Highlight privacy safeguards for participant data.

 
## Usage and Access

- **Licence** 
  [Specify license, e.g., CC BY 4.0]

- **Related Publications/Protocols**
  [Related research paper]
  [Study protocol link]
