# README: Mixed Methods (Interview + Laboratory Sample)

# 1- Essential (Core) Metadata Elements  

## General Information

- **Title of Dataset**  
  Provide the dataset title
  > For example: "Interview and Laboratory Sample Dataset for Sleep and Mental Health, 2023"

- **Description**  
  Briefly describe the datasets

- **Author(s)/Contributor(s)**
  [Name], [Affiliation], [Email]
  [Name], [Affiliation], [Email]

  The Corresponding author is: 

- **Date of Creation/Release** [YYYY-MM-DD]

- **DOI or Persistent Identifier** [Insert DOI or repository link if available]


## Dataset Overview

- **Data Format**       
  Describe the file formats of your data and provide instructions on how to access and open them, especially if you are using less common or non-open formats.

- **Dataset Description**
  Interview_Data/: Contains interview transcripts, audio recordings (if applicable), and metadata.
  Laboratory_Sample_Data/: Includes raw and processed data from biological samples (e.g., blood, saliva, hair cortisol).
  Documentation/: Metadata files describing variables, data dictionary, and study protocols.

- **Participant Instructions**  
  Describe how participants were instructed to use the device (e.g., "Wear on the non-dominant wrist for 14 days").

- **Data Dictionary**
- 
| **Variable**     | **Description**                | **Type**     |  
|------------------|--------------------------------|--------------|  
| `participant_id` | Unique ID for participants     | Categorical  |  
| `age`            | Age in years                   | Numeric      |
| `interview_date` | Date of interview completion   | YYYY-MM-DD   |
| `transcript_text`| Full interview transcript text | Text         |

---
## Methodology

- **Data Collection Timeline**

  Baseline Interview: Conducted on [Start Date].
  Laboratory Sample Collection: Conducted on [Start Date] at [Lab Name].
  Follow-up Interviews: Conducted on [Follow-up Dates] to assess longitudinal changes.
  Final Data Collection Point: Concluded on [End Date].
  Integration Points: Follow-up interviews were conducted after biological sample analysis.

- **Data Analysis**
  Qualitative Analysis: Thematic coding performed using NVivo/ATLAS.ti.
  Biomarker Analysis: Statistical analysis performed using R, Python, or SPSS.
  Mixed-Methods Integration: Merging interview themes with biological data for correlational analysis..

  
## Usage and Access

- **Licence** 
  [Specify license, e.g., CC BY 4.0]


- **Related Publications/Protocols**
  [Related research paper]
  [Study protocol link]

---

# 2- Extanded Metadata Elements 

## General Information

- **Summary/Abstract**  
  Describe the purpose of the dataset and the devices used
  > for example: This dataset includes qualitative data from participant interviews alongside biological samples collected in a laboratory setting. The study explores relationships between subjective experiences and objective physiological markers related to sleep, circadian rhythms, and mental health.

- **Purpose/Objective**  
  Explain the purpose, aims, objective of your project and from this datasets.
  > For Example: The dataset was created to examine the correlation between self-reported behaviors, emotional states, and physiological biomarkers. It aims to bridge qualitative narratives with biological evidence for improved understanding of mental health and circadian research.

- **Dataset Version** v1.0

- **Funding Information** This study was supported by [Funding Agency, Grant Number].

- **Acknowledgments**
  We acknowledge the contributions of [Institution, Participants, Collaborators]


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


- **Data Format**  
  - Explain the structure of the files (e.g., CSV, JSON).  
  - Provide details on key variables (e.g., timestamps, light exposure).

---
## Methodology

- **Ethical Approvals**
  This study was approved by [Institutional Review Board Name, Approval Number]. Participants provided informed consent.

- **Data Collection Timeline**
  Baseline Interview: Conducted on [Start Date].
  Laboratory Sample Collection: Conducted on [Start Date] at [Lab Name].
  Follow-up Interviews: Conducted on [Follow-up Dates] to assess longitudinal changes.
  Final Data Collection Point: Concluded on [End Date].
  Integration Points: Follow-up interviews were conducted after biological sample analysis.

- **Data Processing**  
  - Interview Data: Transcripts were anonymised and coded for thematic analysis.
  - Laboratory Data: Samples were processed and analyzed for specific biomarkers (e.g., cortisol, melatonin levels).
  - Specify the collection method (e.g., "Saliva collected using passive drool").
  - Data Integration: Participant ID was used to link qualitative and biomarker data.

- **Ethical Considerations**  
  Highlight privacy safeguards for participant data.


## Usage and Access

- **Usage Instructions**  
  Interview transcripts can be analyzed using qualitative software.
  Biomarker data can be processed in statistical analysis programs.
  Refer to Data_Dictionary.xlsx for variable descriptions.

- **Citing the Dataset**  
  Provide citation details.
  [Author(s)], [Year]. "Interview and Laboratory Sample Dataset for Sleep and Mental Health". [Repository/DOI].
