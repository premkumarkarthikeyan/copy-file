# copy-file

## AIM:

To write a python program for copying the contents from one file to another file.

## EQUIPEMENT'S REQUIRED: 

PC
Anaconda - Python 3.7

## ALGORITHM: 

Step 1:

Create a text1.txt with some content in it

Step 2:

Open the text1.txt file in read mode

Step 3:

Create a copy.txt file using write mode

Step 4:

Copy the content of text1.txt file to copy.txt using write function

## PROGRAM:
```
Program for copying the contents from one file to another file
Programmed By:PREM KUMAR K
RegisterNumber: 212222230111

with open("text1.txt",'r') as fp:
    msg1=fp.read()
with open("copytxt",'w') as fp1:
    fp1.write(msg1)
```
### OUTPUT:
![image](https://github.com/premkumarkarthikeyan/copy-file/assets/119476243/a6ec0e4d-078c-4999-b457-2e94513bf30f)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
