## Git Branching

### Basic Git commands

* `git init` - Create local repo
* `git add` - Add modified files to index (staging)
* `git commit -m "message"` - commit to local repo
* `git status` - See status of local repo
* `git log` - View commit log
* `git log --oneline` - Compact view of commit log
* `git remote add origin URL` - Connect local repository to remote URL


### Basic Branching
* `git branch` - Show branches, current branch
* `git branch branchName` - Create branch `branchName`
* `git checkout branchName` - Check out the branch
* `git checkout -b otherBranch` - Create and checkout `otherBranch`
* `git pull origin otherBranch` - Pull remote otherBranch
* `git pull origin master` - Pull remote master into local branch to resolve conflicts
* `git push origin otherBranch` - Push local branch to Github; go to Github and create pull request.
