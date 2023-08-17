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
