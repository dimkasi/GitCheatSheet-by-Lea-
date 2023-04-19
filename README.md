# Git Cheat Sheet

![GitHub logo](https://lthub.ubc.ca/files/2021/06/GitHub-Logo.png)

## Setup and Unit
_git init_ - initialize an existing directory as a Git repository  
**git clone [url]** - retrieve an entire repository from a hosted location via URL

## Stage and Snapshot
1. git status - show modified files in working directory, staged for your next commit
2. git add [file] - add a file as it looks now to your next commit (stage)
3. git reset [file] - unstage a file while retaining the changes in working directory
4. git diff - diff of what is changed but not staged
5. git diff --staged - diff of what is staged but not yet commited
6. git commit -m “[descriptive message]” - commit your staged content as a new commit snapshot

## Branche and Merge
+ git branch - list your branches
+ git branch [branch-name] - create a new branch at the current commit
+ git checkout - switch to another branch and check it out into your working directory
+ git merge [branch] - merge the specified branch’s history into the current one
+ git log - show all commits in the current branch’s history

## Rewrite History
`git rebase [branch] - apply any commits of current branch ahead of specified one`  
`git reset --hard [commit] - clear staging area, rewrite working tree from specified commit`

## Share and Update
- [ ] git remote add [alias] [url] - add a git URL as an alias
- [ ] git fetch [alias] - fetch down all the branches from that Git remote
- [ ] git merge [alias]/[branch] - merge a remote branch into your current branch to bring it up to date
- [ ] git push [alias] [branch] - transmit local branch commits to the remote repository branch
- [x] git pull - fetch and merge any commits from the tracking remote branch

### To learn more:
[Basic writing and formatting syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
 
  
   
    
     
       
        
        ## new changes 
        ## i m steelling Leas WORK 
        