git init: Initializes a new Git repository in the current directory, creating a .git subdirectory to store repository data.

git clone [repository_url]: Clones an existing repository from a remote server to create a local copy on your computer. It automatically sets up a remote named "origin" pointing back to the original repository.

git add [file(s)]: Adds file changes to the staging area in preparation for committing. This command stages changes to be included in the next commit.

git commit -m "[commit_message]": Records staged changes to the repository, creating a new commit with a message describing the changes. The -m flag allows you to specify the commit message inline.

git status: Displays the current state of the repository, including any modified, staged, or untracked files. It provides information about which files are staged for the next commit and which files are not being tracked by Git.

git log: Shows a chronological list of commits in the repository, starting with the most recent. It provides information such as commit hashes, authors, dates, and commit messages.

git branch: Lists all branches in the repository. It also indicates the currently checked out branch with an asterisk (*).

git checkout [branch_name]: Switches to the specified branch, updating the working directory to reflect the state of that branch. It's also used to create new branches by specifying the -b flag followed by the new branch name.

git merge [branch_name]: Merges changes from the specified branch into the currently checked out branch. It combines the changes made in the specified branch with the changes in the current branch.

git pull: Fetches changes from a remote repository and merges them into the current branch. It's equivalent to running git fetch followed by git merge.

git push: Pushes local commits to a remote repository, updating the remote branch with your changes. It's used to share your work with others and synchronize changes between local and remote repositories.

git remote: Lists the remote repositories associated with the current repository. It provides information such as the remote's name and URL.
