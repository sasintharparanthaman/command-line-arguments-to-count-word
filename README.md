# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a text file in a specific loaction of interes
### Step 2: 
 On the same location as the text file, create a python program file.
### Step 3: 
n python Program, import sys and open a text file with argument "sys.argv[1]"
### Step 4:  
using read() and split(), split the lines in the file into a sequence of words
### Step 5: 
using len() count the number of words in the text file
### Step 6: 
In command prompt, initiate python followed by program name and text file name to get the output
## PROGRAM:
```
#program for getting the word count from the contents of a file using command line argument
#Developed by: P.Sasinthar
#Register Number:23012532

import sys
with open(sys.argv[0],'r') as f:
    num_words=0
    for i in f:
        word=i.split()
        num_words+=len(word)
print("Number of words={}".format(num_words))
```
### OUTPUT:

![Screenshot 2023-12-29 202817](https://github.com/sasintharparanthaman/command-line-arguments-to-count-word/assets/145743219/640719b6-34d1-422d-8e7e-b37979e51bad)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
