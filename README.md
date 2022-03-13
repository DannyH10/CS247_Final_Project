# CS247_Final_Project
This project contains all test code, training data sets, benchmarking results and our paper for the winter 2022 CS247 course project.

## Please make sure to Unzip Training Data before Opening Jupyter Notebook
- Training data excel files are 13 MB and 112 MB
- Compressed them to a zip file to upload to GitHub

## It is recommended that you run the benchmarking and custom training scripts in Google Collaboratory, so that you can make use of the GPU accessibility. Below, we outline the methods for running the benchmarking code locally on your machine or using Google Collaboratory.

## Set up dev environment on local machine

- `conda env create -n CS247_project`: create new environment
- `conda activate CS247_project`: activate python environment

## The notebooks in this project were developed and run with the follow packages (and package versions) and all of their dependencies

- jupyter 1.0.0
- nltk 3.6.7
- numpy 1.22.2
- pandas 1.4.1
- pytorch 1.10.2
- regex 2022.1.18
- scikit-learn 1.0.2
- scipy 1.8.0
- spacy 3.2.3
- transformers 4.16.2

## Navigate to the file directory and run the following command

-`jupyter notebook` : open jupyter notebook in the directory

## In the jupyter notebook navigate to the Import Traning Sets cell and modify the path to match the file location holding the excel sheets (shown below)
![image](https://user-images.githubusercontent.com/74755502/158052512-7e319d7f-b0cb-4441-aa38-fa95a8bf693d.png)

## Set up dev environment using Google Collaboratory

-Upload the notebook into your Google Collaboratory environment

-Upload the 4 dataset .csv files into the Google Collaboratory environment

--Google Collboratory file upload instructions:
---Make sure to upload/import the 4 dataset .csv files into your Google Collaboratory environment. This can be done in the following steps:
1. Click the 'Files' icon at the very left of this window
2. Within this window, click the 'Upload to session storage' icon.
3. Select the 4 .csv (2 training and 2 test) files stored either locally on your computer or on your Google Drive.
4. Import the files.

-Make sure that the path contains '/content/nameoffile.csv'

![image](https://user-images.githubusercontent.com/82487365/158080925-f2da64ba-0ca0-440a-8485-2e0395814d8e.png)

![image](https://user-images.githubusercontent.com/82487365/158080949-cedec1a8-eb9b-4058-8452-0befcba94209.png)
