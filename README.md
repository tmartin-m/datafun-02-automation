# datafun-02-automation
44608-project 2

# Pull Changes
git pull origin main

# Activate Virtual Environment
https://learn.microsoft.com/en-us/powershell/module/microsoft.powershell.core/about/about_execution_policies?view=powershell-7.5
cmd.exe
pwsh.exe -ExecutionPolicy AllSigned
.venv\Scripts\activate

#Install Dependencies
.\.venv\Scripts\activate
py -m pip install --upgrade pip setuptools wheel
py -m pip install -r requirements.txt

# Activate & Execute
Select VS Code Interpreter
Ctrl + Shift + P
Search for "Python: Select Interpreter"
Choose an Interpreter - A list of available Python environments will appear. Look for the recommended local .venv option
.\.venv\Scripts\activate
py myfile.py

# Modify & Test

# Git Push
git add .
git commit -m "Add .gitignore and requirements.txt files"
git push -u origin main

# To Dos
https://www.stepsize.com/blog/best-vs-code-extensions-to-handle-todos
