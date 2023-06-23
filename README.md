# Circadian Data Standards
Standards for data collection, data curation and data sharing in chronobiology

This project is dedicated to setting standards for data collection, data curation, and data sharing in chronobiology. 
It has been conceived as part of the MRC funded [Circadian Mental Health Network](https://www.circadianmentalhealth.org).

We are still in the initial stage of this project and we would greatly appreciate your feedback, comments, or suggestions for the proposed work. 
Please use GitHub [issues](https://github.com/circadianmentalhealth/circadian-data-standards/issues) to share your thoughts. We have already created a few entries to initiate discussions about our approach and proposed work.  
- [Using templates for dataset descriptions](https://github.com/circadianmentalhealth/circadian-data-standards/issues/1)
- [Multiple templates](https://github.com/circadianmentalhealth/circadian-data-standards/issues/2)
- [Prioritize actions](https://github.com/circadianmentalhealth/circadian-data-standards/issues/3)
- [Examples of published but not avialable (raw)data](https://github.com/circadianmentalhealth/circadian-data-standards/issues/4)

Feel free to add your own comments or start a new thread.

## Proposed work:

1. Agile development: To prevent the neglect of the developed recommendations/standards, we will work in an agile manner, generating actionable recommendations frequently and rapidly. These recommendations should be easily incorporated into current workflows and software infrastructure.

2. Metadata focused on reuse: We believe that the existing minimal information guidelines primarily focus on the technical aspects of measurement and data reproducibility, 
rather than on the reuse of generated output. For example, MIQE covers aspects such as standard curves, 
thermocycling parameters, or buffers, but it only includes "Definition of experimental and control groups" for the biological context. 
Therefore, we will provide guidelines and examples for reporting the biological and environmental context of datasets, such as how to report light and temperature entrainment or drug interventions during experiments.

3. Utilization of README templates: We propose using simple README templates in a human-readable format, such as plain text, to capture the required metadata.
Researchers can easily understand and complete the templates without specialized technical knowledge or tools. README templates can seamlessly integrate into existing data organization practices and repositories, accommodating various needs and contextual information. 
The flexibility of README files, combined with version control systems, allows for collaborative and iterative changes to the metadata. 
README documents retain their value regardless of the target data repository, whether it is a generic data-agnostic one like Zenodo or Figshare, or a domain-specific one like [BioDare2](https://biodare2.ed.ac.uk/). 
Researchers can tailor the template to their specific needs and contextual information. This adaptability allows for capturing a wide range of metadata elements without being constrained by a rigid structure.

5. Tailored templates: Instead of developing a single comprehensive template, we suggest creating multiple templates tailored to specific organisms and experimental techniques. 
This approach will make the documents easier to use, as they will contain only relevant sections. 
It also addresses the issue of different terminology used in human and model organism data. For example, "cohorts" vs "biological replicates" or "demographics" vs "genotypes."

6. Syntax for automatic parsing and validation: While simple README templates offer advantages, we acknowledge the importance of machine-readability and interoperability. 
Therefore, we propose using a syntax that enables automatic parsing and validation of the text documents. This ensures compatibility with evolving data standards and facilitates potential conversion to more formal structures (such as JSON or XML) if necessary.

7. Collaboration with [Metadata4Wearables](https://github.com/Metadata4Wearables): We plan to collaborate with the Metadata4Wearables community, 
which focuses on standardizing actigraphy and light exposure data using JSON schemas. 
This collaboration will ensure compatibility and complementarity between our ongoing initiatives.

Future plans for standardization include:

- Recommending circadian variables for routine use.
- Recommending analysis methods for estimating these variables.
- Indicating suitable ontologies or closed vocabularies for unambiguous descriptions.

## Maintainers
* Tomasz Zieliński ORCID: [0000-0002-0194-5706](https://orcid.org/0000-0002-0194-5706) tomasz.zielinski [@] ed.ac.uk
* Andrew Millar ORCID: [0000-0003-1756-3654](https://orcid.org/0000-0003-1756-3654)
* James Hodge ORCID: [0000-0003-4741-2363](https://orcid.org/0000-0003-4741-2363)

