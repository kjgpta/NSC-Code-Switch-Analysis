# Normalizing Data
This folder consists of code and required data for following three tasks.

## Converting Textgrid files to Text files 
    The data we receive from NSC Part-4 is in textgrid form and we need to convert it to text format, so that we could use it for further analysis.

    "Convert_Textgrid_to_text.ipynb" consists of a function "convert_to_text" which takes two input:
    1. Path of directory which consists TextGrid files
    2. Path of directory to which text files would be saved

    and converts all the textgrid files to text format.

## Merging Data
    Now, we have to merge all the text files so, that we could use the complete text file to use it for analysis.

    "Merge_Data.ipynb" merges all data in the folder named "Text"

## Cleaning Data
    Now, after merging text data, we need to clean the data because it contains several tags like <malay>, (ppo), (ppc), etc. The details can be found in "NSC_Transcription_Guidelines.pdf".
    So, we need to eliminate these tags and also, there are several utterances in the data which are monolingual and we need to eliminate those and focus only on analysis of only code-switched utterances in the data.

    "Data_Cleaner.ipynb" cleans the data and divide the data into monolingual and code-switched data and save it as "Only_English.txt", "Only_Malay.txt", "Only_CS.txt" in the same folder.

    This data can be used for further analysis.


Note: There are library requirements for all of these code. 