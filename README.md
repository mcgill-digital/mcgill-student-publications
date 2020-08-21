# McGill Student Publications

## GENERAL INFORMATION

1. **Title of Dataset:** McGill Student Publications Data Set
2. **Source (URL):** [https://archive.org/details/mcgilluniversitystudentpublications](https://archive.org/details/mcgilluniversitystudentpublications) 
3. **Type of files:** .txt
4. **Date of data collection/extraction:** 2020-07 – 2020-08 

## DATASET/COLLECTION DESCRIPTION

The current data set includes full text files of the OCR’d text from the full run of the student-run publications McGill University Gazette (1874-1890)
and McGill Fortnightly (1892-1896). Digital copies of the full corpus of the McGill Student Publications are available in McGill Student Publications Collection 
in the Internet Archive.  A list of the issues with links to the scan of each issue is available for the Gazette at: http://www.library.mcgill.ca/hostedjournals/mcgill_university_gazette.html  
and the Fortnightly at: http://www.library.mcgill.ca/hostedjournals/mcgill_fortnightly.html. We plan to add .txt files for the remainder of the publications 
in the collection to this repository in due course.  The physical collection is housed in the McGill University Archives. 

## SHARING/ACCESS INFORMATION

5. **Licenses/restrictions placed on the data:** 
McGill Gazette and Fortnightly: [Public domain](https://creativecommons.org/publicdomain/mark/1.0/) 

6. **Usage Statement** We are making these files available on the condition that user credit the McGill University Library and Archives when using or 
reproducing them in any context. Giving credit promotes good scholarship, and helps others find the original source material. 

7. **Recommended citation for this dataset:** McGill University Library (2020). McGill Student Publications (Gazette and Fortnightly) Data Set. V1.
[Derivative dataset for McGill Student Publications Collection]. Physical collection held in McGill University Archives. https://github.com/mcgill-digital/mcgill-student-publications


## DATA &amp; FILE OVERVIEW

8. **File List:**
The subdirectory for each publication contains one folder for each issue of the publication, with one .txt file inside. 
As such, McGillLibrary-university-gazette contains 107 files and mcgill-fortnightly contains 64 files. 

9. **File naming conventions:**
The file names for the Gazette reflect publication name, volume and issue number,  and date of publication. The final number refers to the inhouse database used to track digitization activity (DPD ID).

Djvu indicates that the original scanned document was stored in a DjVu file format.
  e.g. mcgill-university-gazette-v07-n01-november-1-1883_djvu.txt
  
The file names for the Fortnightly reflect only the DPD ID for each issue and the original DjVu file format.
  e.g. 125835_djvu.txt 


## METHODOLGICAL INFORMATION

10. **Description of methods used for collection/generation of data:** These files were extracted using the Internet Archive’s Python library
