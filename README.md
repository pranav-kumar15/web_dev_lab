# web_dev_lab


# P1 – Project Folder and Terminal Navigation

## Aim

To create a portfolio project folder and practise basic terminal navigation commands.

## Commands

Run these commands in the terminal:

```bash
pwd
mkdir MyPortfolio
cd MyPortfolio
mkdir images css
ls
cd css
pwd
cd ..
```

## Description

- `pwd` displays the current working directory.
- `mkdir MyPortfolio` creates a new folder named MyPortfolio.
- `cd MyPortfolio` moves inside the MyPortfolio folder.
- `mkdir images css` creates two folders named images and css.
- `ls` shows the contents of the current folder.
- `cd css` moves inside the css folder.
- `pwd` displays the current location in the terminal.
- `cd ..` moves one folder back to MyPortfolio.

## Result

The MyPortfolio folder was successfully created with images and css subfolders. Basic terminal navigation commands were also practised.















# P2 – Portfolio Repository with an Initial Commit

## Aim

To create a Git repository for a portfolio project and save the first commit.

## Commands

Run these commands inside a new portfolio project folder:

```bash
git init
git status
git add .
git commit -m "Initial commit"

git branch -M main
git remote add origin YOUR_GITHUB_REPOSITORY_URL
git push -u origin main
```

Replace `YOUR_GITHUB_REPOSITORY_URL` with the URL of your GitHub repository.

## Description

- `git init` creates a new local Git repository.
- `git status` shows the current status of the project files.
- `git add .` adds all project files to the staging area.
- `git commit -m "Initial commit"` saves the changes as the first commit.
- `git branch -M main` changes the branch name to main.
- `git remote add origin` connects the local repository with GitHub.
- `git push -u origin main` uploads the project files to GitHub.

## Result

A Git repository was successfully created for the portfolio project. The initial commit was saved and the project was uploaded to GitHub.
















# P3 – Feature Branch Git Workflow

## Aim

To create a new feature branch, make a small change, and push the branch to GitHub.

## Commands

Run these commands from the project repository:

```bash
git switch -c feature/my-change
git status
git add .
git commit -m "Add a portfolio change"
git push -u origin feature/my-change
```

## Description

- `git switch -c feature/my-change` creates a new branch and switches to it.
- `git status` displays the current changes in the project.
- `git add .` stages all modified and new files.
- `git commit -m "Add a portfolio change"` saves the changes in the new branch.
- `git push -u origin feature/my-change` uploads the feature branch to GitHub.

## Result

A new feature branch was successfully created. Changes were committed and the branch was pushed to the remote GitHub repository.













# P4 – GitHub README and Version Tags

## Aim

To document the project using a GitHub README file and learn how to create version tags.

## Repository README

The root README.md file provides basic information about the Web Development Lab repository. It contains the practical folder names and the technologies used.

## Git Commands

First, check the repository status:

```bash
git status
git log --oneline
```

Create an annotated version tag after the P1–P4 practical work is available locally:

```bash
git tag -a v1.0.0 -m "First version of Web Development Lab"
git tag
git push origin v1.0.0
```

To inspect the created tag:

```bash
git show v1.0.0
```

## Description

- `git status` displays the current state of the repository.
- `git log --oneline` shows the commit history in a short format.
- `git tag -a` creates an annotated version tag.
- `v1.0.0` is the name given to the version.
- `-m` adds a message describing the tag.
- `git tag` lists all available tags.
- `git push origin v1.0.0` uploads the version tag to GitHub.
- `git show v1.0.0` displays information about the selected tag.

## Result

The repository was documented using a README file. A version tag named v1.0.0 was successfully created and pushed to GitHub.
