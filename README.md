# tasks_FDA
### Author: Manuel Fernandez
### University : Galway-Mayo Institute of Technology (GMIT)
### Course: Higher Superior Diploma in Science - Data Analytics
### Subject: Fundamentals of Data Analysis  , 1st Semester 2020-2021
Repository to save Fundamentals of Data Analysis  tasks from GMIT's Higher Superior Diploma of Science in Computing (Data analysis))

## A) First task: count function (1),(2),(3)

Counts.py has been created with the aim to count the items appearing in a list. to do that, this notebook has devided the task in two parts. The first one asks the user to provide two inputs: The number of elements the list will contain. 

After that, it will the script will ask the user to proper populate the list taking into account the number of items putted in step 1.

After all this it will output a dictionary with the numebr of times each item appears in the list.

Assets: There is no need to import any extra library since all the functions are Python's built in functions. In addition, it includes the possibility to leave off all empty places in a list leading to a more accurate reality in case by mistake there is a user that presses "enter" quicker than he should. 

## B) Second task: diceroll function (2),(4),(5)

The section called "B) diceroll" is also devided in two parts. The part one defines a function that does all the magic. In this case,the script asks the user to provide the number of dices the user wants to play. Second question is how many times user would like to make the dice roll. Important to enter allways an integer value, otherwise the script won't work (it will raise an alert). The second part of the script just call the function created in the first part and gives the desired output.

## C) Third task: numpy.random.binomial coin flipping task (6), (7), (8)

The script asks the user two questions: how many times wants to flip the coin and how many times wants to repeat the action. After knowing the input values, those values feed the coin variable (where it is used the numpy.random.binomial function to simulate the flip of the coin).

At last, it uses "Series" module from Pandas library to assign a X labelling in the distribution plot (from Seaborn library).

Please note that, it has been set the same seed value at the begining to get the same number to create the random values.

## D) fourth task: simspon's paradox task (9), (10), (11), (12)

This script tries to demonstrate the Simpson's paradox. Simpson's paradox is a phenonmenon in probability in which a trend appears in several different groups of data but disappears or reverses when these groups are combined.  

The script asks the user 4 different parameters a and b to create 4  different datasets following the path Y=Ax + B. After all groups are set, at last a new dataset is set as a concatenate of the 4 groups. For either the 4 groups and the dataset containing all of them, a line regression showing the pattern is represented.



## Bibliography: 
#### (1) GeeksforGeeks : https://www.geeksforgeeks.org/python-get-a-list-as-input-from-user/
#### (2) Stackoverflow : https://stackoverflow.com/questions/2600191/how-can-i-count-the-occurrences-of-a-list-item/23909767
#### (3) Stackoverflow : https://stackoverflow.com/questions/3845423/remove-empty-strings-from-a-list-of-strings
#### (4) Saltycrane : https://www.saltycrane.com/blog/2007/09/how-to-sort-python-dictionary-by-keys/
#### (5) Stackoverflow : (https://stackoverflow.com/questions/41267131/sum-of-n-dice-in-python)
#### (6) cmdlinetips : https://cmdlinetips.com/2018/12/simulating-coin-toss-experiment-with-binomial-random-numbers-using-numpy/
#### (7) Seaborn : https://seaborn.pydata.org/generated/seaborn.distplot.html
#### (8) numpy.random.binomial : (https://numpy.org/doc/stable/reference/random/generated/numpy.random.binomial.html)
#### (9) quantdare : https://quantdare.com/the-simpson-paradox/
#### (10) pandas : https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.html
#### (11) Stackoverflow: https://stackoverflow.com/questions/59670195/filling-multiple-columns-in-dataframe
#### (12) Wikipedia: (https://en.wikipedia.org/wiki/Simpson%27s_paradox)


