# README: Interview/Focus Group Dataset

# 1. Essential (Core) Metadata Elements  
> Without these 7 pieces of information, it will be hard for anyone to locate and re-use your data.  
> You can refer to the "Extended metadata" template (below), where you add more detailed information.  

## General Information

### Title of Dataset
> Provide a clear title (e.g., "Focus Group Discussions on Sleep and Anxiety").

### Description
  Briefly describe the datasets

### Author(s)/Contributor(s)
> List of dataset creators and contributors and their respective emails.
> > Use `FirstName LastName` format. Each contributor name should be in a separate line which starts with `-`.  
> See the example entry bellow:
  [Name], [Affiliation], [Email]
  [Name], [Affiliation], [Email] *

  *Corresponding author 

### Date of Creation/Release   
  [YYYY-MM-DD]
  > A point in time associated with the lifecycle of the dataset.  
  > Date must be expressed in ISO format: **YYYY-MM-DD** (e.g. 2023-03-25)

### DOI or Persistent Identifier         
[Insert DOI or repository link if available]


## Dataset Overview

### Description
> Briefly describe the dataset content including basic information on the methodology used. 

### File Formats

> **If using standard file formats such as .csv, .fasta, .tiff, etc, you can skip this section.**  
> Export any proprietary file formats to open formats whenever possible. For example, export images saved as .czi or .lif (Zeiss and Leica formats) to .tiff, or data saved as .mat or .spss to .csv or .json.  
> Make sure no data was lost or corrupted during conversion and test opening the converted files. Check that formulas and scripts still function after export.   
> **If using uncommon or proprietary formats is unavoidable, list the data file formats and explain how to open the files.**


## Usage and Access 

### Licence
 > For data that do not include code/ software, we recommend either a CC-BY or a CC0 license: keep the text for one, delete the other!

This dataset is released under the [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).  
You are free to use, share, and adapt this dataset as long as you give appropriate credit.

>**or**

This dataset is released under the [CC0 1.0 Universal (Public Domain Dedication)](https://creativecommons.org/publicdomain/zero/1.0/). 
You are free to copy, modify, distribute, and use the data without restrictions.

> Generally, CC-BY 4.0 works well for scientific data as it states that data may be used freely, but attribution must be given to the original authors of the dataset. Another option is CC0, a licence made to reduce any legal and technical impediments to data sharing. CC0 provides creators a way to waive all their copyright and related rights in their works to the fullest extent allowed by law. Although CC0 doesn’t legally require users of the data to cite the source, it does not affect the ethical norms for attribution in scientific and research communities. i.e., it does not exempt researchers from the obligation of citing the original data authors. 

> For **code / software** we recommend [MIT licence](https://opensource.org/license/mit) for its simplicity. However, other types of open source licenses and their descriptions can be found in [Open Source Initiative ](https://opensource.org/licenses)

### Related Publications/Protocols
  > Include links (preferably a DOI) of any other datasets, publications and protocols that are related to this dataset.

---

# 2- Extended Metadata Elements
> Add this information to help others to understand, re-use and cite your data correctly.

## General Information

### Summary/Abstract 
> A short and contextualized description of the data, containing a brief overview of the the dataset purpose, methods and (if applicable) results.  
> The comprehensives details are to be recorded in sections below. This section should help others to understand the content of the dataset without its thorough examination.
> This section can replace the "Description" section if information overlaps. 

### Purpose (Research hypothesis)
> Describe the purpose of the study or intention for conducting a study that resulted in the dataset.
> Or the hypothesis that a study sets out to support (or disprove);
> For example, explain how semi-structured intrviews have been used to identify the social economic factors that associated with low mood.

### Dataset Version
> Include verison number. E.g., v1.0

### Funding Information  
This study was supported by [Funding Agency, Grant Number].

### Acknowledgments
We acknowledge the contributions of [Institution, Participants, Collaborators]


## Dataset Overview

### Dictionary Structure
> All folders/files in the dataset should be listed here. If a file naming schema is used, it is fine to explain it instead of listing all the files.    
> Filenames should include extension (state the file formats used).  
> Preferably include a directory structure similar to the one shown in the example below. When a large number of files is present, listing only main folders is fine, as long as the content of the folder is described.  

├── Interview_Data/  
│   ├── transcripts/        
│   │   ├── participant1_transcript.txt         
│   │   ├── participant2_transcript.txt        
│   ├── interview_metadata.json      
│    
├── Documentation/    
│   ├── Data_Dictionary.xlsx    
│   ├── README.md     

### Data Dictionary

| **Variable**     | **Description**                | **Type**     |  
|------------------|--------------------------------|--------------|  
| `participant_id` | Unique ID for participants     | Categorical  |  
| `age`            | Age in years                   | Numeric      |


## Methodology

### Data Collection  
  Explain the interview protocol and tools used for recording.

### Interview Details     
> Provide a summary of the interview guide, including sample questions.
> State the typical duration of each session.
> Specify the mode (e.g., in-person, virtual).
  
### Participant Demographics
> Recruitment criteria (e.g., inclusion/exclusion criteria).  
> Key demographic details (e.g., age, gender).

### Data Processing  
> Detail preprocessing steps for raw data.
> Describe transcription and anonymization steps.
> Mention any software used for transcription or coding (e.g., NVivo).
  
### Data Analysis
> Include any software used. E.g., Python (pandas, numpy), R (tidyverse), MATLAB.    
> Describe if analysis includes correlation tests, regression modeling, and clustering.     
 
### Ethical Approvals
  This study was approved by [Institutional Review Board Name, Approval Number]. Participants provided informed consent.

## Usage and Access

### Usage Instructions
> Include guidelines for qualitative analysis (e.g., using thematic analysis).

### Citing the Dataset   
> Provide an appropriate citation format.
