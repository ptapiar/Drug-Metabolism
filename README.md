# Drug Metabolism Predictor V1

The purpose of this project is to predict bacterial enzymes involved in drug metabolism. 
For this, we used machine learning and structural similarity search methods to develop the pipeline of the predictor.
We obtain a pipeline that allows to predict from a drug its metabolism based on gut microbiota from uBiome database. The pipeline consists on introducing a query drug or list of drugs in a SDF format (Structure Data Format) as input file.

With the predictor we can determine the bacterial enzymes involved on the metabolization of some drugs with a great precision. However, there are some drugs that cannot be determined because the initial dataset of substrates is very limited. 
Thereby, a second stage of predictor is necessary to improve the initial dataset.


## Requirements:
- Install Open Babel
- Install R
- Download script folder 'Drug-Metabolism-Predictor': https://drive.google.com/drive/folders/1_68YvG_yFzVks-Lm_Qxr4BXIsTPMOdMy


## How to use:
 1) Download the query molecules as SDF format (PubChem)
 2) Modify the directories input parameters on run-predictor.sh file.
 3) To run: sh run-predictor.sh

## Test example 
   Download 'Test-files' folder: https://drive.google.com/drive/folders/1_68YvG_yFzVks-Lm_Qxr4BXIsTPMOdMy
