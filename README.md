# French bible
Parse french bible to test NLP stuff

## Goal

Parse large french text to extract places, people's names, gender and sentiment.  
Build meaningful graphs and create new text features.  
Extend and replace words or sentences in a realistic and controled way.  

## Folders

A quick description of each folder. 

### Notebooks

All notebooks are here. Also, the detailed research log is included,  
to get a quick chronological description of the goals and results of each notebook.  

### original epub

Contains the original epub (with the `.epub` extension changed to `.zip`), and the inflated files. 
Each bible page is a file, and they contain HTML tags. So the base dataset is actually collection of HTML pages. 

## .gitignore

Set to include datasets for now, as the base/raw datasets are included to start the project.  
Derived datasets (sentences, additional features, etc...) should NOT be included here.  
