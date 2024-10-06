# datafun-07-ml
Machine Learning
##  How to Install and Setup Projects

Create a new repo in Git Hub.  Make sure to include README when creating the new repo.

Clone the new repo to your machine.
```
git clone https://github.com/hrawp/datafun-07-ml
```

Add a .gitignore file with:
## Python virtual environment.
```
.venv/
```

## Visual Studio Code settings and workspace.
```
.vscode/
```
added so .venv files will not be sent up to your repo.

## Create a virtual environement by running this command.
```
python -m venv .venv
```

## Activate the environment by running this command.
```
.\.venv\Scripts\activate
```

## If the project uses Jupyter, include an entry in gitignore
```
.ipynb_checkpoints/
```
## Update the requirements.txt with libraries that need to be installed.



## Run the three Git commands to stange and transmit files to GitHub.
```
git add .
```
```
git commit -m "initial commit"
```
```
git push origin main
```


## install depedencies from requirements.txt
```
py -m pip install -r requirements.txt
```