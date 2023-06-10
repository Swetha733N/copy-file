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
![image](https://github.com/Swetha733N/copy-file/assets/122199934/5e74136c-124d-42ab-af7d-48a73a255e34)
![image](https://github.com/Swetha733N/copy-file/assets/122199934/6cb8870e-260c-421e-90b4-8595e241da6e)


### RESULT:
Thus the program is written to copy the contents from one file to another file.
