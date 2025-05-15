Practicing Git in the below repo
https://github.com/Sukankrishnan/GitPractice

Commands:

1. git init

2. git clone https://github.com/Sukankrishnan/GitPractice.git

3. git checkout -b sukanya_branch

4. git status

5. git diff

6. git add learningGit.txt  (Status changed to 'A - Index Added') --> M - Modified

7. git commit -m "adding files"

8. git push origin

When you get error 

        fatal: 'origin' does not appear to be a git repository
        fatal: Could not read from remote repository.
        
        Please make sure you have the correct access rights
        and the repository exists.

Use:
git remote add origin https://github.com/Sukankrishnan/PlaywrightWithTypeScript.git

To unstage the added file in Index
git rm --cached -f learningGit.txt   (-f is used when the file is modified after added to index and forcing to untrack).

How to add collaborators to your git repo?
Go to Settings -> Collaborators -> Add people to contribute


git push
fatal: The upstream branch of your current branch does not match
the name of your current branch.  To push to the upstream branch
on the remote, use

    git push origin HEAD:master

To push to the branch of the same name on the remote, use

    git push origin HEAD

To choose either option permanently, see push.default in 'git help config'.

To avoid automatically configuring an upstream branch when its name
won't match the local branch, see option 'simple' of branch.autoSetupMerge
in 'git help config'.

git fetch
---------
It helps to know the changes made in the remote repository. But it does not make any changes to the working directory.
