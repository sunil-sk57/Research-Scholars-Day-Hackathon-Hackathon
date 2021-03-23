# Research-Scholars-Day-Hackathon-Hackathon
### Detecting COVID-19 induced Pneumonia from CT-scan reports.

#### The main aim of project is to find out whether to isolate a person or not based on chest CT-scan report.
The novel coronavirus has become the most pressing issue facing mankind. Like a wildfire burning through the world, the COVID-19 disease has changed the global landscape since last one year.In this project,we'll explore the feasibility and difficulties in building a system capable of detecting various causes of pneumonia in Chest CT-scan, using Transfer Learning techniques.

This repository contains the following files - 
* `Training Data` - This folder contains the dataset on which we train our model.
  It further contains the following folders - 
  * `CT_COVID` - Contains the CT scan for people who are COVID +ve
  * `CT_NonCOVID` - Contains the CT scan for people who are COVID -ve 
* `training_final.ipynb` - Contains the code for our simple CNN model trained on the dataset

We achieved an accuracy of 77% on the cross validation set.
