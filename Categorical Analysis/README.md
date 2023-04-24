# Categorical Analysis
This folder consists of code and required data for categorical analysis of the code-switched data on the basis of following parameters:
1. Age
2. Gender
3. Relationship
4. Ethnicity
5. Education
6. Employment
7. Dominant Language 
8. First Language

**Library Required**
1. [Pandas](https://pandas.pydata.org/docs/getting_started/install.html)

This consists code for the following two tasks.
## Categorizing Data
    Firstly, we need to categorize our data on the basis of above mentioned parameters, below are the details of those categories.
    1. Age :
        18 to 30 years 
        31 to 45 years
        46 and more
    2. Gender: 
        Male
        Female
    3. Relationship:
        Family
        Friends
        Strangers
    4. Ethnicity:
        Malay
        Indian 
        Chinese
    5. Education:
        School
        Polytechnic
        University
    6. Employment
        Students
        Unemployed
        Employed
    7. Dominant language
        Malay
        English
        Other
    8. First Language
        Malay
        English
        Other

    "Categorizing_Data_of_NSC.ipynb" categorizes and merges all the text files on the basis of aforementioned parameters and saves it into the folders .

## Getting Stats
    "Getting_Stats_of_NSC_categories.ipynb" produces stats for every category and saves those results into "Results.xlsx"


Note: Before running these code, create the following folders in your directory:
1. Age
2. Gender
3. Relationship
4. Ethnicity
5. Education
6. Employment
7. Dominant_Language 
8. First_Language