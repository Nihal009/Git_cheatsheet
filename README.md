# Git_cheatsheet

### Git Configuration
- **Set username:**  
  `git config --global user.name "Your Name"`
- **Set email:**  
  `git config --global user.email "your.email@example.com"`
- **Check configuration:**  
  `git config --list`

### Starting a Project
- **Initialize a new repository:**  
  `git init`
- **Clone an existing repository:**  
  `git clone https://github.com/user/repo.git`

### Basic Commands
- **Check the status of your repository:**  
  `git status`
- **Add files to staging area:**  
  `git add <file>`  
  `git add .` *(to add all files)*
- **Commit changes:**  
  `git commit -m "Commit message"`

### Branching
- **List branches:**  
  `git branch`
- **Create a new branch:**  
  `git branch <branch-name>`
- **Switch to a branch:**  
  `git checkout <branch-name>`
- **Create and switch to a new branch:**  
  `git checkout -b <branch-name>`
- **Delete a branch:**  
  `git branch -d <branch-name>`

### Merging
- **Merge a branch into the current branch:**  
  `git merge <branch-name>`
- **Resolve merge conflicts manually:**  
  Edit the conflicting files to resolve conflicts, then:  
  `git add <resolved-file>`  
  `git commit -m "Resolved merge conflicts"`

### Remote Repositories
- **Add a remote repository:**  
  `git remote add origin https://github.com/user/repo.git`
- **List remote repositories:**  
  `git remote -v`
- **Fetch changes from remote repository:**  
  `git fetch`
- **Push changes to remote repository:**  
  `git push origin <branch-name>`
- **Pull changes from remote repository:**  
  `git pull`

### Undoing Changes
- **Unstage a file:**  
  `git reset HEAD <file>`
- **Revert changes to a file:**  
  `git checkout -- <file>`
- **Amend the last commit:**  
  `git commit --amend -m "New commit message"`
- **Revert a commit:**  
  `git revert <commit-id>`

### Viewing History
- **View commit history:**  
  `git log`
- **View a specific file's commit history:**  
  `git log <file>`
- **Show changes between commits:**  
  `git diff <commit1> <commit2>`

### Tags
- **Create a tag:**  
  `git tag -a v1.0 -m "Version 1.0"`
- **List tags:**  
  `git tag`
- **Push tags to remote repository:**  
  `git push origin --tags`
