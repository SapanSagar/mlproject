##  Machine Learning Project
This Project is step by step guide and will help people to learn how to create and deploy end to end ML Model.
Here we are creating a ML Classification model using US VISA Data. Where we need to predict if Visa application will be approved or denied based on give features in data.

- data link : https://www.kaggle.com/datasets/moro23/easyvisa-dataset

# Guide Step by Step
## Project and enviornment setup

# Create a virtual environment :
    - python -m venv myenv
    - myenv\Scripts\activate   #activate your virtual environment

# Github Setup
- Create a Github Repo :-- #MyProject
- Create a project folder on your system and open VS code in the same folder
# Sync With Git Repo :
    1.	git init   #initialize git 
    2.	create a README.md file in your VS code (Project Folder)
    3.	git add README.md  # add readme file to git
    4.	git commit -m "first Commit"  (commiting changes)
    5.	git branch -M main   (changing branch to main)
    6.	git remote add origin https://github.com/SapanSagar/mlproject.git  (sync with your repo)
    7.	git push -u origin main    (push changes to github repo)

Note : If doing for first time please use below two commands to sync your account before push
-$ git config --global user.name "John Doe"
-$ git config --global user.email johndoe@example.com
-Create .gitignore file in Github repo and select language as Python
Git pull to sync local with github

# Create Template file to define project structure
    - refer template.py for details
# create requirements.txt
    - add all libraries in file you need
    -add -e . to create package (will look for setup.py)

- pip install -r requirements.txt

## DataBase Setup
Mongo DB Link : https://www.mongodb.com/?msockid=0ab9429ac85067b735f95183c956663f
signin--    new project--Give Project Name--Next--add tea members if needed--create project--
create cluster--select plan--name of cluster--select--AWS--create--create username and password for later access (dont share)--click on network acess-add IP Address--Allow access from anywhere--confirm--previous tab--create database user--choose a connection method--select options (driver)--copy connection string and keep it for later use

--Refer Mongodb_demo.ipynb file for further steps on connection creation,load and read data 

## Create Logger,Exception and Utility files
- refer logger,exception and utils python files for detail also demo.py

## Initiate Problem understanding and EDA
- refer eda.ipynb file for details



