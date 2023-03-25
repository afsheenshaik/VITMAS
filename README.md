# VITMAS
Git Repository with all git commands listed the readme file with its Use and syntax
git init:
To initialize a Git repository for our local project folder; git init [repository name].
git add:
To add the specified file(s) into the Git repository; git add [file(s) name].
To take all our files into the Git repository; git add . or git add *.
git commit:
To record or snapshot files permanently in the version history; git commit -m “message”.
git status:
To show the modified status of an existing file and the file addition status of a new file, if any, that has to be committed; git status.
git remote:
To remote the repository of the project; git remote add origin “[URL]”.
git push:
To make some changes in the file and want to push the changes to our remote repository on a particular branch; git push origin [branch name].
git clone:
To import the files of a git revert; git clone [URL].
git branch:
To handle the workspace of multiple developers; git branch [name-of-the-branch].
git checkout:
To navigate to an existing branch, add new files, and commit the files; git checkout [name-of-the-new-branch].
To create a branch and navigate to that particular branch at the same time; git checkout -b [name-of-the-new-branch].
git log:
To check the log for every commit in detail in repository; git log; git log –graph; it log –graph –pretty=oneline.
git stash:
To save our work without staging or committing the code to our Git repository and want to switch between branches; git stash.
To stash the untracked files; git stash -u.
To retrieve the code; git stash pop.
git revert:
To undo; git revert [commit id].
git diff :
It is a multi-use Git command which, when executed, runs a diff function on Git data sources; git diff [commit-id-of-version-x] [commit-id-of-version-y].
git merge:
To combine two branches; git merge [another-file-name].
git rebase:
It is the process of moving and combining a sequence of commits to a new base commit; git rebase [base].
git fetch: 
The command git fetch, Git gathers any commit from the target branch that does not exist in our current branch and stores it in our local repository; git fetch.
git reset:
To return the entire working tree to the last committed state; git reset –hard [SOME-COMMIT].
git pull: 
The git pull command first runs ‘git fetch’ which downloads the content from the specified remote repository and then immediately updates the local repo to match the content; git pull origin master.
