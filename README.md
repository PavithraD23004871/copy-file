# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a file.
### Step 2: 
 Write some lines in that file.
### Step 3: 
Create a python file
### Step 4:  
Write a code to copy the content of the file to a new file.
### Step 5: 
Run the program.
### Step 6: 
Display the output.
## PROGRAM:
Developed By:pavithra.D
Register No: 212223230146

def copy(filename,newfile):
    with open(filename,'r') as fp:
        with open(newfile,'w') as fp1:
            data1=fp.read()
            fp1.write(data1)
filename=input("Enter an Existing File:")
newfile=input("Enter a name for new file:")
copy(filename,newfile)
### OUTPUT:
![WhatsApp Image 2023-12-27 at 18 53 15_1bc758fd](https://github.com/PavithraD23004871/copy-file/assets/138955967/972b3ef6-86e6-4f67-bc14-329273f4c13c)
![WhatsApp Image 2023-12-27 at 18 53 15_47617dbb](https://github.com/PavithraD23004871/copy-file/assets/138955967/95d588d9-0632-4773-be65-7aabf75c90bb)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
