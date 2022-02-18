# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:Import the sys module.

### Step 2: Pass the filename as the first argument after the name of script. Open the file as sys.argv[1]
 
### Step 3: Read the file using read() method.

### Step 4:  Use split() method to split the file content into words.

### Step 5: Use len() to find the total words.

### Step 6:Run the program to determine the number of words in the file created.

## PROGRAM:
```
Python program for getting the word count from the contents of a file using command line arguments.
Developed by:  Evangelin.S
Register Number: 212221230025

import sys
fp= open(sys.argv[1])
data=fp.read()
words=data.split()
print("Total Words:",len(words))
```


### OUTPUT:

![image](https://user-images.githubusercontent.com/94219798/154705122-e87e3008-3cb1-4fad-9c00-f623caa11d21.png)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
