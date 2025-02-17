# Title: Type in the title/name
> A descriptive name given to the dataset.

## Date: YYYY-MM-DD
> A point in time associated with the lifecycle of the dataset.  
> Used mainly to cross-reference with other resources like Lab Notebooks or raw data.  
> Date must be expressed in ISO format: **YYYY-MM-DD** (e.g 2023-03-25)  

## Purpose (Research Hypothesis)
> The overal rationale, reason, or intention for conducting a study that resulted in the the data set.   
> Or the hypothesis that a study sets out to support (or disprove);

## Abstract
> A summary of the content of the dataset.  
> Should include a brief information about the biological material, technique used and measurement/experimental conditions. 
> The comprehensives details are to be recorded in sections below. Here we expect a short description that helps to understand the content of the dataset without its thorough examination.

## Contributors
> List of persons making contribution to the creation of the dataset.  
> Use `FirstName LastName` format, each contributor name should be in a separate line which starts with `-`.  
> See the example entry bellow
- Ana Student
- Tom Thorough
- Diana Helpful

## Biosample
> Description of biological entity that was monitored / measured/ experimented on.    
> Typical content will have information about:
>
 -Species;  
 -Strains used;  
 -Age / developmental stage - standard terms for describing drosophila developmental stages can be found [here](https://bioportal.bioontology.org/ontologies/FB-DV?p=classes)  
 -Sex;  
 -If experiments were done in vivo / Ex vivo / In vitro;  
 -Sample type: Whole fly / organ / tissues/ cells / extracts. 

## Husbandry 
> Describe the conditions where the animals were grown. Typical descriptions will include:  
  - Feeding: type of diet / time when food was offered
  - Housing: apparatus dimensions, material.
    - Temperature
    - Humidity
    - Light intensity
    - Type of light (fluorescent, LED panel, colour temperature, etc)
    - Entrainment: describe light/dark cycles e.g., *Newly eclosed males were collected and entrained 4 to 7 days in a 12-h:12-h light:dark (LD) cycle*
    
## Experimental design and conditions
> Here you will describe your experimental design. For example, if flies were divided in different groups and the treatments applied to which group. Some suggestions are described next.   

### Stimuli
> Describe any type of stimuli such as vibration, light, olfactory, touch, hot or cold temperature, sound, electrical etc.  
> Describe any type of deprivation applied such as food, water, rest, sleep, mobility, etc.
> Add the timing (ZT) and duration of stimuli, as well as to which individuals it was applied and when.  

### Mating
> Describe mating experiments such as mating success or mating competition.
 - number of individuals of each sex involved
 - developmental stage 
 - time (ZT).
> Add how mating success or competition was measured.

## Measurements
> For any type of measurement, describe when and which flies were collected, which parts were dissected for analysis and the number of samples.
> If necessary, include separate README files for each data type. For example, a separate README file for Imaging experiments and a separate README file for gene expression experiments.
> Describe measured techniques and the measured data. Some suggestions are described next: 

### Sleep measurement / activity monitoring
> Describe the monitoring system and how fly activity was measured.  
e.g., *"Individual flies were placed into approximately 65 mm tubes, which were then placed into Trikinetics Drosophila Activity Monitoring System (www.Trikinetics.com, Waltham, Massachusetts)"*  
> Refer to images taken of the device used that are present in the dataset.  
> Describe how sleep was defined (e.g., *"sleep was defined as periods of quiescence lasting 5 min or longer"*).    

### Imaging
> Include links to protocols and a description of sample preparation and mounting for imaging.
> Describe the biosample collected for imaging if different from general biosample description above. 
> Image acquisition: 
  - Instrument
  - Image acquisition parameters (filters used, magnification, etc.)
> Image data:
  - Describe if you are sharing raw, processed, and/or segmented images.
  - File formats
  - Image dimensions
  - Channel information
  - Image processing methodology

### Video recording
 - Type of camera and where it was placed in housing.
 - How many frames per second (FPS)
 - How long animals were recorded
 - Time of recording (ZT)
   
### Gene expression / Immunocytochemistry / Transcriptomics or other   
> Include all details necessary to reproduce the data. This might include links to external protocols.    
> See [Gene expression omnibus guidelines](https://www.ncbi.nlm.nih.gov/geo/info/MIAME.html) for data submission, where they describe critical elements to include in genomic datasets

