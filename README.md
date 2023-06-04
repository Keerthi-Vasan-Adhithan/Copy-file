# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a text1.txt with some content in it
### Step 2: 
Open the text1.txt file in read mode
### Step 3: 
Create a copy.txt file using write mode
### Step 4:  
Copy the content of text1.txt file to copy.txt using write function

## PROGRAM:
```
''' 
Program for copying the contents from one file to another file
Developed by: KEERTHI VASAN A
RegisterNumber: 212222240048
'''
with open("text1.txt",'r') as fp:
    msg1=fp.read()
with open("copytxt",'w') as fp1:
    fp1.write(msg1)
```
### OUTPUT:
![5c1](https://github.com/Vanitha-SM/copy-file/assets/119557985/48ad7f5b-b1c6-401d-9ba1-f9176d7262cb)
![5c2](https://github.com/Vanitha-SM/copy-file/assets/119557985/a87f7a25-0364-4e48-a3cd-b628a12cfbdd)
![5c3](https://github.com/Vanitha-SM/copy-file/assets/119557985/a25524f0-55cd-407f-ade0-c7ffd7a76536)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
