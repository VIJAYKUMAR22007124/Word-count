# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Get the file name as input from the user.
### Step 2: 
Open the file in read mode.
### Step 3: 
Use for loop to split the lines.
### Step 4:  
Store the split lines in a variable.
### Step 5: 
Add the number of lines and store it in a variable.
### Step 6: 
Print the stored variable.
## PROGRAM:
```Python

fname = input('Enter file name : ')
num_words = 0
with open(fname,'r') as f1:
    for line in f1:
        words = line.split()
        num_words += len(words)
print("Number of words : ",num_words)

```

### OUTPUT:
![image](./Screenshot%20from%202023-01-28%2013-44-08.png)



## RESULT:
Thus the program is written to find the word count from a text.
