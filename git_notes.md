# Get started

1. Make a repository in GitHub
2. On the terminal, move to the folder where you want your local copy of this
repo to be, and clone it using: `git clone [file path]`.


# Git flow
git status (when using it, need to be in the repo)
# Git stages

1. Unstaged

2. Staged

3. Committed

4. Live

## Moving from one stage to the next

1. `git add` . - from unstaged to staged

2. `git commit -m "Commit description"` - commit any staged files

3. `git push` - upload committed files to GitHub (has no arguments, takes everything in the current file)

# Git commands

* `git log` - History of commits
* `git log --oneline` - Shorter history of commits
* `git checkout [nr of commit]` - set the current version to an older commit.
Tags can be used as shortcuts instead: `git checkout [tagname]`
* `git checkout master` - set the current version to the most recent on the master brach
