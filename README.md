# Deepfake Detection Using Python
This repository contains the code accompanying the book "Ultimate Deepfake Detection with Python".
There is a .ipynb file each for the chapters 7, 8, and 9.
You can run this code on your local machine which has Anaconda Python and Jupyter Notebook installed or you can run it on Google Colab. In case you run on Google Colab, please store the datasets in your Google Drive and connect to your Google Drive in your Colab notebook to access the data.


# Important Information About Datasets and Code Used

## Chapter 7: Deepfake Image Detection 

The original source of fake and real image is the OpenForensics++ Dataset available at https://zenodo.org/records/5528418#.YpdlS2hBzDd under the CC-BY 4.0 License.

A subset of above dataset is available at Kaggle here: https://www.kaggle.com/code/diegoguizanlopez/it-s-an-ai-or-a-person/input
The dataset used in this implementation is a subset of Kaggle dataset.
I have created this folder "shorter_df_images" to contain subset of images downloaded from Kaggle
You can use entire dataset downloaded from Kaggle and save it using any name. Use the name of your folder 
as value of the variable "imagedataset_path" in the jupyter notebook titled "Chapter7_OpenForensicsImageDetection.ipynb"


The code in the Jyputer Notebook titled "Chapter7_OpenForensicsImageDetection.ipynb" in this repository was implemented in Anaconda 3 Python Distribution (Python 3.11.9) on my Windows 11 PC. 



## Chapter 8: Deepfake Video Detection
Dataset: 
We will use the Deepfake Detection Challenge’s sample training data set available on Kaggle (Deepfake Detection Challenge Data, 2019) available at https://www.kaggle.com/c/deepfake-detection-challenge/data. 

This sample data contains 800 video files (real videos and fake videos included) in .mp4 format. The videos are placed in two folders – training and testing with 400 videos each. A metadata.json file indicates for each video following four pieces of information – filename of the video file, whether the video is real or fake as its label, if the video is fake then original indicates the name of original video from which the fake was created, and the split is train for all videos in the training folder.

Code:
The code you will see below is inspired from the Keras blog on Video classification (Paul, 2021), and these Kaggle Notebooks - DeepFake Starter Kit page at Kaggle (Deepfake Starter Kit, Kaggle, 2020) and (DB, 2022). Both the notebooks were released under the Apache 2.0 Licence (https://www.apache.org/licenses/LICENSE-2.0). 

The code in the Jyputer Notebook titled "Chapter8_DeepfakeVideoDetection.ipynb" in this repository was implemented in Anaconda 3 Python Distribution (Python 3.11.9) on my Windows 11 PC. 


## Chapter 9: Deepfake Audio Detection

For this task, We will use the dataset containing real and fake audio of well known people from https://www.kaggle.com/datasets/birdy654/deep-voice-deepfake-voice-recognition

The dataset is available under MIT License.

Download the Audio folder from above URL and save it with folder name "AudioClassification". It contains two sub folders - FAKE and REAL containing fake and real audio files respectively. Also download two files under the folder 'DEMONSTRATION' to test our audio classifier. These files are named as 'linus-original-DEMO.mp3' and 'linus-to-musk-DEMO.mp3', they contain original voice of Linus and voice of Linus converted to that of Elon Musk.

The code given here is inspired by the solutions to DEEP-VOICE: DeepFake Voice Recognition at Kaggle.com (https://www.kaggle.com/datasets/birdy654/deep-voice-deepfake-voice-recognition)

The code presented in the file titled "Chapter9_DeepfakeAudioClassification.ipynb" was implemented in Anaconda 3 Python Distribution (Python 3.11.9) on my Windows 11 PC.



