# Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Define the function as copy with arguements as existing file name and new file name.

### Step 2:
Open the existing file to read.

### Step 3:
Open the new file to write.

### Step 4:
Copy the contents from existing file to new file.

### Step 5:
Get the inputs from the user for existing file and new file. Call the function.

### Step 6:
End the program.

## PROGRAM:
```
Developed By: Samakash.R.S
Register Number: 212223230182

with open("text1.txt",'r') as fp:
    msg1=fp.read()
with open("copytxt",'w') as fp1:
    fp1.write(msg1)
```

### OUTPUT:

![alt text](<Screenshot 2024-05-12 133738.png>)
![alt text](<Screenshot 2024-05-12 133745.png>)
![alt text](<Screenshot 2024-05-12 133752.png>)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
