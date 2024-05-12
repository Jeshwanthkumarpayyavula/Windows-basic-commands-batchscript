# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file
Save each script in a file with a .bat extension.
Ensure you have the necessary permissions to perform the operations.
Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:

## Developed by : P.Jeshwanth Kumar
## Reg No.      : 212223240114

## Exercise 1: Basic Directory and File Operations
Create a directory named "MyLab" on the desktop.


## COMMAND AND OUTPUT

```
Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.

![image](https://github.com/Jeshwanthkumarpayyavula/Windows-basic-commands-batchscript/assets/145742402/70377139-0ce7-450e-b86c-a0a1b7bf90a5)
```

## COMMAND AND OUTPUT

```
List the contents of the "MyLab" directory.

![image](https://github.com/Jeshwanthkumarpayyavula/Windows-basic-commands-batchscript/assets/145742402/1358f7b2-aa16-447f-b989-68bc1d50adaf)

![image](https://github.com/Jeshwanthkumarpayyavula/Windows-basic-commands-batchscript/assets/145742402/ae8510a2-43b2-4b90-8e1e-9d1b2ee55e35)
```

## COMMAND AND OUTPUT

```
Copy "MyFile.txt" to a new folder named "Backup" on the desktop.

![image](https://github.com/Jeshwanthkumarpayyavula/Windows-basic-commands-batchscript/assets/145742402/5bee299e-614c-48b7-8555-00ffbfff7f27)

```

## COMMAND AND OUTPUT

```
Move the "MyLab" directory to the "Documents" folder.


![image](https://github.com/Jeshwanthkumarpayyavula/Windows-basic-commands-batchscript/assets/145742402/2ceb90f5-1ed3-49cd-90b6-d54d8bec640b)

![image](https://github.com/Jeshwanthkumarpayyavula/Windows-basic-commands-batchscript/assets/145742402/9f6e897d-e3a8-47f3-b2ad-757d42aa39b5)

```

## COMMAND AND OUTPUT
```
mv Myfile.txt %userprofile%\Documents

![image](https://github.com/Jeshwanthkumarpayyavula/Windows-basic-commands-batchscript/assets/145742402/47c03304-feb4-4239-9057-afcce0964b81)

```

## Exercise 2: Advanced Batch Scripting

```
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.

@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
echo Backup completed successfully!

```

## OUTPUT

![image](https://github.com/Jeshwanthkumarpayyavula/Windows-basic-commands-batchscript/assets/145742402/a9cc9582-7227-44b6-9053-fe521640eba5)


# RESULT:

The commands/batch files are executed successfully.

