# Command--line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import the sys module to access command-line arguments.
### Step 2: 
Initialize a variable count to store the
total word count, set it to 0.
### Step 3: 
Open the file specified by the first command-line argument (sys.argv[1]) in read mode using the open() function with a context manager.
### Step 4:  
Start a loop to iterate through each line in the file.
### Step 5: 
Within the loop, split each line into words using the split() method and add the count of words in each line to the count variable.
### Step 6: 
After the loop, print the total word count stored in the count variable.

## PROGRAM:
```
/*
Program to  get the word count from the contents of a file using command line arguments:
Register number: 212223100049
Developed by: S.Sajetha
*/
```
```
import sys
count = 0
with open (sys.argv[1], 'r') as f1:
    for line in f1:
        word = line.split()
        count += len(word)
print("Word count in file =", count)
```
## OUTPUT:

![alt text](<Screenshot 2024-05-12 101516.png>)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
