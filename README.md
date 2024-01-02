# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open a python file using with statement.
### Step 2: 
Read the file in a variable called 'a'
### Step 3: 
Use split statement to seperate the contents given in the file and store it in a variabe called 'b'
### Step 4:  
print len(b) to get the word count.
## PROGRAM:
with open("text1.txt","r") as f:
    a=f.read()
    b=a.split()
    print("Word count",len(b))
## OUTPUT:
![exp 5a op](https://github.com/Vikaash19/Word-count/assets/148514589/eaae9e46-3bfd-4a95-919c-7a7dd517c46a)
### TEXT FILE:
![exp 5a tf](https://github.com/Vikaash19/Word-count/assets/148514589/f0415c6f-10b8-4df3-baec-f7c4d7dd19de)

## RESULT:
Thus the program is written to find the word count from a text.
