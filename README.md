# machine-learning-module1lab
Module 1 Lab
Melissa Stone Rogers, June 27, 2024

## Introduction
Professional project to use Jupyter Lab, python, and needed frameworks to complete simple guided machine learning application.
Commands were used on a Mac machine running zsh.  

## How to Install and Run the Project
Create project repository in Github and clone to your machine.

```
git clone project.url
```
Verify Python version of Python 3
```
python3 --version

```
```
python3 -m venv ds-venv
source ds-venv/bin/activate
```
Install required packages 
```
pip install numpy
pip install jupyterlab matplotlib pandas
python3 -m pip install -U scikit-learn
```

Create requirements.txt in the root project folder. 
```
touch requirements.txt
```
Add the following requirements into requirements.txt:
- numpy
- jupyterlab 
- matplotlib 
- pandas

## Freeze Requirements

```
python3 -m pip freeze > requirements.txt
```

## Add .gitignore File
Add .gitignore file to the root project folder. 
```
touch .gitignore
```
Add the following to your .gitignore file: 
- .ds-venv/
- .vscode/
- .ipynb_checkpoints/

### Troubleshooting Jupyter Lab
I encountered an error when when trying to run Jupyter Lab: "[W 2024-06-27 13:35:32.925 LabApp] Could not determine jupyterlab build status without nodejs" After conulting ChatGPT, I did the following to install Node.js: 
```
brew install node
```

Verify installation
```
node -v
npm -v
```

Rebuild Jupyter Lab
```
jupyter lab build
```

## Initial Project Save
```
git add .
git commit -m "initial"                         
git push origin main
```
### Start and Complete Project 
Copy lab1_starter.ipynb into workspace and open it. 

Follow project steps as found in [this PDF](https://github.com/meldstonerogers/machine-learning-module1lab/blob/main/Lab%20W1%20scikit.pdf).


## Complete Your Project
Save your project and push back to your repository. 
```
git add .
git commit -m "final"                         
git push origin main