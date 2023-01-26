# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
import numpy as np

### Step 2: 
Enter the correct input values
 
### Step 3: 
write a python program for getting the word count from the contents of a file using command line
arguments.

### Step 4:
Use command line arguments

### Step 5:
End the program

## PROGRAM:
'''
Program developed by:G.R.Nandhakumar

Reference no:22001737

'''
```
import sys 
count=0 
with open(sys.argv[1],'r') as file:
    for line in file:
        word= line.split()
        count+= len(word)
print("word count in file = ",count)
```


### OUTPUT:
![Screenshot from 2023-01-26 15-10-03](https://user-images.githubusercontent.com/120230694/214804051-e217e7b2-b385-4bf5-a925-6d8d1602c2cc.png)
![Screenshot from 2023-01-26 15-11-07](https://user-images.githubusercontent.com/120230694/214804305-2de29ec8-6b37-4a55-baa7-db9b08d5da99.png)




## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
