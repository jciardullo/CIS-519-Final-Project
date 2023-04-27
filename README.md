# CIS-519-Final-Project

## Setup/Build Instructions
To train a model, download the notebook corresponding to that model (ex. LR=logistic regression). We ran our notebooks in colab with a specific drive path.
In order to run the notebook: 
1. Import it into google colab
2. Set the variables in the first cell according to how you want to run the notebook
3. Change the "project_folder" variable to a existing directory in your drive
4. Execute
This process should work for every notebook.

## Files
Each notebook can load in, clean, tokenize/lemmatize the data, and prepare training/test datasets.
+ LR.ipynb: trains a Logistic Regression model
+ SVM.ipynb: trains a Support Vector Machine (specifically Linear Support Vector Classification)
+ BERT.ipynb: trains a Bidirectional Encoder Representations from Transformers model
