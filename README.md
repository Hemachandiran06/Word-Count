# Word-Count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Decleare number of words is 0
### Step 2: 
 open it with txt file
### Step 3: 
Give range for i
### Step 4:  
Then next split the words
### Step 5: 
count the number of words

### Step 6: 
Giving print statement for getting output
## PROGRAM:

```python
#Program for getting the word count from a text
#Developed by : HEMACHANDIRAN J
#Reg num : 212224040113
num_words =0
with open('trty','r') as file1:
 for i in file1:
  word =i.split()
  num_words += len(word)
print("Number of words={}".format(num_words))

```

### OUTPUT:
 ### text file:
![image](https://github.com/user-attachments/assets/99d3c22b-8bcf-4168-bec3-4f4888027541)


 ### program output:


![image-1](https://github.com/user-attachments/assets/ba8e9f37-ab05-4ec7-b0a5-75b0f4d6f6ab)

## RESULT:
Thus the program is written to find the word count from a text.
