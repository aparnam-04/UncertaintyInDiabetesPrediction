# UncertaintyInDiabetesPrediction
Modeling Uncertainty in Diabetes Prediction by Race in the United States


File Name: Master_File_FINAL.ipynb
Open with Google Colab. 

Dependencies: 
Numpy
Pandas
Pymc3
Arviz
Matplotlib.pyplot
Seaborn
Pickle
Sklearn.model_selection

To access data & trace files in pickle format: 

Go to this link while logged in to your UVA email:
https://drive.google.com/drive/folders/1xvfoBilTrcl6mZJQHGT1Ft5EFn__14sL?usp=sharing 

Once there, click on the folder name and click Add shortcut to Drive. 

Once you have done that, you should be able to access the files to run this code by running these lines of code (which are in the file): 

from google.colab import drive
drive.mount('/content/gdrive')
%cd /content/gdrive/MyDrive/6040 Final Project/deliverables/code/RawData

Alternatively, all files may be downloaded from https://github.com/hschmuckler/BayesFinalProject. 


Pickle is a way of saving large python objects and retrieving them later. Our file has been built with many pymc3 traces that take a long time to run, the code to run them is commented out by default. Once your working directory is set as above, the code should automatically load the traces and run smoothly. If this does not work, uncomment the trace to run it manually, and comment out the save and load pickle functions. 
