# git-task

Version Control is the practice of tracking and managing changes to a file.


Git and Github

- Git is a version control system used for tracking andrecording changes to a file overtime.
- Github is a version control platform that allows users to share and contribute to project and collaborate with one another.


3 other Github alternatives

- GitLab
- Bitbucket
- SourceForge


Git fetch and Git pull

- Git fetch downloads changes from a remote repository to your local repository but doesn't automatically merge or modify your working directory. It's useful for checking what changes exist before deciding to merge.

- Git pull fetches changes from a remote repository and automatically merges them into your current branch, updating your working directory.


Git rebase and its command

- Git rebase rewrites commit history by moving or combining a sequence of commits to a new base commit. It's often used to maintain a clean, linear history.
command: git rebase branch-name


Git cherry-pick and its command

- Git cherry-pick selects a specific commit from one branch and applies it to another. It's useful for applying specific changes without merging entire branches.
command: git cherry-pick <commit-hash>
