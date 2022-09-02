************** HOW TO RUN THE PROJECT **************

RUNNING IT ON KAGGLE:

1) Open and join the competition using the given link: https://www.kaggle.com/competitions/hubmap-organ-segmentation/overview 
2) Run "Model2.ipynb" file using the kaggle's notebook on the GPU.
3) Once Step 2 is completed, download the file named "model_final.pth" from the kaggle's directory.
4) Create a new notebook, upload the previously downloaded file "model_final.pth" as an input and use the code from the file "KaggleSubmission.ipynb".
5) Run the notebook created in Step 4 and once a file named "Submission.csv" created successfully, submit this file to get the final score.


RUNNING IT ON YOUR LOCAL MACHINE:

1) Download the dataset from the given link: https://www.kaggle.com/competitions/hubmap-organ-segmentation/data
2) Unzip the file downloaded.
3) Change the paths according to your location in all the notebooks.
4) Run “EDA.ipynb”
5) Run “Model1.ipynb”
6) Run “Model2.ipynb”

In case of any issues: Reach out to shambhavisingh15@gmail.com


Note: Folder present inside contain the "model_final.pth" (for model 2 which works better) file obtained while running both the models. It is the model saved while training according to the best Dice score.

The below two files where generated while running the code. Included in the zip file for reference.
->  "submission.csv" is the submission file created for Kaggle submission
->  "tiles_tiles.csv" is the updated csv generated after image tiling.