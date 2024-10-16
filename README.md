# Date:
# Ex.No 10: Command--line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1: Import sys module to use command line arguments.`

### Step 2: Create a file pointer and open the file which is passed in command line.
 
### Step 3: Initialize word count as zero.

### Step 4:  For each line in file, split it into words and find number of the words in every line.

### Step 5: Sum the number of words in each line.

### Step 6: Display the total words in the file.

## PROGRAM:
```
# Program to find Command--line-arguments-to-count-word
# Developed by: Hanshika VArthini R
# Register no: 212223240046

import sys
fp=open(sys.argv[0])
wordcount=0
for i in fp:
    words=i.split()
    wordcount+=len(words)
print("Total no of words in file is",wordcount)
fp.close()
```

### OUTPUT:

![Screenshot 2024-10-16 155920](https://github.com/user-attachments/assets/9b61d12c-a874-4172-8f4b-c64dcdaa508a)
![Screenshot 2024-10-16 155910](https://github.com/user-attachments/assets/f92110bd-658b-4306-a526-6003fc638c77)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
