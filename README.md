# NextGen_DataCleaning_Week1
# Week 1 - Applicant Dataset Cleaning (NextGen Learners Internship)

This repository contains the deliverables for **Week 1 of the NextGen Learners Internship Program**.  
The focus of this task was **data cleaning, wrangling, and exploration using Pandas** on a raw applicant dataset.


## Files Included
- **Week1_Data_Cleaning_Jamsad_Chowdhury.ipynb**  
  → Fully documented Jupyter/Colab notebook with code and markdown explanations.  
- **applicants_cleaned.csv**  
  → Final cleaned dataset after handling missing values, duplicates, inconsistent text, and wrong data types.  


## Task Objectives
- Practice **data cleaning** on real‑world messy data.  
- Learn to handle **missing values** column by column with justification.  
- Identify and remove **exact & near duplicates**.  
- Standardize **text fields** (Domain Applied, Status, Names).  
- Fix **data types** (Application Date → datetime, Phone → cleaned text).  
- Document every decision with **markdown explanations**.  
- Export and share the **cleaned dataset**.


## Tools & Libraries
- **Python 3.x**  
- **Pandas** (data cleaning & wrangling)  
- **Google Colab / Jupyter Notebook** (interactive environment)  


## Dataset Issues Found
- Missing values in Applicant Name, Email, University, Status.  
- Duplicate rows (same applicant multiple times).  
- Inconsistent casing/spelling in Domain Applied & Status.  
- Mixed date formats and invalid dates (`not-a-date`, `31/19/2026`).  
- Phone numbers with inconsistent spaces/dashes.  


## Cleaning Actions Taken
- Dropped rows with missing Applicant Name.  
- Filled missing Email with placeholder (`not_provided@example.com`).  
- Filled missing University with `"Not Specified"`.  
- Filled missing Status with `"Under Review"`.  
- Removed duplicates (exact + by Email).  
- Standardized Domain Applied into 5 categories:  
  `Web Development, App Development, Graphic Design, Digital Marketing, Data Science`.  
- Standardized Status values (`Selected, Under Review, Rejected`).  
- Converted Application Date to proper datetime format.  
- Cleaned Phone numbers to consistent digit strings.  


## Deliverables
1. `Week1_Data_Cleaning_YourName.ipynb` — documented notebook  
2. `applicants_cleaned.csv` — final cleaned dataset  
3. Both files uploaded in this GitHub repository  


## How to Reproduce
1. Clone this repository:
   ```bash
   git clone https://github.com/YourUsername/NextGen_DataCleaning_Week1.git
