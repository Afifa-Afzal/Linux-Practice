# Linux Practice — Operating System Practicals

## About This Project
This repository contains screenshots of five Linux command-line practical exercises completed as part of my Operating System learning.

## Practical Tasks

### Question 1: Directory Structure                                                                                         OS_Project/ 
├── Documents/ 
│   ├── Notes/ 
│   └── Reports/ 
├── Programs/ 
│   ├── C/ 
│   └── Python/ 
└── Backup/ 
Then create these empty files: 
Documents/Notes/linux.txt 
Documents/Reports/report.txt 
Programs/C/program.c 
Programs/Python/program.py 
Finally, display the complete directory structure.
- Create directories using `mkdir -p`
- Create empty files using `touch`
- Display directories using `ls -R`

### Question 2: Rename and Copy Files
Inside the OS_Project directory created in Question 1: 
1. Rename linux.txt to linux_notes.txt. 
2. Copy linux_notes.txt into the Backup directory. 
3. Copy program.py into the Backup directory. 
4. Rename the copied program.py in Backup to python_backup.py. 
5. Display the contents of the Backup directory.                                                                            - Rename files using `mv`
- Copy files using `cp`
- Display directory contents using `ls`

### Question 3: University Directory
Create the following structure: 
University/ 
├── Semester1/ 
│   ├── OS/ 
│   └── Programming/ 
├── Semester2/ 
│   ├── OS/ 
│   └── Programming/ 
└── Backup/ 
Then: 
1. Create os_notes.txt inside Semester1/OS. 
2. Create program.c inside Semester1/Programming. 
3. Move os_notes.txt from Semester1/OS to Semester2/OS. 
4. Move program.c from Semester1/Programming to Semester2/Programming. 
5. Create a copy of both files inside Backup.                                                                               - Create a university directory structure
- Move files between semester folders
- Copy files into a backup directory

### Question 4: Delete Files and Directories
Create this structure: 
Lab_Work/ 
├── Week1/ 
│   ├── notes.txt 
│   └── old.txt 
├── Week2/ 
│   ├── assignment.txt 
│   └── test.txt 
└── Temporary/ 
├── temp1.txt 
└── temp2.txt 
Perform the following operations: 
1. Rename notes.txt to linux_notes.txt. 
2. Copy linux_notes.txt into Week2. 
3. Delete old.txt. 
4. Delete test.txt. 
5. Remove the Temporary directory along with all files inside it. 
6. Display the final directory structure.                                                                               - Rename and copy files
- Delete files using `rm`
- Remove directories using `rm -r`

### Question 5: Complete Practical Challenge
Starting from your home directory, create a directory called: 
Linux_Practical 
Inside it create: 
Linux_Practical/ 
├── Files/ 
│   ├── Text/ 
│   └── Programs/ 
├── Backup/ 
└── Old/ 
Now perform all of the following: 
1. Create notes.txt and commands.txt inside Files/Text. 
2. Create program.c and script.py inside Files/Programs. 
3. Rename commands.txt to linux_commands.txt. 
4. Copy notes.txt and linux_commands.txt into Backup. 
5. Move program.c from Files/Programs to Old. 
6. Rename script.py to backup_script.py. 
7. Move backup_script.py into Backup. 
8. Delete program.c from Old. 
9. Remove the empty Old directory. 
10. Display the final structure using an appropriate Linux command. 
Final expected structure 
Linux_Practical/ 
├── Files/ 
│   ├── Text/ 
│   │   ├── notes.txt 
│   │   └── linux_commands.txt 
│   └── Programs/ 
├── Backup/ 
│   ├── notes.txt 
│   ├── linux_commands.txt 
│   └── backup_script.py 
└── Old/                                                                                                                     - Create nested directories
- Rename, copy, and move files
- Delete files and remove an empty directory

## Commands Practiced
`mkdir -p`, `touch`, `mv`, `cp`, `rm`, `rm -r`, `rmdir`, `ls`, `ls -R`

## Learning Outcome
Practiced basic Linux file management, directory organization, file operations, and command-line navigation.

## Evidence
Screenshots of the practical tasks are included in this repository.
