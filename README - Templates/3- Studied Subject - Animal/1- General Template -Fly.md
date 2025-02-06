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
> -Species;  
> -Strains used;  
> -Age / developmental stage;  
> -Sex;  
> -If experiments were done in vivo / Ex vivo / In vitro;  
> -Sample type: Whole fly / organ / tissues/ cells / extracts. 

## Husbandry 
> Describe how flies were cultured.  
> Include temperature, humidity, diet, housing.
> When applicable, include the time when food was offered

## Entrainment
> Describe light/dark cycles.  
e.g., *Newly eclosed males were collected and entrained 4 to 7 days in a 12-h:12-h light:dark (LD) cycle*

## Experimental design
>Here you will describe your experimental design. Some suggestions based on typical circadian experiments are added below.  

### Sleep measurement
> Describe the monitoring system and how fly activity was measured.  
e.g., *"Individual flies were placed into approximately 65 mm tubes, which were then placed into Trikinetics Drosophila Activity Monitoring System (www.Trikinetics.com, Waltham, Massachusetts)"*  
> Refer to images taken of the device used that are present in the dataset.  
> Describe how sleep was defined (e.g, *"sleep was defined as periods of quiescence lasting 5 min or longer"*.    

### Stimuli
> Describe any type of stimuli such as vibration, light, olfactory, touch, hot or cold temperature, sound, electrical etc.  
> Describe any type of deprivation applied such as food, water, rest, sleep, mobility, etc.  
> Add the timing (ZT) and duration of stimuli, as well as to which individuals it was applied. 


### Mating
> Describe mating experiments such as mating success or mating competition.
> Add number of individuals of each sex involved, developmental stage and time (ZT).
> Add how mating success or competition was measured.

## Measurements
> For any type of measurement, describe when and which flies were collected, which parts were dissected for analysis and the number of samples. Separate README files with more details can be included with each data type. For example, a separate README file for Imaging experiments and a separate README file for gene expression experiments.  

### Imaging
> Include links to protocols and a description of sample preparation and mounting for imaging.   
> Include microscopy or any other imaging system details such as name of equipment, filters used, magnification, etc.  

### Gene expression / Immunocytochemistry / Transcriptomics or other   
> Include all details necessary to reproduce the data. This might include links to external protocols.    
> See [Gene expression omnibus guidelines](https://www.ncbi.nlm.nih.gov/geo/info/MIAME.html) for data submission, where they describe critical elements to include in datasets

### Measured data
Activity

### Measurement technique
Infrared beam (TriKinetics)


### Measured data
RNA levels in R5 neurons

## Measurement technique
Fluorescence activated cell sorting and RNA-seq
