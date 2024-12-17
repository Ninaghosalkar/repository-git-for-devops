Git Commands for Development Workflow
Navigating Directories
ls: Lists the files and directories in the current directory.
cd <directory_name>: Changes the current directory to the specified directory.
ls -a: Lists all files, including hidden ones.
Git Status and Tracking Changes
git status: Shows the current state of the repository (which files are staged, modified, or untracked).
git add <file_name>: Stages a file to be committed (e.g., git add nibba.txt).
git commit -m "<message>": Commits the staged changes with a descriptive message.
git rm --cached <file_name>: Removes a file from the staging area without deleting it from the working directory.
git restore <file_name>: Restores a file to the last committed state.
git log: Displays the commit history.
git branch: Lists the current branches.
git checkout <branch_name>: Switches to the specified branch (e.g., git checkout dev).
git checkout -b <branch_name>: Creates and checks out a new branch (e.g., git checkout -b dev).
Git Configuration
git config --global user.name "<name>": Sets the global username for commits.
git config --global user.email "<email>": Sets the global email address for commits.
File Removal and Restoration
git rm -a <file_name>: Removes a file from both the working directory and the staging area.
rm <file_name>: Deletes a file from the working directory.
