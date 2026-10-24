Assignment 1.3 — Terminal & Developer Workflow
Objective: To create and manage a project folder structure using terminal commands and open the project in Visual Studio Code.
Procedure
1. Opened the terminal in Windows using Command Prompt or the VS Code terminal.
2. Created a folder named web-development-practice.
3. Created three subfolders named week-1, week-2, and week-3.
4. Created an index.html file inside each subfolder.
5. Practiced navigating between folders, renaming folders, and deleting folders using terminal commands.
6. Opened the project folder in Visual Studio Code directly from the terminal.
Terminal Commands
The following commands can be used in Windows Command Prompt (cmd):
mkdir web-development-practice
cd web-development-practice

mkdir week-1 week-2 week-3

type nul > week-1\index.html
type nul > week-2\index.html
type nul > week-3\index.html

cd week-1
cd ..
dir

ren week-1 week-1-practice
ren week-1-practice week-1

cd week-2
cd ..

code .


To practice deleting a folder, use a temporary folder:
mkdir test-folder
rmdir test-folder


Note: The deletion commands above remove only the empty test folder. The ren commands demonstrate renaming a folder and restoring its original name.
Final Folder Structure
Expected project structure
web-development-practice/
│
├── week-1/
│   └── index.html
│
├── week-2/
│   └── index.html
│
└── week-3/
    └── index.html


Result
Successfully created the project folder structure using terminal commands. Practiced folder navigation, renaming, and deletion, and learned how to open a project in Visual Studio Code using the code . command.
Submission
Attach a screenshot showing:
1. The terminal with the commands executed.
2. The final folder structure in VS Code Explorer, with week-1, week-2, and week-3 and their respective index.html files visible.