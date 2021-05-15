==========================================git command==================================================

============git initialization==============================
============================================================

folder create ==mkdir(folder name)
file create == touch(file name)
go into folder == cd
back from folder == cd../

initialized git == git init
download from github == git clone (link here)

show the folder list  ==ls

modified any kind of status == git status
where i am right now        == pwd

==========================================local to stage==================================================
to take stage == git add --all,/git add -A

if i want to get bact to local ==git reset
if i take the specific folder files to the stage  the command == git add .//this is the best way
* it will take all files without deleted files! == git add *
if i want to take the files with the specific extention  == git add *.txt


==========================================stage to local repository==================================================
if i want to commit all things so == git commit -m"what kind of changes i have done!"
Now from at the stage if i want to go back to the local directory == git reset HEAD~
IF i want to take back deleted files so that == git reset --hard

==========================================git Remove==================================================
if i want to delete or remove the files  == git rm files.txt
if i change the files but didnt knew the git and that time if i want to delete the files git dont do that and it will not work
if i write the command like this == git rm files.txt  || it will work == git rm files.txt -f



@)if i want to inform to git that i want to change the files but i dont want to delete the files from the working directory  == git rm --cached files.txt

@) now if i want to delete the files from the very deep nested folders so == git rm -r folder


==========================================branch crate and work move to one branch to another branch!==================================================


@)if you want to know that how many branch you have than == git branch

@)if you want to go one branch to another branch so == git checkout'branch name';

=====here is most interesting things is that every branch has their own structure and design controll each branch will not mixt up with another branch!=
 
@)if i want to merge with another branch == git merge 'branch name' -m "what i have changed?"



============================================================merge conflict==========================================================================
if your partner change the file together like you and your partner working at the same stage and same thing and after that if you want to 
make them merge with the another branch then it will be conflict . 

and after that the git will give the chance to take decition to us!



============================================================Local to Remote ==========================================================================
if i want to move the file from local to remote than it will be == push

and if i want to take only changes files from remote than it will be  == fetch

and if i want to take all files changes and without changes files then the command will be  ==  git pull ;|| so the git pull==git fetch+git merge





============================================================Local to Remote ==========================================================================

@)remote means == origin

@)so if you want to push the all files from local to remote the command == git push origin "remote branch name"

@)if you want to take the all changes files from remote to local then the command will be === git fetch 
@) and after that you have to again need to do command if you want to see the changes from remote the command will be === git merge

@) and now this is improtant and time safe if you write the command === git pull || so that it directly fetch the files and merge it together







                                                         " That's all Thank you so much! "















