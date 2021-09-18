# CerealTimeKillers
This project is a collaboration between the CerealTimeKillers team. 

## Project description
Deep learning model to predict emotional states based on EEG data. EEG data was collected while participants different video games of varying emotional content. 

## Data description
Data was collected from Kaggle (https://www.kaggle.com/sigfest/database-for-emotion-recognition-system-gameemo).
Data is from Alukas et al.: https://www.sciencedirect.com/science/article/abs/pii/S1746809420301075?via%3Dihub


What does this repo contain?
* Folders with raw data
* modules containing functions and classes to run convolutional and LSTM networks
* notebooks to execute modules

## Files

'GAMEEMO' - contains the raw and processed EEG during each video, and self assesment scores

'GameLabels.csv' - labels of each game type
 
 
## Modules

'admin_functions.py' - useful administrative functions useful

'CTK_net.py - functions and classes for running deep learning on EEG data


## Notebooks

'analysis_SAM.ipynb' - analysis of the self-reported assessment scores for participants

'CerealTimeKillersNet.ipynb' - notebook for training neural networks on EEG data


