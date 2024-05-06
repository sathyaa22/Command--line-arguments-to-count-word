# Command--line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open the file specified in the command-line argument using sys.argv[0].

### Step 2: 
Initialize a variable wordcount to zero.

### Step 3: 
Iterate through each line in the file.

### Step 4:  
Split each line into words.

### Step 5: 
Add the number of words in each line to wordcount.

### Step 6: 
Print the total number of words in the file.

## PROGRAM:

#Developed by SATHYAA R

#Register Number 212223100052
```
import sys
fp=open(sys.argv[0])
wordcount=0
for i in fp:
    words=i.split()
    wordcount+=len(words)
print("Total no of words in file",wordcount)
fp.close()
```

### OUTPUT:

![alt text](<10 pyth.jpg>)
![alt text](<10 pyth op.jpg>)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
