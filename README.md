# python-internship-task_7

1)Create a python module with list and import the module in another .py file and change the value in list

list_1.py
l1=[4,2,6,8]

#temp.py
import list1 as li
s=[]
s=li.l1
for i in range(len(s)):
	s[i]+=10
print(s)

2)pip install pandas

3)Import a module that picks random number and write a program to fetch a random number from 1 to  100 on every run

import random 
num=random.randint(1,50)
print(num)

4)Import sys package and find the python path

import sys,os
file=sys.argv[0]
path_name=os.path.dirname(file)
print(path_name)
