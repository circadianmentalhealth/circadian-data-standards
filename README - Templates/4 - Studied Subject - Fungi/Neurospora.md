# General information

## Title: 
> A descriptive name given to the dataset.

## Authors / contributors
> List of people of dataset creators and contributors.  
> Use `FirstName LastName` format, each contributor name should be in a separate line which starts with `-`.  
> See the example entry bellow
- Ana Student
- Tom Thorough
- Diana Helpful *  
*corresponding author [diana.help@edu.uni.uk]

## Date: YYYY-MM-DD
> A point in time associated with the lifecycle of the dataset.  
> Used mainly to cross-reference with other resources like Lab Notebooks or raw data.  
> Date must be expressed in ISO format: **YYYY-MM-DD** (e.g. 2023-03-25)  

## Purpose (Research Hypothesis)
> The overall rationale, reason, or intention for conducting a study that resulted in the data set.   
> Or the hypothesis that a study sets out to support (or disprove);

## Abstract
> A summary of the content of the dataset.  
> Should include a brief information about the biological material, techniques used and measurement/experimental conditions. 
> The comprehensives details are to be recorded in sections below. 
> Here we expect a short description that helps to understand the content of the dataset without its thorough examination.

## Funding Information 
This study was supported by [Funding Agency, Grant Number].

## Acknowledgments
> Add any acknowledgements

## Dataset Folder/File Overview
Data file list: 

> All folders/files in the dataset should be listed here. If a file naming schema is used, it is fine to explain it instead of listing all the files.   
> Filenames should include extension. 

File formats: 

> State the file formats used and how to open specific file formats when applicable. 
> Export any proprietary file formats to open formats whenever possible. For example, export images saved as .czi or .lif (Zeiss and Leica formats) to .tiff, or data saved as .mat or .spss to .csv or .json.  
> Make sure no data was lost or corrupted during conversion and test opening the converted files. Check that formulas and scripts (e.g., MATLAB) still function after export. 


Dataset structure:

> Preferably include a directory structure similar to the one shown in the example below. When a large number of files is present, listing only main folders is fine, as long as the content of the folder is described.

 |--`zebrafish_actogram_data/`       
 |  |--`14L10D_male.csv`              
 |  |--`14L10D_female.csv`    
         
 |--`larval_moving_image_data/`  
 |  |--`Control_S01`  
 |  |--`Control_S02`    
 |  |--`Control_S03`    
 |  |--`Heat_treatment_S01`    
 |  |--`Heat_treatment_S02`    
 |  |--`Heat_treatment_S03` 

 > In this example image data are represented by folders and image files are ommited for clarification due the large number of individual files. 
      
# Methodological information 

## Biosample description
> Description of biological entity that was monitored / measured/ experimented on.    
> Typical content will have information about:
 - Species;  
 - List of genotypes/ strains used 
     - include designations (e.g., *wt*, *mutant_name*) and unique identifiers when applicable.  
     - describe the strain (e.g., period defect KO).  
     - Include the provenance of strains. If new strains were generated, describe how this was done.
 
## Growth conditions
> Describe the growth conditions. 
> Differentiate Control condition from Treatment conditions when applicable. 
> Differentiate growth conditions for vegetative growth, inoculation and colony isolation when applicable
> Typical descriptions will include:
  - Liquid/ solid media
  - Culture medium used 
  - Supplementation of culture medium including its concentration and source of chemicals. E.g.,: 2% glucose (CAS 50-99-7, Sigma-Aldrich) and  200 μg/ml hygromycin B (CAS 31282-04-9, ThermoFischer).
  - Volume of growth medium 
  - Growth temperature
  - Incubation time
  - Incubator used (e.g., Percival) 
  - Entrainment: add light/dark cycles and temperature where cultures were entrained and the light intensity when applicable.
  - Light/dark conditions and temperature during analysis if different from entraining 

## Experimental design and conditions
> Here you will describe your experimental design. 
> For any type of measurement, cite the strains used for analysis and the number of replicates used.  
> If necessary, include separate README files for each experiment type (measured data type). For example, a separate README file for Luciferase assay and a separate README file for RNA sequencing.  
> Describe measured techniques and the measured data. Some suggestions are described next. Feel free to include new sections or delete sections that are not applicable to your work: 

### Treatments / Stimuli
> Describe any specific treatment or stimuli applied. For example:   
  - light or dark pulse stimulus;
  - heat or cold stimulus;
  - starvation
  - chemical treatments (drug name, concentration, brand and identifier number) 
  - timing and duration of interventions - **use Zeitgeber time (ZT)**

### Race tube assay
> Describe the race tube assay.
  - Race tube medium.  
  - Origin of inoculum.  
  - Light/ dark and temperature conditions during analysis.  
  - Duration of analysis and measurement frequency.  
  - Describe how analysis was performed including any software and its version.
  
### Luciferase assay
> Describe the Luciferase assay.
  - Plates used.  
  - Growth medium.  
  - Medium supplementation including Luciferin. Add concentration and provenance of chemicals (e.g., 25 μM firefly luciferin (LUCNA-300; Gold Biotechnology, St. Louis, MO).  
  - Origin of inoculum.
  - Light/ dark and temperature conditions during experiment
  - Equipment and software used for bioluminescence measurements
  - Periodicity and duration of measurements (e.g., recordings were taken every 60 min over 5 days)
   
### Protein analysis





## Data analysis
> Describe how the data was analysed including any software used and its version.  
> Include any data processing (detrending, smoothing, averaging, etc).
> Describe any statistical analysis.
> Describe the methods used for period and phase analysis.   
     
# Dataset usage and access

## Licence
This dataset is shared under [Insert licence here]
> Generally, CC-BY 4.0 works well for scientific data as it states that data may be used freely, but attribution must be given to the original authors of the dataset. Another option is CC0, a licence made to reduce any legal and technical impediments to data sharing. CC0 provides creators a way to waive all their copyright and related rights in their works to the fullest extent allowed by law. Although CC0 doesn’t legally require users of the data to cite the source, it does not affect the ethical norms for attribution in scientific and research communities. i.e., it does not exempt researchers from the obligation of citing the original data authors. 

## Usage Instructions 
> Include guidelines for reproducing or reusing the data or to open specific file formats. 

## Citing the Dataset
> Provide citation details.

## Related Publications/Protocols
> Include links (preferably a DOI) of any other datasets, publications and protocols that are related to this dataset. 

