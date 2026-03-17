# VS CODE + CLI COMMAND REFERENCE (Top 50)

# ---------------------------

# VS CODE CLI (code command)

# ---------------------------

code .

# Open current folder in VS Code

code <folder-name>

# Open a specific folder in VS Code

code <file-name>

# Open a specific file

code -n

# Open a new VS Code window

code -r

# Reuse existing VS Code window

code -g file:line

# Open file at specific line number

code --diff file1 file2

# Compare two files side-by-side

code --add <folder>

# Add folder to current workspace

code --remove <folder>

# Remove folder from workspace

code --list-extensions

# List installed extensions

code --install-extension <extension-id>

# Install extension via CLI

code --uninstall-extension <extension-id>

# Remove extension

code --disable-extensions

# Start VS Code without extensions

code --version

# Show VS Code version

code --help

# Show all CLI options

# ---------------------------

# FILE SYSTEM (BASIC)

# ---------------------------

dir / ls

# List files in current directory

cd <folder>

# Change directory

cd ..

# Move up one directory

mkdir <name>

# Create new folder

rmdir <name>

# Delete folder

del <file> / rm <file>

# Delete file

copy <src> <dest> / cp

# Copy file

move <src> <dest> / mv

# Move or rename file

cls / clear

# Clear terminal screen

# ---------------------------

# GIT (MOST IMPORTANT)

# ---------------------------

git init

# Initialize a new Git repository

git clone <url>

# Download repo from GitHub

git status

# Show current changes

git add .

# Stage all changes

git add <file>

# Stage specific file

git commit -m "message"

# Save snapshot of changes

git log

# Show commit history

git diff

# Show changes not yet committed

git branch

# List branches

git branch <name>

# Create new branch

git checkout <branch>

# Switch branch

git checkout -b <branch>

# Create + switch branch

git merge <branch>

# Merge branch into current branch

git pull

# Fetch + merge latest changes

git push

# Upload changes to remote

git push origin main

# Push to main branch

git remote -v

# Show connected remotes

git remote add origin <url>

# Connect repo to GitHub

git rm -r --cached <file>

# Remove file from Git tracking (not disk)

git reset --soft HEAD~1

# Undo last commit (keep changes)

git reset --hard HEAD

# Reset everything (dangerous)

# ---------------------------

# NPM / NODE (FOR PROJECTS)

# ---------------------------

npm init -y

# Create package.json quickly

npm install

# Install dependencies

npm install <package>

# Install a package

npm install --save-dev <package>

# Install dev dependency

npm start

# Run app (uses package.json script)

npm run <script>

# Run custom script

npm list

# Show installed packages

npm uninstall <package>

# Remove package

node <file.js>

# Run JavaScript file with Node

node -v

# Check Node version

npm -v

# Check npm version

# ---------------------------

# POWER USER / DEBUG

# ---------------------------

history

# Show command history

where <command>

# Find where command is installed

echo <text>

# Print text to terminal

echo %PATH%

# Show environment paths (Windows)

set

# Show environment variables

exit

# Close terminal

# ---------------------------

# BONUS (VERY USEFUL)

# ---------------------------

explorer .

# Open current folder in Windows Explorer

start .

# Open folder (Windows)

open .

# Open folder (Mac)

pwd

# Show current directory path

whoami

# Show current user
