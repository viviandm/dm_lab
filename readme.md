"#github_test" 
"#dm_lab"
############################## introduction about using git and github#################################
step 0: install git ,and  registe an account on github.com (using sign in)
step 1 : creat a repository on github 
("+" => choose new repository) 
record it's url (https://github.com/user_account/repository_name.git)

step 2:  choose a directory on your PC as your  local resposory,use " git init " to creat it as repository
in "git cmd",using:
cd path
git init

step 3: copy the directory or files you want to manage  to the directory, add and commit to the local repository
in  "git cmd",using:
"git add . " //"." means all the content in current directory   or   
"git add files' name "  

then using
"git commit -m "comments about commition"  "


step 4: if you want to update the github repository with the local one,using:
git remote add origin github url  such as  
git remote add origin https://github.com/user_account/repository_name.git

then 

git push -u origin master  (master is the default branch ,it  can also be replaced with other branch name)
