# 1. Git Configuration Commands

### git config --global user.name
Command Name: git config --global user.name
Syntax: git config --global user.name "Your Name"
Purpose: Sets the username that will appear in Git commits.
Example: git config --global user.name "Harika"
Screenshot Proof: Screenshot proof

### git config --global user.email
Command Name: git config --global user.email
Syntax: git config --global user.email "your-email@example.com"
Purpose: Sets the email address associated with Git commits.
Example: git config --global user.email "harika@gmail.com"
Screenshot Proof: Screenshot proof

### git config --list
Command Name: git config --list
Syntax: git config --list
Purpose: Displays all Git configuration settings.
Example: git config --list
Screenshot Proof: Screenshot proof

### git config --unset
Command Name: git config --unset
Syntax: git config --unset user.name
Purpose: Removes a configuration value from Git settings.
Example: git config --unset user.name
Screenshot Proof: Screenshot proof


# 2. Repository Setup Commands

### git init
Command Name: git init
Syntax: git init
Purpose: Initializes a new Git repository in the current directory.
Example: git init
Screenshot Proof: Screenshot proof

### git clone
Command Name: git clone
Syntax: git clone repository-url
Purpose: Creates a copy of a remote repository on the local machine.
Example: git clone https://github.com/username/project.git
Screenshot Proof: Screenshot proof

### git clone --branch
Command Name: git clone --branch
Syntax: git clone --branch branch-name repository-url
Purpose: Clones a specific branch of a repository.
Example: git clone --branch main https://github.com/username/project.git
Screenshot Proof: Screenshot proof

### git clone --depth
Command Name: git clone --depth
Syntax: git clone --depth number repository-url
Purpose: Performs a shallow clone with limited commit history.
Example: git clone --depth 1 https://github.com/username/project.git
Screenshot Proof: Screenshot proof


# 3. Repository Status & Inspection

### git status
Command Name: git status
Syntax: git status
Purpose: Shows the current status of files in the repository.
Example: git status
Screenshot Proof: Screenshot proof

### git log
Command Name: git log
Syntax: git log
Purpose: Displays commit history.
Example: git log
Screenshot Proof: Screenshot proof

### git log --oneline
Command Name: git log --oneline
Syntax: git log --oneline
Purpose: Displays commit history in a short format.
Example: git log --oneline
Screenshot Proof: Screenshot proof

### git log --graph
Command Name: git log --graph
Syntax: git log --graph
Purpose: Shows commit history with a graphical branch structure.
Example: git log --graph
Screenshot Proof: Screenshot proof

### git show
Command Name: git show
Syntax: git show commit-id
Purpose: Displays detailed information about a specific commit.
Example: git show a1b2c3
Screenshot Proof: Screenshot proof

### git diff
Command Name: git diff
Syntax: git diff
Purpose: Shows differences between working directory and last commit.
Example: git diff
Screenshot Proof: Screenshot proof

### git diff --staged
Command Name: git diff --staged
Syntax: git diff --staged
Purpose: Shows differences between staged files and last commit.
Example: git diff --staged
Screenshot Proof: Screenshot proof

### git blame
Command Name: git blame
Syntax: git blame file-name
Purpose: Shows who last modified each line of a file.
Example: git blame index.html
Screenshot Proof: Screenshot proof

### git reflog
Command Name: git reflog
Syntax: git reflog
Purpose: Shows history of HEAD changes.
Example: git reflog
Screenshot Proof: Screenshot proof

### git shortlog
Command Name: git shortlog
Syntax: git shortlog
Purpose: Summarizes commit history grouped by author.
Example: git shortlog
Screenshot Proof: Screenshot proof


# 4. File Tracking Commands

### git add
Command Name: git add
Syntax: git add file-name
Purpose: Adds a file to the staging area.
Example: git add index.html
Screenshot Proof: Screenshot proof

### git add .
Command Name: git add .
Syntax: git add .
Purpose: Adds all files in the current directory to the staging area.
Example: git add .
Screenshot Proof: Screenshot proof

### git add -p
Command Name: git add -p
Syntax: git add -p
Purpose: Allows interactive staging of changes.
Example: git add -p
Screenshot Proof: Screenshot proof

### git restore
Command Name: git restore
Syntax: git restore file-name
Purpose: Restores a file to its previous committed state.
Example: git restore index.html
Screenshot Proof: Screenshot proof

### git restore --staged
Command Name: git restore --staged
Syntax: git restore --staged file-name
Purpose: Removes a file from the staging area.
Example: git restore --staged index.html
Screenshot Proof: Screenshot proof

### git rm
Command Name: git rm
Syntax: git rm file-name
Purpose: Deletes a file from the repository and working directory.
Example: git rm test.txt
Screenshot Proof: Screenshot proof

### git mv
Command Name: git mv
Syntax: git mv old-name new-name
Purpose: Renames or moves a file in the repository.
Example: git mv file1.txt file2.txt
Screenshot Proof: Screenshot proof


# 5. Commit Commands

### git commit
Command Name: git commit
Syntax: git commit
Purpose: Records changes to the repository.
Example: git commit
Screenshot Proof: Screenshot proof

### git commit -m
Command Name: git commit -m
Syntax: git commit -m "message"
Purpose: Commits changes with a message.
Example: git commit -m "Initial commit"
Screenshot Proof: Screenshot proof

### git commit --amend
Command Name: git commit --amend
Syntax: git commit --amend
Purpose: Modifies the most recent commit.
Example: git commit --amend
Screenshot Proof: Screenshot proof

### git commit --no-edit
Command Name: git commit --no-edit
Syntax: git commit --no-edit
Purpose: Amends the previous commit without changing its message.
Example: git commit --no-edit
Screenshot Proof: Screenshot proof