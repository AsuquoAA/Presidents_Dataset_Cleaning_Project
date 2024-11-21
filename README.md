# Presidents Dataset Cleaning Project

## Overview

My first ever data cleaning project; The Presidents Dataset Cleaning Project involves preparing a dataset containing information about various presidents, including their dates of birth, election, and departure from office, as well as their age and years lived after leaving office. The goal is to transform the raw dataset into a clean, structured, and analyzable format.

---


## Dependencies and Installations

To use this repository and run the notebooks, you will need to have Python and the following libraries installed:
1. Pandas
2. IDE: Jupyter Notebook for Interactive Analysis
- code: pip install pandas jupyter

Installation
To get started with this repository, clone it to your local machine:
- code: git clone https://github.com/Lazycodes/Applied_Data_Science_with_Python_Study.git
  
Navigating to directory
- code: cd Applied_Data_Science_with_Python_Study

---


## Dataset 
The following was the dataset used:
1. <a href="https://github.com/Lazycodes/First_Data_Cleaning/blob/main/presidents.csv">Presidents.csv</a>

The dataset includes the following details about presidents:

President: Full name of the president.
Born: The birth date of the president.
Age atstart of presidency: Age when the president was elected and date they entered.
Age atend of presidency: Age the president left office and date they left.
Post-presidencytimespan: The number of years the president lived after leaving office.
Died: The date of death of the president
Age: The age of the president at the time of their death.

---

## Cleaning Process
The cleaning process included but was not limited to:

1. Splitting the column to separate create more columns
2. Using regular expressions to extract (or clean) date and year patterns
3. Changing dates to datetime format 
4. Replacing column names

### Dataset features after cleaning

President: Full name of the president.
Born: The birth date of the president.
Start of Presidency: date president entered office
End of Presidency: date president left office
Years lived after Presidency: The number of years the president lived after leaving office.
Died: The date of death of the president
Age: Age of death of president
Firstname: First name of president
Lastname: Last name of president
Age at the start of Presidency: Age when the president was elected
Age at the end of Presidency: Age the president left office
Next_President_Start: Date next president assumes office

---


## Challenges Faced

1. Inconsistent Date Formats: Several entries had non-standard
2. Missing Data: Some presidents did not have DPost-presidencytimespan values.
3. Handling Living Presidents: Properly marking and imputing data for presidents still alive.

---


## Future Enhancements
1. Add visualizations to analyze trends (e.g., age at election, years in office).
2. Incorporate additional columns such as party affiliation or country for a global dataset.

---

## Acknowledgements
I would like to thank the University of Michigan and Coursera for providing the Applied Data Science with Python Specialization, which has been an invaluable resource for learning data science with Python, where I found this exercise.
