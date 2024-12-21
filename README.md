# version-control-Task


## What is Version Control?  
Version control is a system that tracks changes to files over time, allowing you to recall specific versions later. It is essential for collaboration and maintaining code history.  

## Git vs GitHub  
- **Git**: A distributed version control system that runs locally on your machine to manage project history.  
- **GitHub**: A cloud-based platform that hosts Git repositories, making it easier to collaborate with others.  

## 3 GitHub Alternatives  
1. GitLab  
2. Bitbucket  
3. SourceForge  

## Git Fetch vs Git Pull  
- **git fetch**: Retrieves changes from the remote but does not merge them into your working directory.  
- **git pull**: Fetches and automatically merges the remote changes into your current branch.  

## Git Rebase  
Rebasing integrates changes from one branch into another by moving commits to the tip of the branch.  
```bash
git rebase <branch>
git rebase main

## Git cherry-pick
 Allows you to apply specific commits from one branch to another without merging the entire branch.
 git cherry-pick <commit-hash>
