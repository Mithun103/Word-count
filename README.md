# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
## Step 1:
Open terminal and activate conda, then open jupyter notebook.

## Step 2:
Create a text file in jupyter notebook or upload a text file in the jupyter notebook.

## Step 3:
Open a new cell in jupyter notebook.

## Step 4:
Type the program in the cell.

## Step 5:
Now in the output box,type the file name.

## Step 6:
End the program.

## PROGRAM:
```
#Developed by: MITHUN MS
#Reference No: 22008364
fname=input("Enter file name: ")
num_words=0
with open(fname,'r') as f:
    for line in f:
        words=line.split()
        num_words+=len(words)
print("Number of words: ",num_words)
```

### OUTPUT:

![Screenshot_20230126_043737](https://user-images.githubusercontent.com/118344695/214822686-85b4614d-1084-4577-ab3e-f1a4c0b30992.png)
![Screenshot_20230126_043749](https://user-images.githubusercontent.com/118344695/214822853-d7281adc-6ae0-497a-8542-9b6b79bec385.png)



## RESULT:
Thus the program is written to find the word count from a text.
