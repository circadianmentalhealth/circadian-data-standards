## Draft templates

README templates for datasets descriptions.

## Format description

In general, a metadata description of a dataset can be viewed as a collection of key-value pairs,
for example:

* title : Effect of chronotype on localization
* authors: John Smith, Su Key, Fiona Arias
* description: 
Activity of fruit flies of 4 genotypes: WT, CRY, GAL4, KIR was monitored using video tracking software.  
The selected genotypes were supposed to mimic various chronotypes: control, arythmic, early birds and night olws.  
Flies were entrained and monitored under cyclic light conditions: normal LD12:12, short days LD6:18 and long days LD18:6. 
* start date: 25.06.2023

the keys values are:
* `title` is a key and its value is the text *"Effect of chronotype on localization"*
* `authors` is a key and its value is a list of 3 names
* `description` is a key and its value is multine string
* `start date` is a key and its value is the date 25th June 2023

At this stage of the standardization project we do not know all the relevant keys for the data descriptions.
For that reason we propose a format which can be automatically parsed into key-values without specifying what the keys are.

Rules:
* Each key is marked with `#` sign(s) at the start of the line. 
* The key name is the text between `#` sign(s) and end of the line or `:` sign if present
* The key name is not case sensitive
* The key value is composed from all the text after the key name up to the next key or end of file.  
That means that if the key ends with `:` the key value can be recorded in the same line as the key,  
otherwise the value starts in the new line. 
* Lines that starts with `>` contain comments and are to be ignored
* For the list of values, each value is recorded in separate line which starts with `-`
* For increased readibility the keys-value pairs should be separated by an empty line  
(ie there should be empty line before each `#` openning sign.

Parsing files that follow this convention is straightforward, but at the same time permits capture of multi line text values
as well as list of values.

This format is *markdown-friendly* in the sense that it can be pretty-printed rendered by markdown viewers.
Each key will be rendered as a header. The key value will be rendered bellow the key or following it if the key ends with `:`.
The list of values are rendered as lists. And the comments are shown as blockquotes, clearly distinguishing them from keys and values.
Users familliar with markdown can still use the additional simple formatting available in markdown (like line breaks, italic and bold font).

At the same time the documents are easily readable as plain text, with clear separation between keys and values.

The example above could be encoded using the proposed format as:
```
## Title: Effect of chronotype on localization

### Authors 
- John Smith
- Su Key
- Fiona Arias

### Description 
Activity of fruit flies of 4 genotypes: **WT, CRY, GAL4, KIR** was monitored using video tracking software.  
The selected genotypes were supposed to mimic various chronotypes: control, arythmic, early birds and night olws.  
Flies were entrained and monitored under cyclic light conditions: 
normal **LD12:12**, short days **LD6:18** and long days **LD18:6**. 

### Start date: 2023-06-25
> Dates should be in the ISO format YYYY-MM-DD
```

Which is rendered as (for example if you see this file in github):

## Title: Effect of chronotype on localization
### Authors 
- John Smith
- Su Key
- Fiona Arias
### Description 
Activity of fruit flies of 4 genotypes: **WT, CRY, GAL4, KIR** was monitored using video tracking software.  
The selected genotypes were supposed to mimic various chronotypes: control, arythmic, early birds and night olws.  
Flies were entrained and monitored under cyclic light conditions: 
normal **LD12:12**, short days **LD6:18** and long days **LD18:6**. 
### Start date: 2023-06-25
> Dates should be in the ISO format YYYY-MM-DD


