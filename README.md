# ISM3232 - Module 2: zsh Navigation and File Operation

## Commands Practiced 

| Command | What it does |
| pwd | prints the current working directory |
| ls | lists visible files and folders |
| ls -la | lists all files including the hidden ones |
| cd .. | moves up one directory level |
| cd ~ | goes back to the home directory |
| cd ~/ism3232 | moves to our course folder |
| tree -L 2 | shows a directory tree 2 levels deep |
| touch | creates a new empty file |
| echo | writes text into a file |
| cat | shows file contents |
| head -1 | shows the first line in a file |
| cp | copies a file |
| rm | deletes a file |
| code . | opens the current folder in VS Code |
| mv | moves files and folders |

## AI Use Statement 

For this assignment I tested and wrote everything myself, only when stuck did I use Ai but not to copy and paste  but as a tool to debug or fix issues I could not resolve on my own. All code written was written by me and followed from the lab instructions on the website.

## Week 3: Virtual Environments and .zshrc 

### Commands Practiced 

| Command | What it does |
| python3 -m venv .venv | created an isolated virtual environment via python |
| source .venv/bin/activate | this activated the virtual environment |
| which python3 | shows which python you are using |
| pip list | lists installed packages |
| pip freeze > requirements.txt | saves installeed packages to a file |
| pip install -r requirements.txt | installs packages listed in a file |
| deactivate | turns the virtual environment off |
| pytest --collect-only | checks the pytest setup without runnig any tests| 
| .gitignore | prevents unwanted files from being tracked by git |

### Shell Aliases 

| Alias | what it does |
| ll | shortcut for ls -la |
| c | shortcut for clear |
| py | shortcut for python3 |
| gs | shortcut for gitstatus |
| ga | shortcut for git add . |
| gcmsg | shortcut for git commit -m |
| gp | shortcut for git push |
| gl | shortcut for git log --oneline |
| tree2 | shortcut for tree -L 2 |
| mkcd() | creates a new directory and enters it right away |