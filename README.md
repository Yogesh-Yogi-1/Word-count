# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Declare number of words as 0.
### Step 2: 
Open the txt file for reading 
### Step 3: 
Create a range function for the file.
### Step 4:  
Then next, split the words by space.
### Step 5: 
Count the number of words
### Step 6: 
End the program by printing the output.
## PROGRAM:
```
\*
# Program to find the word count
# Developed by: V. Yogesh
# register number: 212223230250
\*
num=0
with open("/content/story.txt","r") as f1:
  for i in f1:
    word=i.split()
    num+=len(word)
print("The number of words in the file is ",num)
```
### OUTPUT:
![Screenshot 2024-01-02 202131](https://github.com/Yogesh-Yogi-1/Word-count/assets/148514598/8fba8882-dcbe-4137-a0b1-22cec6add8e0)

## RESULT:
Thus the program is written to find the word count from a text.
