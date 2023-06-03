# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open the file f1 in read mode.
### Step 2: 
Open the file f2 in append mode.
### Step 3: 
Copy the contents using write() with the for loop.
### Step 4:  
End the program.
## PROGRAM:
```
#Developed By: JAYASRI DODDA
#Register No: 212222240028
with open('f1.txt','r') as f1:
    with open ('f2.txt','a') as f2:
        for line in f1:
            f2.write(line)
            
```
### OUTPUT:

![Screenshot (46)](https://github.com/jayasridodda/copy-file/assets/123259278/fff80964-fa29-4433-9caf-e5c7633abc89)

## File1
![Screenshot (47)](https://github.com/jayasridodda/copy-file/assets/123259278/46abe598-44cf-4144-9365-2ae4cfa2ec4f)

## File2
![Screenshot (48)](https://github.com/jayasridodda/copy-file/assets/123259278/f6dc5a12-2dda-4977-8835-7827e19a9923)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
