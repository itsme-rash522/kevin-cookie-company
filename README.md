# Kevin Cookie Company <img src="https://github.com/itsme-rash522/kevin-cookie-company/assets/127365805/cb710528-20af-4199-89a9-659f9df1185c" alt="cookie" width="20px">

- This is a sample repo for practicing Git & Github.
- All git commands that I used are below.

# With Git Bash or any CLI

- `git config --global user.name "Rashindu Tharinda"`
- `git config --global user.email tharindarashindu@gmail.com`
- `git config --global init.default branch main`
- `git config -h`
- `git help config`
- `git init`
- `git status`
- `git add index.htm`
- `git rm --cached index.htm`
- `git add --all | git add -A | git add .`
- `git commit -m "first commit"`
- `git diff`
- `git restore --staged index.htm`
- `git commit -a -m "skip staging area and commit"`
- `git rm "secret recipe.htm"`
- `git restore "secret recipe.htm"`
- `git mv "KCC Logo.png" "Primary Logo.png"`
- `git log`
- `git log --oneline`
- `git commit -m "amend previous commit" --amend`
- `git log -p`
- `git help log`
- `git reset c193567`
- `git rebase -i --root`
- `git branch NewBranch`
- `git branch`
- `git switch NewBranch`
- `git merge -m "merge NewBranch back to main" NewBranch`
- `git branch -d NewBranch`
- `git switch -c AnotherBranch`
- `git merge AnotherBranch`
- `git push --all`
- `git fetch`
- `git merge`
- `git pull`

# For GitHub

### Create a new repository on the command line

- Create a folder and open it on CLI
- `git init`
- `git add README.md`
- `git commit -m "first commit"`
- `git branch -M main`
- `git remote add origin https://github.com/itsme-rash522/repoName.git`
- `git push -u origin main`

### Push an existing repository from the command line

- Open local repository(folder) on CLI
- `git remote add origin https://github.com/itsme-rash522/repoName.git`
- `git branch -M main`
- `git push -u origin main`

### Push new files from local repo to remote repo while remote repo have different existing files

- `git fetch origin main`
- `git log origin/<branch-name>`
- `git merge origin/<branch-name>`
- `git rebase origin/<branch-name>`
- `git push origin <branch-name>`
