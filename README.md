# Assignment 1

- Name : Haniif Satria Wardana
- ID : 2702358065
- Class : L4CC

# Git Clone

Here we'll examine the git clone command in depth. git clone is a Git command line utility which is used to target an existing repository and create a clone, or copy of the target repository.

# Git Fork

Forking a repository means creating a copy of the repo. When you fork a repo, you create your own copy of the repo on your GitHub account. When several developers want to work on a project but need to make changes that are inappropriate for the original repository, forking is frequently used in open-source software development.
# Git Push

The git push command is used to upload local repository content to a remote repository. Pushing is how you transfer commits from your local repository to a remote repo. It's the counterpart to git fetch, but whereas fetching imports commits to local branches, pushing exports commits to remote branches. Remote branches are configured using the git remote command. Pushing has the potential to overwrite changes, caution should be taken when pushing. These issues are discussed below.

# Git Pull

he git pull command is used to fetch and download content from a remote repository and immediately update the local repository to match that content. Merging remote upstream changes into your local repository is a common task in Git-based collaboration work flows. The git pull command is actually a combination of two other commands, git fetch followed by git merge. In the first stage of operation git pull will execute a git fetch scoped to the local branch that HEAD is pointed at. Once the content is downloaded, git pull will enter a merge workflow. A new merge commit will be-created and HEAD updated to point at the new commit.

```bash
git pull
```

# Git stash

git stash temporarily shelves (or stashes) changes you've made to your working copy so you can work on something else, and then come back and re-apply them later on. Stashing is handy if you need to quickly switch context and work on something else, but you're mid-way through a code change and aren't quite ready to commit.


![image](https://github.com/user-attachments/assets/6ae59190-9d71-41b1-ae5a-edde6c949005)

![image](https://github.com/user-attachments/assets/898232c8-8499-46c4-9386-90ec5eafa4bc)

![image](https://github.com/user-attachments/assets/898232c8-8499-46c4-9386-90ec5eafa4bc)
 

 # Git Revert
 The git revert command can be considered an 'undo' type command, however, it is not a traditional undo operation. Instead of removing the commit from the project history, it figures out how to invert the changes introduced by the commit and appends a new commit with the resulting inverse content. This prevents Git from losing history, which is important for the integrity of your revision history and for reliable collaboration.
