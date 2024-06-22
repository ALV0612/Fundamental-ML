# Mini-Project for Fundamentals of Machine Learning Course
![background](./materials/ai_wp.jpg)
This repository contains the code and data for a mini-project on facial expression recognition using machine learning algorithms.

## 📑 Project Policy
- Team: group should consist of 3-4 students.

    |No.| Student Name    | Student ID |
    | --------| -------- | ------- |
    |1|||Nguyễn Minh Toàn|21110195|
    |2|||Lê Vũ Hoàng An|21110|
    |3|||Nguyễn Hoàng Gia Bảo|21110|
    |4|||

- The submission deadline is strict: 11:59 PM on June 22nd, 2024. Commits pushed after this deadline will not be considered.

## 📦 Project Structure

The repository is organized into the following directories:

- /data: This directory contains the facial expression dataset. You'll need to download the dataset and place it here before running the notebooks. (Download link provided below)
- /notebooks: This directory contains the Jupyter notebook ```EDA.ipynb```. This notebook guides you through exploratory data analysis (EDA) and classification tasks.

## Result 
    Question 1: ![image](https://github.com/KOHAKUDEUS/Fundamental-ML/assets/114238406/5c5257e8-b298-4c25-97c1-73d44c0eff2f)

    Question 2: Optimal number of principal components: 255

    Part3 + 4:
    
     With transform data: 
     
     |No.| Model                      | Accuracy | Precision | Recall | F1-score
|:-:| -------------------------- | :------: | :-------: | :----: | :------: 
| 1 |KNeighborsClassifier        | 0.40     | 0.40      | 0.40   | 0.40
| 2 |RandomForestClassifier      | 0.40     | 0.50     | 0.40   | 0.36
| 3 |SupportVectorClassifier      | 0.48     | 0.48      | 0.48   | 0.47
| 4 |MLPClassifier               | 0.35     | 0.32      | 0.35   | 0.33

    With original data:
    
       |No.| Model                      | Accuracy | Precision | Recall | F1-score
|:-:| -------------------------- | :------: | :-------: | :----: | :------: 
| 1 |KNeighborsClassifier        | 0.42     | 0.42      | 0.42   | 0.42
| 2 |RandomForestClassifier      | 0.47     | 0.50     | 0.47   | 0.45
| 3 |SupportVectorClassifier      | 0.48     | 0.48     | 0.48   | 0.47
| 4 |MLPClassifier               |      |       |    |   
## ⚙️ Usage

This project is designed to be completed in the following steps:

1. Fork the Project: Click on the ```Fork``` button on the top right corner of this repository, this will create a copy of the repository in your own GitHub account. Complete the table at the top by entering your team member names.

2. Download the Dataset: Download the facial expression dataset from the following [link](https://mega.nz/file/foM2wDaa#GPGyspdUB2WV-fATL-ZvYj3i4FqgbVKyct413gxg3rE) and place it in the /data directory:

3. Complete the Tasks: Open the ```notebooks/EDA.ipynb``` notebook in your Jupyter Notebook environment. The notebook is designed to guide you through various tasks, including:
    
    1. Prerequisite
    2. Principle Component Analysis
    3. Image Classification
    4. Evaluating Classification Performance 

    Make sure to run all the code cells in the ```EDA.ipynb``` notebook and ensure they produce output before committing and pushing your changes.

5. Commit and Push Your Changes: Once you've completed the tasks outlined in the notebook, commit your changes to your local repository and push them to your forked repository on GitHub.


Feel free to modify and extend the notebook to explore further aspects of the data and experiment with different algorithms. Good luck.
We using some tool of AI to help complete this project.
