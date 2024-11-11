# Twin Cities School Sergregation Descriptive Report

It is coded in R and thus far uses the following datasets:
- Stanford NCES 1991-2022 Dataset (found here: )
- Stanford Segregation 1991-2022 Dataset (found here: https://edopportunity.org/segregation/data/downloads/#segregation-1)

Here is an overview of the structure of this project and the associated R scripts:
- Import and format NCES data (importnces.R)
- Build out the school segregation descriptive file (schoolsegbuild.R)
- School segregation descriptive analysis (schoolsegdesc.qmd)
- School segregation index analysis (schoolsegindex.qmd)
- Ecological analysis (ecological.qmd)
- Supplemental materials (suppmaterials.qmd)

School segregation is a district level measure, but we might need to use school-level % minority. Exposure to concentrated poverty as a measure. 

We have to prove one things to the court:
School segregation is a substantial factor in school/educational adequacy (the state has a duty to provide an adequate education). Adequacy is not defined per se. Adequacy: low test scores, poor outcomes (health, etc.), high school graduation rates.

National patterns vs. MN patterns of school segregation.

Can we replicate basic descriptive stats to see if MN operates similar to other cities? The same causal pathways exist in MN.

Within school districts, do schools significantly differ in our outcome measures as exposure to segregation (% BIPOC) increase (stratify by poverty proxy)?
- How does this same analysis compare to other metro cities in the US?

Tell the story of what happens when we segregate kids into schools. Fewer opportunities, fewer high level classes. Counterfactual set of districts that moved in a separate direction around the US.

School closures data. 

To do:
- Update the Isolation index thresholds (wht_non wht)
- Census CBSA and place==Minneapolis
- 1-year ACS estimates for 5-17 year olds from 2001-2022
- Explore Civil Rights Dataset and what shcools are there compared to metro overall, are they representative of the metro area?
- Add in difference of percent from mean for ecological analysis
- Update Racial Composition and Economic Segregation to filter by year (or maybe show the different correlation lines over time stacked)
- What does the four year graduation rate mean? The proportion of students
- N of schools and districts that are in the ecological plot (and percent of students - is there selection bias into this chart?)


*This repo was initially generated from a Quarto template available here: https://github.com/jtr13/website-template.*

