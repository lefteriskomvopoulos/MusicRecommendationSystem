# Yahoo_Music_Recommendation_System

## Task 
This is an RS using collaborative filtering, that tries to predict new songs that a user might like , based on similar user's music preferences/ratings. All datasets has been received from the [official yahoo website](https://webscope.sandbox.yahoo.com/catalog.php?datatype=r&guccounter=1) after granting permission

## Criteria
* Big data managment and manipulation (size >10^7)
* Collaborative filtering algorithm
* SVD tranformation

## Functionality
Predicts the ratings that a user might put on a set of songs and also recommends to that user top 5 songs that would like the most. An extended documentation about this project , can be found [here](https://docs.google.com/document/d/1NMKCL3HeC8fqH5O4PJM3EEbl-g5w3SuOESPZLiQw0i4/edit#heading=h.r0v7pgch0w0z)

## Run locally / on your own
* Download the required datasets from the [official yahoo website](https://webscope.sandbox.yahoo.com/catalog.php?datatype=r&guccounter=1) -dataset R2- or use thes subsets of datasets at [this public drive](https://drive.google.com/drive/folders/10nyWTMPp78mJynyyO4eV2eae5D2nY7FR?usp=sharing)
* Download the final code of .ipynb and open it a google colab (or kaggle , jupiter notebook etc)
* Modify it accordingly so it can read the datasets 
  * either by changing at the first cell the directory url as : directory = "/content/drive/MyDrive/location_on_your_drive" 
  * or downloading them locally and upload them to colab by running an extra cell with these commands: 
    1) from google.colab import files 
    2) uploaded = files.upload() 
* Then do your testing!

## Tech stack
* Colab
* Python
* Pandas
* Numpy
* Matplotlib
