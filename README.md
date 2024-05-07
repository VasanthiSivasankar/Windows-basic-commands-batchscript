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
## Exercise 1: Basic Directory and File Operations
Create a directory named "MyLab" on the desktop.


## COMMAND AND OUTPUT

Change to the "MyLab" directory and create an empty text file named "MyFile.txt" inside it.
![image](https://github.com/VasanthiSivasankar/Windows-basic-commands-batchscript/assets/161431945/ec22b70e-55e1-44c4-9190-334de365a785)


## COMMAND AND OUTPUT

List the contents of the "MyLab" directory.
![image](https://github.com/VasanthiSivasankar/Windows-basic-commands-batchscript/assets/161431945/2ecbb1da-0080-499d-82a9-02219862125a)


## COMMAND AND OUTPUT

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
![image](https://github.com/VasanthiSivasankar/Windows-basic-commands-batchscript/assets/161431945/48225300-32a9-4c38-8618-9130423d708b)

## COMMAND AND OUTPUT

Move the "MyLab" directory to the "Documents" folder.
![image](https://github.com/VasanthiSivasankar/Windows-basic-commands-batchscript/assets/161431945/e488feb9-32e0-4197-9408-1986f983ebb7)


## COMMAND AND OUTPUT

![image](https://github.com/VasanthiSivasankar/Windows-basic-commands-batchscript/assets/161431945/03a81962-4b65-4e15-b8a0-b8e622ffd639)

## Exercise 2: Advanced Batch Scripting
Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.
```
@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
echo Backup completed successfully!
```
Modify the script to delete files with the ".docx" extension from the "Documents" folder after creating the backup.
```
@echo off
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
del %userprofile%\Documents\*.docx
echo Backup and deletion completed successfully!
```







## OUTPUT


![image](https://github.com/VasanthiSivasankar/Windows-basic-commands-batchscript/assets/161431945/924098bd-8ea7-43be-8128-c89b19d220b8)



# RESULT:
The commands/batch files are executed successfully.

