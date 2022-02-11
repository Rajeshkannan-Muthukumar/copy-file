# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a function that takes two inputs, an existing file name and a new file name.

### Step 2: 
Open the existing file in read mode.
 
### Step 3: 
Open the new file in write mode.

### Step 4:  
Read the contents on existing file using read() and store it in a variable.
### Step 5: 
Copy the variable data into the new file using write().

### Step 6: 
Call the function.

## PROGRAM:
```
'''
Python program for copying the contents from one file to another file.
Developed by: M.RAJESHKANNAN
RegisterNumber: 21500434
'''

def copy(fname,newfile):
  with open(fname,'r')as fp:
    with open(newfile,'w')as fp1:
      data1=fp.read()
      fp1.write(data1)
fname=input("Enter an existing file: ")
newfile=input("Enter a name for new file: ")
copy(fname,newfile)
```

### OUTPUT:
## New Text File "File3.txt":
![OP 1](https://user-images.githubusercontent.com/93901857/153646233-bf35501f-9732-4c09-928a-ee5aa849cfbf.jpg)

## Output of the code (to receive input):
![OP2](https://user-images.githubusercontent.com/93901857/153646245-93aab30d-59f3-47d7-8c62-8a04b5e31e87.jpg)



## RESULT:
Thus the program is written to copy the contents from one file to another file.