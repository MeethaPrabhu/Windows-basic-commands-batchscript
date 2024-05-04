# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript
# DEVELOPED BY:
```
NAME: MEETHA PRABHU
REG NO: 212222240065
```
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
```
mkdir %userprofile%\Desktop\MyLab
cd %userprofile%\Desktop\MyLab
type nul > MyFile.txt
```
## OUTPUT
![image](https://github.com/MeethaPrabhu/Windows-basic-commands-batchscript/assets/119401038/1d58fd59-d02e-4e2c-a148-8f603032e80e)

## COMMAND 
List the contents of the "MyLab" directory.
```
dir %userprofile%\Desktop\MyLab
```

## OUTPUT
![image](https://github.com/MeethaPrabhu/Windows-basic-commands-batchscript/assets/119401038/0ef7e157-ee2b-4e80-92fe-3512cc80c33b)


## COMMAND 

Copy "MyFile.txt" to a new folder named "Backup" on the desktop.
Move the "MyLab" directory to the "Documents" folder.
```
mkdir %userprofile%\Desktop\Backup
copy MyFile.txt %userprofile%\Desktop\Backup
```
![image](https://github.com/MeethaPrabhu/Windows-basic-commands-batchscript/assets/119401038/e1c25edb-3370-499c-b610-fd0da34e44b6)



## Exercise 2: Advanced Batch Scripting

Create a batch script named "BackupScript.bat" that creates a backup of files with the ".docx" extension from the "Documents" folder to a new folder named "DocBackup" on the desktop.
```
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
```
![326272045-580064dc-ef03-40ab-8972-7027e649655f](https://github.com/MeethaPrabhu/Windows-basic-commands-batchscript/assets/119401038/31b489fd-e2ca-4260-8602-d15c47a93f75)

```
mkdir %userprofile%\Desktop\DocBackup
copy %userprofile%\Documents\*.docx %userprofile%\Desktop\DocBackup
del %userprofile%\Documents\*.docx
```

## OUTPUT
![326272029-a4de0dc2-b8ff-4f3d-82cf-1490bac46e34](https://github.com/MeethaPrabhu/Windows-basic-commands-batchscript/assets/119401038/d5d006d6-4193-4abc-af44-ac0db8314d1e)



# RESULT:
The commands/batch files are executed successfully.

