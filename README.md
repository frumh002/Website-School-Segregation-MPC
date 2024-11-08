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
- Sequence index of segregation? Impute a sequence to gauge clustering?

PELSB outcomes:
- average years of teacher experience
- new teacher
- proportion of teachers in Experience 1 to 5 years
- proportion without a graduate degree (group BA and less than BA and unknown and group Masters and PhD)
- average age of teacher
- proportion of teachers less than 30 vs. greater than 30

- Math and Reading for 3rd, 7th, 11th

- four year graduation percent
- four year dropout percent

- Integration 

- What does the four year graduation rate mean? The proportion of students
- does graduation rate correlate with droupout rate
No - someone could have graduated, dropped out, or been held back?
- correlation matrix among all variables



*This repo was initially generated from a Quarto template available here: https://github.com/jtr13/website-template.*

