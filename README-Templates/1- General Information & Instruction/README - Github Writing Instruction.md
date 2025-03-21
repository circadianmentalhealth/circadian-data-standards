## Where to Place the README File
Place the README.md or README.txt file in the root directory of your project, whether it's on GitHub or in another research data repository.  
If prior to data sharing, place it alongside your dataset in your working directory.  
Ensure it is the first thing users see when they visit your repository.

---

# Writing Language of READMEs in markdown format

## Markdown Basics for Writing READMEs
Markdown is a lightweight markup language that makes it easy to create structured and visually appealing README files on GitHub. Other platforms such as Zenodo can also render .md files in their file preview, diplaying the formatted content. 
Here’s how to use it:

---

### 1. Headings
Use headings to organize your content into sections.
Markdown Syntax	Output Example
# Title	
(# Title: you will use one # to write the title in the shape, font and size that is seen before the cautation)
## Section	
(## # Title: you will use two # to write the section's title in the shape, font and size that is seen before the cautation)
### Subsection	
(### Subsection: you will use three # to write the subsection#s title in the shape, font and size that is seen before the cautation)

Example:
# My Dataset  
## Dataset Description  
### Variables and Units  

---
### 2. Text Formatting
Make your text stand out using bold, italics, or inline code.

*italic* or _italic_	(use * or _ before and after the word/sentence to write in italic)

**bold**	(use ** before and after the word/sentence to write in bold)

`inline code`	(use ` before and after the word/sentence to write in inline code)

---
### 3. Lists
Organize information with bullet points or numbered lists.

**Unordered list**

if the writing way is : 

![image](https://github.com/user-attachments/assets/a8d366db-613b-4caa-a0fc-4e91611079e7)

the output will be: 

Unordered Lists
- Item 1  
- Item 2  
  - Subitem 2.1

**Ordered Lists**

if the writing way is:

![image](https://github.com/user-attachments/assets/1127a778-54aa-4d06-932a-9faa2d81a4a3)

the output will be: 

Ordered List
1. Step 1  
2. Step 2  
   1. Substep 2.1  

---
### 4. Links
Add clickable links to external resources or other sections.

if the writing way is: 

![image](https://github.com/user-attachments/assets/d63372be-85af-40ac-ac4f-5bf95a4bd0ec)

the output will be:

[Text](https://example.com)	Text
[Section Link](#section-name)	Section Link

So what between the [] is teh text that you want people to click to go to the needed website or section, while what between () is the link/url or section name after a #, and there should not be any space in between.

---
### 5. Tables
Use tables to present data dictionaries or comparisons.

if the writing way is:

![image](https://github.com/user-attachments/assets/fde9ff7e-e7a4-4809-9790-9d8b07ddcfeb)


the output will be:

| **Variable**    | **Description**                | **Type**   |  
|------------------|--------------------------------|------------|  
| `participant_id` | Unique ID for participants    | Categorical |  
| `age`            | Age in years                 | Numeric     |  

---
### 6. Code Blocks
Use code blocks for scripts, commands, or example code.

Inline Code: Use backticks; (`) at the begining of the code and another one at the end of it

fo example 
` Run the following command to install dependencies:  install.packages() `

---

### 7. Images
Include images for better visualization.

if the writing way is:

![image](https://github.com/user-attachments/assets/4f01da78-0a94-4c5a-9b68-ff334b189bd5)
 
the image will be uploaded

![Sleep Data Visualization](https://example.com/sleep-data-graph.png)  

---

### 8. Blockquotes
Use blockquotes for notes, warnings, or highlights.

if the writing way is:

![image](https://github.com/user-attachments/assets/818fb0ef-2dd6-45b8-8557-1c8cad567900)

the output will be:

> Note: Missing values were handled using mean substitution.  

---
### 9. Horizontal Lines
Separate sections with horizontal lines, by writing this dash - three times. The horizontal line will appear as the one after this section

---

### 10. Checklist
Create interactive checklists for tasks or required steps.

if the writing way of the checklist is like this: 

![image](https://github.com/user-attachments/assets/1f69aede-e85f-4c7e-86a2-5bd7eea0a016)

the output will be:

- [ ] Step 1: Load the data  
- [x] Step 2: Clean the data (Completed)  
- [ ] Step 3: Run the analysis  

---
The example below could be encoded using the proposed format as:
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


