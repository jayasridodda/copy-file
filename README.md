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
![Screenshot (46)](https://github.com/jayasridodda/copy-file/assets/123259278/5408e689-78e3-4819-90cb-2a683e94c099)


## File1
![Screenshot (47)](https://github.com/jayasridodda/copy-file/assets/123259278/b51f1c4c-db5f-4535-814d-b5b07065e083)

## File2

![Screenshot (48)](https://github.com/jayasridodda/copy-file/assets/123259278/6a4b5ca4-5202-43b4-a05a-019cf94137b1)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
