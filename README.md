
### Questions
* MacBeth Project in Section 02
* defining the terms in git
    * add vs merge vs push
* forks
* checkouts

### Objectives
YWBAT
* define pep8 standards
    * code of conduct of code
    * standard way of writing code in python
    * standard format for python code
    * makes things easier to read and understand
    * use pep8 because other people might look at our code and we want them to feel at home. 
* find some tools online that will autopep8 your code
    * `conda install -c conda-forge jupyter_contrib_nbextensions`
* define git
    * version control system
    * the objects that it is using are called repos
    * why do we need version control?
        * roll back, back up
        * collaborating becomes less of a headache
        * sharing work
* perform branching and merges in git (remotely)
* compare and contrast git commit to git push

### Outline
* Git stuff 
* Pep-8


```python
# simple imports go at the top
import math
import json

import pandas as pd
import numpy as np
import scipy.stats as scs

from time import time

from sklearn.linear_model import LinearRegression
from sklearn.model_selection import train_test_split, GroupKFold



# visualization tools go at the bottom, typically
import matplotlib.pyplot as plt
import seaborn as sns
```

# Pep 8 Standards (Because we aren't newbs)

![](images/pep8.jpg)

What is an IDE? (Interactive Development Environment)
- It's a piece of software where you can write code

Install Jupyter Notebook Extensions Here:
 
`conda install -c conda-forge jupyter_contrib_nbextensions`


```python
class myClass:
    def __init__(self):
        pass

    
    def function1():
        return None
```


```python
x = 3
y = 4
print(x+y)
```

    7



```python
# let's reformat the cell above for pep8 standards
x = 3
y = 4

print(x + y)
```

    7



```python
# let's reformat this function
def NewFunction(a, b):
    return(a * b)


def new_function(a, b):
    return a*b
```


```python
class my_class():
    
    def myFunction(self, a=4, b=3):
        return a*b
    
    
# reformatting the class above for pep8 we get

class MyClass():

    def my_function(self, a=4, b=3):
        return a*b
```

# Git Discussions

### Looking at Numpy

* Why do people fork it? 
    * store it on your local and to add enhancements
    * to experiment and try stuff out
* What's the difference between a branch and a fork?
    * branch is connected to the master
    * a fork is a snapshot that you take and remove it from the master
    
* Can you push a fork back to the master? 
    * yes, use the online tool (pull request)
    
* what does checkout do? 
    * moves you to a desired branch
    
* how do I check differences between branch and master? 
    * `git diff`

### Assessment


```python

```
