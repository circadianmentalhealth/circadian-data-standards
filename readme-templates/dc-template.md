# Title: Type in the title/name
> -> http://purl.org/dc/terms/title  
> A descriptive name given to the dataset.


## Identifier: YourID
> -> http://purl.org/dc/terms/identifier  
> An unambiguous and internal reference to the dataset within the context of its creators.  
> For example, experiment id or name of a folder containing data

## Date: YYYY-MM-DD
> -> http://purl.org/dc/terms/date  
> A point in time associated with the lifecycle of the dataset.  
> Used mainly to cross-reference with other resources like Lab Notebooks or raw data.  
> Date must be expressed in ISO format: **YYYY-MM-DD** (e.g 2023-03-25)  

## Purpose (Research Hypothesis)
> -> http://purl.obolibrary.org/obo/NCIT_C146997
> -> http://purl.obolibrary.org/obo/NCIT_C142668  
> The overall rationale, reason, or intention for conducting a study that resulted in the the data set.   
> Or the hypothesis that a study sets out to support (or disprove);

## Abstract
> -> http://purl.org/dc/terms/abstract  
> A summary of the content of the dataset.  
> Should include a brief information about the biological material, technique used
> and measurement/experimental conditions. 
> The comprehensives details are to be recorded in sections bellow, here, 
> we expect a short description that helps to understand the content of the dataset without its thorough examination.

## Contributor
> -> http://purl.org/dc/terms/contributor  
> List of persons making contribution to the creation of the dataset.  
> We recommend to include: technicians, experimentalists, statistician / data analysts, curators and supervisors
> Use `FirstName LastName` format, each contributor name should be in a separate line which starts with `-`.  
> See the example entry bellow
- Ana Student
- Tom Thorough
- Diana Helpful


## Bibliographic Citation
> -> http://purl.org/dc/terms/bibliographicCitation  
> If part of a publication the bibliographic details to identify the paper

## Entrainment
> -> http://purl.obolibrary.org/obo/GO_0009649  
> The synchronization of a circadian rhythm to environmental time cues such as light.

### Locomotor activity
> -> http://purl.obolibrary.org/obo/GO_0045475  
> The locomotor activity of an organism during its activity cycle.



### Event
> -> http://rs.tdwg.org/dwc/terms/Event  
> An action that occurs at some location during some time.

### MeasurementOrFact
> -> http://rs.tdwg.org/dwc/terms/MeasurementOrFact  
> A measurement of or fact about an rdfs:Resource


## Husbandry (Cultivation)
> -> http://purl.bioontology.org/ontology/MESH/D000822  
> Care and cultivation of test subject organisms before the experiment  
>
Flies were maintained on a media of sucrose, yeast, molasses, and agar under 12:12 LD cycles at 25 °C. One- to 3-day-old female flies were separated and maintained on standard cornmeal-yeast medium under LD12:12 cycles at 25 °C for 4 nights before experiments began.  


Fig1,F2,F3

## Experiment design
> -> http://purl.obolibrary.org/obo/NCIT_C15320
> A plan detailing how a study will be performed in order to represent the phenomenon under examination or to answer the research questions that have been asked.
> Plan should include
> - choice of interventions
> - timing of interventions
> - entrainment conditions prior and during measurement, eg free running, LD... 
> - environmental variables that typically influence clock like Light, Temperature, Feeding
> 
Flies were transferred into capillary tubes (containing sucrose-agar food) and loaded into Drosophila activity monitor (DAM) system.
They were kept in LD12:12 cycles at 25 °C. On the 3rd day test flies were subjected to sleep deprivation for 2.5 hours.  

## Protocols
- forced desynchrony protocol: this 2.5 hr stimulus was repeated every 7 hr
(allowing for a total of 4.5 hr of rest following each stimulus) 24 times until SD occurred at each hour around the clock.   
- abridged protocol: this 2.5 hr stimulus was applied 5 times: ZT0, ZT8 and ZT23 of day 3, ZT7 of day 4 and ZT6 of day 5.
- in DD protocol: sleep deprivation was applied at ZT 2.5 and ZT 10.5 under constant dark

## Control
> ->http://purl.bioontology.org/ontology/MESH/D035061  
> Groups that serve as a standard for comparison in studies. They are similar in relevant characteristics to the experimental groups 
> but do not receive the experimental intervention.
>
Undisturbed flies

## Interventions
> -> http://purl.obolibrary.org/obo/ERO_0000347  
> A process used to influence one or more factors in a research study.  
> Typical examples are light pulses, stress induction, drug treatments, activation of signalling pathways
>
- Sleep deprivation (SD): A 2 s vibration stimulus was applied approximately every 20 s with a randomized protocol for a time period of 2.5 hr using vortexer

## Measured data
> -> http://edamontology.org/data_3108  
> -> http://purl.bioontology.org/ontology/SNOMEDCT/122869004
> 
Activity

?Where to put:
All behavioral data consist of pooled data from multiple runs with independent samples.

## Measurement technique
> -> http://purl.bioontology.org/ontology/SNOMEDCT/272391002  
>
Infrared beam (TriKinetics)

## Derived data
> -> http://ncicb.nci.nih.gov/xml/owl/EVS/Thesaurus.owl#C41091  
> 
- Sleep: Activity was measured in 1 min bins and sleep was identified as 5 min of inactivity (Hendricks et al., 2000).
- Sleep lost: is determined by the difference between baseline sleep and sleep during the sleep depravation
- Sleep gain: Calculated as the difference between sleep during rebound and sleep during the equivalent 4.5 hr at baseline.

F8

## Measured data
RNA levels in R5 neurons

## Measurement technique
Fluorescence activated cell sorting and RNA-seq

## Derived data
Differential expression

## Measurement details? / Samples preparation
Fluorescence activated cell sorting and RNA-seq
Immediately following SD the flies were transfered into CO2 pads and brains were dissected in medium blocking neuronal activity. 40–45 brains per time point were pooled as a single sample and every condition and time point was run in triplicate for a total of twelve samples. Following papain digestion samples were transferred to the Northwestern FACS core on ice. GFP-positive cells were sorted on an Aria II FACS Cell Sorter. 300–550 cells per sample were obtained, lysed and used for library preparation. 

See RNA extraction protocol.

Reads were pseudo aligned and quantified using Kallisto (v0.46.1) (Bray et al., 2016) against a prebuilt index file constructed from Ensembl reference transcriptomes (v96). Kallisto was used to process paired end reads with 10 bootstraps. Differential expression analysis of the resulting abundance estimate data was then performed with Sleuth (v0.30.0; Pimentel et al., 2017). 

## Measured data
BRP protein levels


## Measurement technique
Immunostaining 

## Measured data
Intracellular Ca2+

## Measurement technique
???Confocal with Tags???

## Biology

### Lines

name: phenotype / function
