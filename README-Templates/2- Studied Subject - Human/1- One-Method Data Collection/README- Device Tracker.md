# README: Device Tracker Dataset

# 1- Essential (Core) Metadata Elements  
> Without these 7 pieces of information, it will be hard for anyone to locate and re-use your data.

## General Information
> You can refer to the Extended metadata (below), where you add more detailed information.

- **Title**  
> Provide the dataset title (e.g., "Light Exposure and Sleep Activity Data").

- **Description**  
> Briefly describe the dataset content including basic information on the methodology used. 

- **Author(s)/Contributor(s)**  
  [Name], [Affiliation], [Email]  
  [Name], [Affiliation], [Email]  

  The Corresponding author is: [Author Name]

- **Date of Creation/Release**  
  [YYYY-MM-DD]
> Date must be expressed in ISO format: **YYYY-MM-DD** (e.g. 2023-03-25)

- **DOI or Persistent Identifier**  
  [Insert DOI or repository link if available]

## Dataset Overview  

- **File Formats**:
> **If using standard file formats such as .csv, .fasta, .tiff, etc, you can skip this section.**
> Export any proprietary file formats to open formats whenever possible. For example, export images saved as .czi or .lif (Zeiss and Leica formats) to .tiff, or data saved as .mat or .spss to .csv or .json.  
> Make sure no data was lost or corrupted during conversion and test opening the converted files. Check that formulas and scripts still function after export.   
> **If using uncommon or proprietary formats is unavoidable, list the data file formats and explain how to open the files.**
  
- **Data Dictionary**
> Describe the data elements

| **Variable**     | **Description**                | **Type**     |  
|------------------|--------------------------------|--------------|  
| `participant_id` | Unique ID for participants     | Categorical  |  
| `age`            | Age in years                   | Numeric      |


## Usage and Access

- **Licence** 
 > For data that do not include code/ software, we recommend either a CC-BY or a CC0 license: keep the text for one, delete the other!

This dataset is released under the [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).  
You are free to use, share, and adapt this dataset as long as you give appropriate credit.

>**or**

This dataset is released under the [CC0 1.0 Universal (Public Domain Dedication)](https://creativecommons.org/publicdomain/zero/1.0/). 
You are free to copy, modify, distribute, and use the data without restrictions.

> Generally, CC-BY 4.0 works well for scientific data as it states that data may be used freely, but attribution must be given to the original authors of the dataset. Another option is CC0, a licence made to reduce any legal and technical impediments to data sharing. CC0 provides creators a way to waive all their copyright and related rights in their works to the fullest extent allowed by law. Although CC0 doesn’t legally require users of the data to cite the source, it does not affect the ethical norms for attribution in scientific and research communities. i.e., it does not exempt researchers from the obligation of citing the original data authors. 

> For **code / software** we recommend [MIT licence](https://opensource.org/license/mit) for its simplicity. However, other types of open source licenses and their descriptions can be found in [Open Source Initiative ](https://opensource.org/licenses)

- **Related Resources**
 > Include links (preferably a DOI) of any other datasets, publications and protocols that are related to this dataset.

---

# 2- Extended Metadata Elements 
> Add this information to help others to understand, re-use and cite your data correctly.

## General Information

- **Summary/Abstract**  
> Describe the purpose of the dataset and the devices used (e.g., "Actigraphy Data to Measure Sleep Patterns in Adults").

- **Purpose/Objective**  
> Explain how device data contributes to understanding circadian rhythms or mental health.

- **Dataset Version**  
> Include verison number. E.g., v1.0
  
-  **Funding Information**  
   This study was supported by [Funding Agency, Grant Number].

- **Acknowledgments**  
  We acknowledge the contributions of [Institution, Participants, Collaborators]

## Dataset Overview

- **Dataset Structure**
> All folders/files in the dataset should be listed here. If a file naming schema is used, it is fine to explain it instead of listing all the files.    
> Filenames should include extension (state the file formats used).  
> Preferably include a directory structure similar to the one shown in the example below. When a large number of files is present, listing only main folders is fine, as long as the content of the folder is described.  

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

- **Participant Instructions**  
> Describe how participants were instructed to use the device (e.g., "Wear on the non-dominant wrist for 14 days").

## Methodology

- **Data Collection**
> Provide data collection information such as: 
   - Information about patient recruitment criteria, number of participants, etc. 
   - Explain device calibration processes.  
   - Describe sampling intervals (e.g., "Data recorded every 30 seconds").
   - Provide details on key variables (e.g., timestamps, light exposure).
   - Provide the timing of any interventions. 

- **Data Analysis** 
> Include any software used. E.g., Python (pandas, numpy), R (tidyverse), MATLAB.  
> Describe if analysis includes correlation tests, regression modeling, and clustering.  

- **Data Processing**  
> Detail preprocessing steps for raw data.  
> Describe derived metrics (e.g., total sleep time, activity counts).
    
- **Ethical Considerations**  
>  Highlight privacy safeguards for participant data.

## Usage and Access

- **Usage Instructions**  
> Include guidelines for interpreting device data (e.g., "Activity levels are measured in arbitrary units"), and for reproducing or reusing the data. 

- **Citing the Dataset**  
  Provide citation details.
