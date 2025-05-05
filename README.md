# ML_readability
Capstone Project for Masters in CL: Readability Assessment and Resource Generation for Multilingual Learners of English

This is a random forest classifier for English-language texts. Its primary function is readability assessment. However, it differs from most formulas in that the output is an English Language Development level ("Beginner", "Intermediate", or "Advanced") rather than a grade level.

This tool takes an English-language text as input and outputs and ELD level as well as lists of cognates and academic vocabulary. Cognates lists are available for Spanish, French, Haitian Creole, and Portuguese. Academic word lists come from eapfoundation dot com, via the compleat lexical tutor.

Main Files:
capstone_compleat.ipynb
This file contains the bulk of the project, including the functions for feature extraction, training, and analysis.

capstone_functional.ipynb
This file is a streamlined version of the project, which operates on a .txt file and generates a .txt file as output.

Support Files:
cognates_final.csv
This file contains lists of approximately 1500 cognates each for English-Spanish, English-French, English-Haitian Creole, and English-Portuguese.
eap_asl.csv
This file contains the academic word list from eapfoundation.com, with inflected forms and head-words.
eap_gsl.csv
This file contains the general service word list from eapfoundation.com, with relative frequency values.
longman_final.csv
This file contains the relative frequency values of words in the "longman communication 3000." Double weight is given to the written corpus.
classifier_v4.joblib
This file contains the values of the trained random forest model.
