# Git Commands Cheatsheet

Here are some common commands used for git:

- **cd** - Change Directory
- **pwd** - Pring Working Directory
- **mkdir [name]** - Creates new Directory
- **touch [file-name]** - Creates new empty file
- **mv [original-file-location][new-file-location]** - Moves file from one location to another
- **cp** - Copies file from one location to another
- **rm** - Removes a file

## Configure Tooling

- **git config --global user.name"[name]"** - Set the name you want attached to your commit transactions
- **git config --global user.email "[email address]"** - Sets the email you want attached to your commit transactions
- **git config --global color.ui auto** - Enables helpful colorization of command line output

## Creats Repositories

- **git init [project-name]** - Creates a new local repository with the specified name
- **git clone [url]** - Downloads a project and it's entire version history

## Make Changes

- **git status** - List all new or modified files to be committed
- **git diff** - Show file differences not yet staged
- **git add[file]** - Snapshots the file in preperation for versioning
- **git diff --staged** - Shows file differences between staging and the last file version
- **git reset [file]** - Unstages the file, but preserve its contents
- **git commit -m "[descriptive message]"** - Records file snapshots permanently in version history

## Group Changes

- **git branch** - List all local branches in the current repository
- **git branch [branch-name]** - Creates a new branch
- **git checkout [branch-name]** - Switches to the specified branch and updates the working directory
- **git merge [branch]** - Combines the specified branch's history into the current branch
- **git branch -d [branch-name]** - Deletes the specified branch

## Refactor Filenames

- **git rm[file]** - Deletes the file from the working directory and stages the deletion
- **git rm --cached [file]** - Removes the file from version control but preserves the file locally
- **git mv [file-original][file-renamed]** - Changes the file name and prepares it for commit

## Suppress Tracking

- _.log build/temp-_ - A text file named .gitignore suppresses accidental versioning of files and paths matching the specified patterns
- **git ls-files --other --ignored --exclude-standard** - List all ignored files in this project

## Save Fragments

- **git stash** - Temporarily stores all modified tracked files
- **git stash pop** - Restores the most recently stashed files
- **git stash list** - Lists all stashes changesets
- **git stash drop** - Discards the most recently stashes changeset

## Review History

- **git log** - List version history for the current branch
- **git log --follow [file]** - list version history for a file, including renames
- **git diff [first-branch]...[second-branch]** - Shows content differences between two branches
- **git show [commit]** - Outputs metadata and content changes of the specified commit

## Redo Commits

- **git reset [commit]** - Undoes all commits after [commit], preserving changes locally
- **git reset --hard[commit]** - Discards all history and changes back to the specified commit

## Synchronize Changes

- **git fetch [bookmark]** - Downloads all history from the repository bookmark
- **git merge [bookmark]/[branch]** - Combines bookmark's branch into current local branch
- **git push [alias][branch]** - Uploads all local branch commits to GitHub
- **git pull** - Downloads bookmark history and incorporates changes

### Dev Enviorment set up (GA level)

- **Slack**
- **Zoom**
- **Homebrew**
- **Xcode**
- **VS Code**
- **Git / Github / Github Enterprise**
- **Global Gitignore**

- **Spectacle**
- **Imgur**
