# DukeOIT-clinical-notes


This project aims to make use of Natural Language Processing techniques to take Electronic Health Records and translate them into a set of features fit for prediction in order to more efficiently and more accurately track the progress of medical students.

The formal write-up containing more details about our methodology can be found in the file titled "report.pdf".

## A. Data:    
ALL DATA IN THIS REPO IS FAKE. We made a generator (code/fake_notes_generator.ipynb) to create notes that are free of sensitve information, yet maintain proper clinical note structure so the code found in this repo can be demonstrated

## B. Code:
The code files in this repo are pieces of the following pipeline.

1.  fake_notes_generator.ipynb
        This file generates a csv of fake notes to run the rest of the code on, 
        complete with all of the same columns we had in our real data.
        Output: fake_notes.csv
        A version of this notebook's output can be found in the "data" directory.

2.  labeling.ipynb
        This file takes in the fake_notes.csv and condenses three features: "admission_service", "title" and "specialty" into one,          called  "type".
        Output: fake_notes_labeled.csv
3. soap_extract.ipynb
            Output: fake_notes_extracted.csv
4. entity.....

