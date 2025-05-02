# Git_Commands

1. **Check Username and Email Configured -**
```
git config --list
```
![image](https://user-images.githubusercontent.com/88997177/132237604-979f0f3e-e805-40f9-9e8c-348c01a3a484.png)

2. **Set Username and Email - Locally**
```
git config user.name "Your Username"
git config user.email "Your Email Address"
```

3. **Set Username and Email - Globally**
```
git config --global user.name "Your User Name"
git config --global user.email "Your Email Address
```

4. **Check again Username and Email -**
```
git config --list
```

5. **We can also check using -**
```
git config --global user.name
git config --global user.email
```
| Command                                   | Description                                      |
|-------------------------------------------|--------------------------------------------------|
| `git init`                                | Initialize a new Git repository in the folder    |
| `git clone <repo-url>`                    | Clone (download) a remote repository             |
| `git status`                              | Show the status of changes (staged, unstaged)    |
| `git add <file>` or `git add .`           | Add file(s) to staging area                     |
| `git commit -m "message"`                 | Commit staged changes with a message            |
| `git push`                                | Push commits to the remote repository           |
| `git pull`                                | Pull updates from the remote repository         |
| `git branch`                              | List all branches                               |
| `git checkout -b <branch-name>`           | Create and switch to a new branch               |
| `git checkout <branch-name>`              | Switch to an existing branch                   |
| `git merge <branch-name>`                 | Merge a branch into the current branch         |
| `git log`                                 | View commit history                            |
| `git remote -v`                           | Show remote repository URLs                    |
| `git reset --hard <commit-hash>`          | Reset to a specific commit (destructive)       |
