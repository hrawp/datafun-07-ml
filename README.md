# datafun-07-ml
Machine Learning

This project will use machine learning to create a model and run that model to make a predicition.

## Question about Classes, Atributes, Methods, and
Besides DataFrame, list another class widely used in data analytics:
ChatGPT said:
ChatGPT
Another widely used class in data analytics is the Series class from the pandas library. A Series is a one-dimensional labeled array capable of holding any data type, and it's often used for handling and analyzing one-dimensional data.



You said:
Give an example of an attribute (data) stored in the class
ChatGPT said:
ChatGPT
In the Series class, one common attribute is the index. The index provides labels for each element in the Series, allowing for easy data retrieval and alignment.

For example:

python
Copy code
import pandas as pd

# Creating a Series
data = pd.Series([10, 20, 30], index=['a', 'b', 'c'])

# Accessing the index attribute
print(data.index)
In this example, the index attribute would output: Index(['a', 'b', 'c'], dtype='object').



You said:
Give an example of a class method (function) that operates on that data:
ChatGPT said:
ChatGPT
A common class method that operates on the Series class is the .sum() method. This method calculates the sum of the values in the Series.

Here’s an example:

python
Copy code
import pandas as pd

# Creating a Series
data = pd.Series([10, 20, 30], index=['a', 'b', 'c'])

# Using the sum() method
total = data.sum()

print(total)  # Output: 60
In this example, calling data.sum() returns the sum of the values in the Series, which is 60.


## End of question about class

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
git push -u origin main
```


## install depedencies from requirements.txt
```
py -m pip install -r requirements.txt
```