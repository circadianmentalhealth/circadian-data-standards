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

 |--`N_crassa_luciferase_assay/`       
 |  |--`mutant_period_analysis.csv`          
 |  |--`mutant_raw_data.csv`  
 |  |--`wt_period_analysis.csv`  
 |  |--`wt_raw_data.csv`  
         
 |--`N_crassa_ChIP_GO_analysis/`    
 |  |--`Gene1_ChIP_seq_targets.tsv`  
 |  |--`Gene1_GO_analysis.tsv` 
 
      
# Methodological information 

## Biosample description
> Description of biological entity that was monitored / measured/ experimented on.    
> Typical content will have information about:
 - Plant species;  
 - Genotypes used 
     - include designations (e.g., *wt*, *mutant_name*) and unique identifiers when applicable.  
     - Provenance of genotypes / lines. If new genotypes were generated, plant transformtion method.
- Plant material analysed (e.g., whole seedling, root, 3rd leaf, etc.)
- Developmental stage analysed (e.g., 20-30 days after germination) 
   
## Growth conditions
> Describe the growth conditions. 
> Differentiate Control condition from Treatment conditions when applicable. 
> Typical descriptions will include:
  - Stratification and seed germination process
  - Type of growth media if in vitro, including pH and agar concentration.
  - When a hydroponic system was used, add a description or link for the system, and include content of hydroponic culture solution.  
  - Type of substrate used if plants were grown in pots and the corresponding manufacturer (e.g., rockwool, peat based soil mix, vermiculite, etc.)
  - Watering and soil supplementation (if plants were watered with water only, or any liquid media or fertilizer were added and the frequency of watering/ supplementation) 
  - Growth temperature
  - Incubator used (e.g., Percival)
  - Entrainment: add light/dark cycles and temperature where seedlings were entrained. Include light intensity (μmol m−2 s−1 ) when applicable.
  - Light/dark conditions and temperature during analysis if different from entraining 

## Experimental design and conditions
> Here you will describe your experimental design. 
> For any type of measurement, cite the genotypes used for analysis and the number of replicates used.  
> If necessary, include separate README files for each experiment type (measured data type). For example, a separate README file for Luciferase assay and a separate README file for transcritomics data.  
> Describe measured techniques and the measured data. Some suggestions are described next. Feel free to include new sections or delete sections that are not applicable to your work: 

### Treatments / Stimuli
> Describe any specific treatment or stimuli applied. For example:   
  - light or dark pulse stimulus;
  - increased light intensity
  - heat or cold stimulus;
  - media / soil supplementation (e.g., added nitrate, glucose, etc)
  - chemical treatments (drug name, concentration, brand and identifier number) 
  - timing and duration of interventions - **use Zeitgeber time (ZT)**

### Luciferase assay
> Describe the Luciferase assay.
  - Plates used.  
  - Growth medium.  
  - Medium supplementation including Luciferin. Add concentration and provenance of chemicals (e.g., 25 μM firefly luciferin (LUCNA-300; Gold Biotechnology, St. Louis, MO).  
  - Origin of inoculum.
  - Light/ dark and temperature conditions during experiment
  - Equipment and software used for bioluminescence measurements
  - Periodicity and duration of measurements (e.g., recordings were taken every 60 min over 5 days)
   
### Protein / Transcriptomics / ChIP-seq analysis etc
> Describe throughly any other analysis such RNA sequencing, ChIP-seq, RT-qPCR, metabolomics etc. For example:  
> - Include detailed protocols for DNA/ RNA / protein extraction  
> - Include detailed protocols for library sequencing  
> - Include all primers used and gene expression analysis protocol
> - Number of biological replicates
> If protocols are described in detail elsewhere, include the link to them (preferably a DOI when possible).
> Some minimum reporting and information standards are available for consultation when describing such experiments. For example:  
> 
> **ChIP-seq**  
> - [ChIP-seq guidelines and practices of the ENCODE and modENCODE consortia](https://doi.org/10.1101/gr.136184.111) 
>
>  **High-throughput nucleotide SEQuencing Experiment**    
> - [MINSEQE describes the Minimum Information about a high-throughput nucleotide SEQuencing Experiment](https://doi.org/10.5281/zenodo.5706412)
>
> **RT-qPCR**  
> - [Minimum Information for Publication of Quantitative Real-Time PCR Experiments](https://doi.org/10.1373/clinchem.2008.112797)
>
> **Metabolomics**  
> - [Proposed minimum reporting standards for chemical analysis Chemical Analysis Working Group (CAWG) Metabolomics Standards](https://doi.org/10.1007/s11306-007-0082-2)

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

