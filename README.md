# tasks_FDA
### Author: Manuel Fernandez
### University : Galway-Mayo Institute of Technology (GMIT)
### Course: Higher Superior Diploma in Science - Data Analytics
### Subject: Fundamentals of Data Analysis  , 1st Semester 2020-2021
Repository to save Fundamentals of Data Analysis  tasks from GMIT's Higher Superior Diploma of Science in Computing (Data analysis))

## A) First task: count function (1),(2),(3),(4)
the first task is a script that asks the user two inputs: first one to know the total number of items in the list he wants to add, and as soon as the number is set, will ask to populate the items of the list. as a final output, the result will be a dictionary that will be set with the values of the list as keys followed by the number of times each of the iteams appear in the list. As an asset and as required in the module, there is no need to import any extra library since all the functions are Python's built in functions.

In addition, it includes the possibility to leave off all empty places in a list leading to a more accurate reality in case by mistake there is a user that presses "enter" quicker than he should. 

## B) Second task: diceroll function (2),(4),(5)
The section called "B) diceroll" is in the same Jupyter document called Tasks_file. By executing the function, the system will ask how many dices you want to roll and the number of times you want to roll them. As output, it will generate a dictionary saying the number of times the sum of of dices has showed up.

## C) Third task: numpy.random.binomial coin flipping task (6), (7)
The scripts aims to show the probability to get a head when flipping a coin. To do that, the user is asked two questions: How many times you want to flip the coin? , and, how many times you want to repeat this action?. to simulate the flipping of the coin it has been set up a coin flipping using Numpy's random binomial function, where N and size parameters are inputed by answering the before mentioned questions. As a result it is displayed a plot where it is stored how many times has been observed a head in the total number of actions. As expected, the result is a shaped curve in the distribution of results

## D) fourth task: simspon's paradox task
The scripts sets 4 different datasets following different x inputs (using linspace function) and 4 different outputs following the path Y=Ax + B. A and B for all four of the cases are set by the user by answering different questions when running the script. After all groups are set, at last a new dataset as a result of concatenate is set and line regression is run again. As a result it is clear that when a dataset is split by groups, each of those follow a pattern that diffears from the one with all groups listed in one unique dataset.

## Bibliography: 
#### (1) GeeksforGeeks : https://www.geeksforgeeks.org/python-get-a-list-as-input-from-user/
#### (2) Stackoverflow : https://stackoverflow.com/questions/2600191/how-can-i-count-the-occurrences-of-a-list-item/23909767
#### (3) Stackoverflow : https://stackoverflow.com/questions/3845423/remove-empty-strings-from-a-list-of-strings
#### (4) Saltycrane : https://www.saltycrane.com/blog/2007/09/how-to-sort-python-dictionary-by-keys/
#### (5) Stackoverflow : (https://stackoverflow.com/questions/41267131/sum-of-n-dice-in-python)
#### (6) cmdlinetips : https://cmdlinetips.com/2018/12/simulating-coin-toss-experiment-with-binomial-random-numbers-using-numpy/
#### (7) Seaborn : https://seaborn.pydata.org/generated/seaborn.distplot.html
#### (8) quantdare : https://quantdare.com/the-simpson-paradox/
#### (9) pandas : https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.html
#### (10) Stackoverflow: https://stackoverflow.com/questions/59670195/filling-multiple-columns-in-dataframe

