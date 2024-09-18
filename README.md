Guide to push  file or folder to github from Local  to Online.
first create a folder using Terminal in visual studio.(mkdir ABC).
then creat html or css ar any file of our projekt.
there will be no hidden folder at first (.git)(ls -a) when creating object local.
therefore we have to inilitize it using code ( git init)
now to show hidden file we write(ls -a) and it shows the file name(.git)
After making change in Visual Studio  code it shows U in green color it means untracked files.
to see untracked files we write or to see status what is happening (git status)
to add or stage the files we write the code(git add . )it means to add all the untracked or changed files.alternative(git stage ABC)
then the file has to be commited (git commit -m "Message")
After commit-- this changes are made only in local until  now
We have to create a new reposotory (folder ) in github.com
To push the code to online we use the following codes
(git push origin <-link of the reposotory>)
we can verify if its pushed(git remote -v)
we can also check the branch(git branch)by default branch name is Master
Master and main branch are different
(git branch -M main) with this code we renamed the master branch to mains
(git push -u origin main) finally it pushed to origin that means its now online in github.com
-u means it is the upstram .from next time we can use only the code(git push).If we want to work long time in a same projekt it is  very useful.
to delete the file we use the code (git rm (file path))then we have to commit and finally pushed.
(git checkout -b (NAME))to create a new branch
(git branch) to see in which branch we are now
(git checkout (NAME)) to change to NAME branch
(git branch -d (NAME) ) to delete a branch
(git diff (Branch name)) to see difference with that branch
(git pull origin main)used to fetch and download content from a remote repo and immidetely update to local repo
(git reset (file name))to go to previous version before add command or simply (git reset) for multiple reset
(git reset Head~1)to go one commit before
(git reset <-commited hash>)to go multiple commited before
(git reser --hard <-commited hash>)same as above but it shows the changes also in vscode.



