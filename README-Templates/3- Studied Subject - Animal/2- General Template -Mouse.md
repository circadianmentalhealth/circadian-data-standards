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

## Ethical statements 
> Include ethical approval number and the guidelines used to conduct the experiment. 

## Dataset Folder/File Overview
Data file list: 

> All folders/files in the dataset should be listed here. If a file naming schema is used, it is fine to explain it instead of listing all the files. Filenames should include extension.

File formats: 

> State the file formats used and how to open specific file formats when applicable.  
> Export any proprietary file formats to open formats whenever possible. For example, export images saved as .czi or .lif (Zeiss and Leica formats) to .tiff, or data saved as .mat or .spss to .csv or .json.  
> Make sure no data was lost or corrupted during conversion and test opening the converted files. Check that formulas and scripts  still function after export. 


Dataset structure:

> Preferably include a directory structure similar to the one shown in the example below. When a large number of files is present, listing only main folders is fine, as long as the content of the folder is described.

 |--`Mice_monitoring_data/`       
 |  |--`wheel-running_raw.csv`              
 |  |--`wheel-running_analysed.csv`    
         
 |--`Brain_confocal_imaging/`  
 |  |--`SCN_control_S01`  
 |  |--`SCN_control_S02`    
 |  |--`SCN_control_S03`    
 |  |--`SCN_treatment_S01`    
 |  |--`SCN_treatment_S02`    
 |  |--`SCN_treatment_S03`    
      
# Methodological information 

## Biosample description
> Description of biological entity that was monitored / measured/ experimented on.    
> Typical content will have information about:
 - Species;  
 - Genotypes/ strains used
     - include designations (e.g., *wt*, *mutant_name*) and unique identifiers when applicable
 - Provenance of animals and strains. If new strains were generated, describe how this was done. 
 - Age / developmental stage - for standard mouse developmental stages look [here](https://bioportal.bioontology.org/ontologies/MMUSDV/?p=classes);  
 - Sex;
 - If experiments were done in vivo / Ex vivo / In vitro;  
 - Sample type collected: Whole mouse / organ / tissues/ cells / extracts.
 - Number of animals studied

## Husbandry 
> Describe the conditions where the animals were grown. Differentiate Control condition from Treatment conditions when applicable.   
> Typical descriptions will include:  
  - Feeding: type of diet / food availability / time when food was offered  
  - Housing:
    - Housing apparatus description. Include a link to commercial apparatus where applicable. 
    - Number of individuals per box
    - Temperature
    - Humidity
    - Bedding type
    - Light intensity
    - Type of light (fluorescent, LED panel, colour temperature, etc)
    - Presence of running wheels
    - Sound control (are cages soundproof?)
  - Entrainment: add light/dark cycles where animals are entrained and the light intensity used when applicable. 

## Experimental design and conditions
> Here you will describe your experimental design. For example, if mice were divided in different groups and the treatments applied to which group. Describe the control group.   
> For any type of measurement, describe the animals that were selected for analysis and the number of samples.  
> If necessary, include separate README files for each experiment type (measured data type). For example, a separate README file for Imaging experiments and a separate README file for gene expression experiments.  
> Describe measured techniques and the measured data. Some suggestions are described next. Feel free to include new sections or delete sections that are not applicable to your work: 

### Treatments
> Describe any specific treatment applied. For example:   
  - brain (SCN) lesions;  
  - light pulse stimuli;  
  - phase-shifting;  
  - pharmacological interventions.
> Add timing of interventions - **use Zeitgeber time (ZT)**

### Live activity monitoring
> Describe the activity monitoring system. Typical descriptions include:
   - Activity and monitoring system used (e.g., wheel running activity, infrared camera, etc.)
   - How data was measured and recorded.
   - Developmental stage and sex of monitored animals 
   
### Sample preparation
> When the experiment involves euthanasia and sample preparation, include: 
   - Animals selected for euthanasia (sex, developmental stage)
   - Time when animals were anesthetized and/or euthanized
   - Euthanasia method 
   - Sample collected from mice - for standards (ontologies) in adult mouse brain regions look [here](https://bioportal.bioontology.org/ontologies/ABA-AMB?p=classes&conceptid=http%3A%2F%2Fmouse.brain-map.org%2Fatlas%2Findex.html%23SCH)
   - Sample preparation protocol
   - Number of biological samples analysed

### Imaging
> If not described earlier in sample preparation, include a description of sample preparation and mounting for imaging or add links to corresponding protocols.
   - Imaging method: (e.g. fluorescence microscopy, bioluminescence, etc)
   - Image acquisition:   
     - Instrument used
     - Image acquisition parameters (filters used, magnification, etc.)

   - Image data:
     - Describe if you are sharing raw, processed, and/or segmented images.
     - File formats
     - Image dimensions
     - Channel information
     - Image processing methodology

## Data analysis
> Describe how the data was analysed including any software used and its version.  
> Include any data processing (detrending, smoothing, averaging, etc).  
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
