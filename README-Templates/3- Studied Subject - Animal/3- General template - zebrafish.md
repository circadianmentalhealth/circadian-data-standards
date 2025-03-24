# README template - Essential (Core) Metadata Elements
> Without these 7 pieces of information, it will be hard for anyone to locate and re-use your data.

## General information section
> You can refer to the Extended metadata (below), where you add more detailed information.

### Title 
> A descriptive name given to the dataset.

### Creator
> List of dataset creators and contributors and their respective emails.  
> Use `FirstName LastName` format. Each contributor name should be in a separate line which starts with `-`.  
> See the example entry bellow:

- Ana Student [Ana.Student@edu.uni.uk]   
- Tom Thorough [Tom.Thorough@edu.otheruni.uk]  
- Diana Helpful*  [diana.help@edu.uni.uk]  
*corresponding author 

### Date
YYYY-MM-DD
> A point in time associated with the lifecycle of the dataset.  
> Used mainly to cross-reference with other resources like Lab Notebooks or raw data.  
> Date must be expressed in ISO format: **YYYY-MM-DD** (e.g. 2023-03-25)

### Description
> Briefly describe the dataset content, including studied organism and basic methods used. 

### File Formats
> **If using standard file formats such as .csv, .fasta, .tiff, etc, you can skip this section.**  
> Export any proprietary file formats to open formats whenever possible. For example, export images saved as .czi or .lif (Zeiss and Leica formats) to .tiff, or data saved as .mat or .spss to .csv or .json.    
> Make sure no data was lost or corrupted during conversion and test opening the converted files. Check that formulas and scripts still function after export.     
> **If using uncommon or proprietary formats is unavoidable, list the data file formats and explain how to open the files.**  


## Dataset usage and access 

### Licence
> For data that do not include code/ software, we recommend either a CC-BY or a CC0 license: keep the text for one, delete the other!

This dataset is released under the [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).  
You are free to use, share, and adapt this dataset as long as you give appropriate credit.

>**or**

This dataset is released under the [CC0 1.0 Universal (Public Domain Dedication)](https://creativecommons.org/publicdomain/zero/1.0/). 
You are free to copy, modify, distribute, and use the data without restrictions.

> Generally, CC-BY 4.0 works well for scientific data as it states that data may be used freely, but attribution must be given to the original authors of the dataset. Another option is CC0, a licence made to reduce any legal and technical impediments to data sharing. CC0 provides creators a way to waive all their copyright and related rights in their works to the fullest extent allowed by law. Although CC0 doesn’t legally require users of the data to cite the source, it does not affect the ethical norms for attribution in scientific and research communities. i.e., it does not exempt researchers from the obligation of citing the original data authors. 

> For **code / software** we recommend [MIT licence](https://opensource.org/license/mit) for its simplicity. However, other types of open source licenses and their descriptions can be found in [Open Source Initiative ](https://opensource.org/licenses)

### Related resources 
> Include links (preferably a DOI) of any other datasets, publications and protocols that are related to this dataset.

---

# README template - Extended Metadata Elements
> Add this information to help others to understand, re-use and cite your data correctly. 

## General information section

### Purpose (Research Hypothesis)
> The overall rationale, reason, or intention for conducting a study that resulted in the data set.   
> Or the hypothesis that a study sets out to support (or disprove);

### Abstract
> A summary of the content of the dataset.  
> Should include a brief information about the biological material, technique used and measurement/experimental conditions. 
> The comprehensives details are to be recorded in sections below.
> Here we expect a short description that helps to understand the content of the dataset without its thorough examination.

### Funding Information 
This study was supported by [Funding Agency, Grant Number].

### Acknowledgments
> Add any acknowledgements


### Dataset Folder/File Overview
#### Data files list 

> All folders/files in the dataset should be listed here. If a file naming schema is used, it is fine to explain it instead of listing all the files.  
> Filenames should include extension (tate the file formats used).    

#### Dataset structure

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
      
## Methodological information section

### Ethical statements 
> Include ethical approval number and the guidelines used to conduct the experiment. 

### Biosample 
> Description of biological entity that was monitored / measured/ experimented on.    
> Typical content will have information about:
 - Species  
 - Genotypes/ lines used
     - include designations (e.g., *wt*, *mutant_name*) and unique identifiers when applicable
 - Provenance of animals and lines. If new lines were generated, describe how this was done (e.g., generation of new knockout lines)
 - Age / developmental stage range used- For [standard zebrafish developmental stages look here](https://bioportal.bioontology.org/ontologies/ZFS?p=classes)  
 - How eggs were obtained
 - Sex
 - If experiments were done in vivo / Ex vivo / In vitro  
 - Sample type collected: Whole fish / organ / tissues/ cells / extracts
 - Number of animals studied

### Husbandry 
> Describe the conditions where the animals were grown. 
> Differentiate Control condition from Treatment conditions when applicable. 
> Differentiate embryo and adult fish conditions when applicable.     
> Typical descriptions will include:  
  - Feeding: type of diet / food availability / time when food was offered  
  - Housing:
    - Tank description including water volume. Include a link to commercial tanks where applicable. 
    - Number of individuals per container (e.g., embryo density per petri dish or number of adult fish per tank) 
    - Water quality/ treatment (e.g., dechlorinated, salt content, anti-fungal treatment, oxygenation) 
    - Water pH, temperature, conductivity
    - Frequency of water change
  - Entrainment: add light/dark cycles where fish were entrained and the light intensity and light type when applicable. 

### Experimental design and conditions
> Here you will describe your experimental design. For example, if fish were divided in different groups and the treatments applied to which group. Describe the control group.   
> For [standards in Zebrafish experimental conditions look here](https://bioportal.bioontology.org/ontologies/ZECO?p=classes)

> For any type of measurement, describe the animals that were selected for analysis and the number of samples.  
> If necessary, include separate README files for each experiment type (measured data type). For example, a separate README file for Imaging experiments and a separate README file for gene expression experiments.  
> Describe measured techniques and the measured data. Some suggestions are described next. Feel free to include new sections or delete sections that are not applicable to your work: 


#### Treatments / Stimuli
> Describe any specific treatment or stimuli applied. For example:   
  - light or dark pulse stimulus  
  - heat or cold stimulus  
  - UV stimulus  
  - mechanical disturbance stimulus  
  - phase-shifting   
  - changes in feeding time or food type  
  - social isolation  
  - pharmacological treatments (drug name, concentration, brand and identifier number)  
  - timing and duration of interventions - **use Zeitgeber time (ZT)**  

#### Live activity monitoring
> Describe the activity monitoring system. Typical descriptions include:
  - Developmental stage and sex of monitored animals, as well as growth conditions if different that what has been described before. 
  - Monitoring system used (e.g., infrared motion sensors, infrared camera, video recording, videotracking (ViewPoint ZebraBoxes), etc.)
  - How data was recorded 
  - Duration of recording, and fish maintenance during recording
  - Software name and version used in activity data analysis
  
#### Spawning 
> Describe how spawning was analysed. 
  - describe any specific apparatus used (e.g., specific tanks used as spawning boxes).  
  - number of males and females involved and their developmental stage
  - water quality and temperature during analysis
  - photoperiod (e.g., 14:10 light-dark cycles) and light intensity
  - describe how spawning was recorded and how the eggs were counted (include any software used and its version) 
   
#### Sample preparation
> When the experiment involves euthanasia and sample preparation, include: 
   - Animals selected for euthanasia (sex, developmental stage)
   - Time when animals were euthanized
   - Euthanasia method (e.g., ice water or chemical)
   - Sample collected from fish - 
   - Sample preparation protocol
   - Number of biological samples analysed

#### Imaging
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

### Data analysis
> Describe how the data was analysed including any software used and its version.  
> Include any data processing (detrending, smoothing, averaging, etc).
> Describe any statistical analysis.
> Describe the methods used for period and phase analysis.   
     
## Dataset usage and access section

### Usage Instructions 
> Include guidelines for reproducing or reusing the data or to open specific file formats. 

### Citing the Dataset
> Provide citation details.

