# Git Learning

## For setup:

```
   git config --global user.name "your name"
   git config --globla user.email "your email"
```

## Basic Commands

- **git init** ----> _Initialize a repository_
- **git clone** ----> _Clone a repository_

## Git Links

[git link](https://github.com/RoadToDevOpsWorld/)

## Branching Strategy

 - Create a branch
 ``` 
 git checkout -b feature-branch 
 ```
 - Merge a branch
 ```
 git checkout main
 git merge feature-branch
 ```
 - Delete a branch 
 ```
 git branch -d feature-branch
 ```

 # Pull Requests

 ## commands for pull requests

 ```
    git push origin feature-requests
 ```

 ## On Github

 **Go to the repository**
    1.~~click~~ pull requests ---> New pull request
    2.Select base branch and compare branch
    3. Add title/description and submit