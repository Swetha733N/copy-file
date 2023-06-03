# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
1. Get the input matrix using np.array() 

2. Find the 2-norm of the matrix using np.linalg.norm()

3. Print the norm of the matrix in two decimal places.

## PROGRAM:
```
Program for copying the contents from one file to another file
Developed by:SWETHA N
RegisterNumber: 212222110050

with open("text1.txt",'r') as fp:
    msg1=fp.read()
with open("copytxt",'w') as fp1:
    fp1.write(msg1)
```
### OUTPUT:
![image](https://github.com/Swetha733N/copy-file/assets/122199934/a3c9f5d9-55bd-4d58-b1d3-dbd1000ee90b)

### RESULT:
Thus the program is written to copy the contents from one file to another file.
