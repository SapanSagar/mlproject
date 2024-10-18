##  Machine Learning Project

# Guide Step by Step

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
    4.	git commit -m "first Commit"  (comiting changes)
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




