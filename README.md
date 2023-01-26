# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Get the file name and location from the user.

### Step 2: 
Give a new file name to create a copy of a file content
 
### Step 3: 
Give a new file name to create a copy of a file content

### Step 4:
Now write the content in the new file.

### Step 5: 
When done print "File copied successfully".

### Step 6:
End of the program.

## PROGRAM:
'''
Program for copying the contents

Developed by:G.R.Nandhakumar

Reference number:22001737

'''
```
print("Enter the name of source file: ")
sFile=input()
print("Enter the name of target file: ")
tFile=input()
fileHandle=open(sFile,"r")
texts=fileHandle.readlines()
fileHandle.close()

fileHandle=open(tFile,"w")
for s in texts:
    fileHandle.write(s)
fileHandle.close()

print("\nFile Copied Successfully!")
```

### OUTPUT:
![commandcopy](https://user-images.githubusercontent.com/120230694/214801032-5b75dc01-6639-4c23-bd78-a5b0eeeadbcc.png)
![copy1](https://user-images.githubusercontent.com/120230694/214801074-255a73a7-5100-487a-93fa-e18072c35f24.png)
![copy2](https://user-images.githubusercontent.com/120230694/214801132-f777eeda-b1be-4fc6-9b1a-3a480e224914.png)




## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
