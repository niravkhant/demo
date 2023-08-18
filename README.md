# First Github Repo for Practice


## …or create a new repository on the command line

Use the Git Bash Terminal for command line.

```bash
git init
```
```bash
git status
```
```bash
git add .
```
```bash
git commit -m "first commit"
```
```bash
git branch -M main
```
```bash
git remote add origin https://github.com/niravkhant/demo.git
```
```bash
git push -u origin main
```
## …or push an existing repository from the command line

```python
# (1)=> set path or location
git remote add origin https://github.com/niravkhant/demo.git

# (2)=> set branch
git branch -M main

# (3)=> push code to repo
git push -u origin main
```
## Deleting Files

- If you delete files they will appear in git status as deleted, and you must use git add to stage them. Another way to do this is using git rm command, which both deletes a file and stages it all with one command:

- To Remove File
```bash
  git rm example.html
```
- To Remove Folder
```bash
  git rm -r myfolder
```

## Fixing Your Last Commit Message

- If you made a mistake in your last commit message, run this command:


```bash
  git commit --amend -m "Put your corrected message here"
```
## View a List/Logs of Commits

- To see a list of commits with more detail (such who made the commit and when), run this command:


```bash
  git log
```
```bash
  git log --stat
```
#### NOTE: If the list is long, use the Down/Up Arrow keys to scroll and hit Q to quit.

## Clone a repository from remote hosts (Github, GitLab etc.)



- To Clone Any Repo
```bash
  git clone <remote_repo_url
```
- Clone only a specific branch
```bash
  git clone -branch <branch_name> <re¢o_url
```

## Branches

- List all branches
```bash
  git branch
```
```bash
  git branch --list
```
  (shows remote branches as well)---↓
```bash
  git branch -a
```

- Create a new local branch named ne_branch without checking
  out that branch
```bash
  git branch <new_branch>
```

- Switch into an existing branch named <branch>
```bash
  git checkout <branch>
```

- Create a new local branch and switch into it
```bash
  git checkout -b <new_branch>
```
- Safe delete a local branch (prevents deleting unmerged changes)
```bash
  git branch -d <branch>
```
- Force delete a local branch (whether merged or unmerged)
```bash
  git branch -D <branch>
```
- Rename the current branch to <new_name>
```bash
  git branch -m <new_name>
```
- Merging a branch into the main branch
```bash
  git checkout main
```
- Merging a branch and creating a commit message
```bash
  git merge --no-ff <other_branch>
```
- Compare the differences between two branches
```bash
  git diff <branch_1> <branch_2>
```
- Compare a single <file> between two branches
```bash
  git diff <branch_1> <branch_2> <filename>
```
## Pulling changes from Remote Repo to local Repo

- A more aggressive version of fetch which calls fetch and merge
simultaneously
```bash
  git pull <remote>
```
