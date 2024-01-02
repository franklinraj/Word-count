# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
create a text file using jupyter 
### Step 2: 
now open the text file sample.txt 
### Step 3: 
to open use with open() function
### Step 4:  
now to count split the text by giving split()
### Step 5: 
give for loop to count

### Step 6: 
by now it gets added and gives output
## PROGRAM:
```
#Program to find the word count
# developed by: FRANKLIN RAJ G
# REGISTER NO:23001518
num=0
with open("sample.txt","r") as f1:
    for i in f1:
        word=i.split()
        num+=len(word)
print("the number of words are in the file is",num)

```

### OUTPUT:
![Screenshot 2024-01-02 231601](https://github.com/franklinraj/Word-count/assets/148993740/ec915aa9-e70a-4d14-83c2-bf551a4ae8d2)




## RESULT:
Thus the program is written to find the word count from a text.
