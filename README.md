•	To Connect Git And GitHub 
In Git
$git config --global user.name "name of your github account"
$git config --global user.email "email of your github account"

•	To connect git with github
Get SSH Key
step 1:  $ ssh-keygen -t rsa -f ~/.ssh/id_rsa <<< y
step 2:  cat  ~/.ssh/id_rsa.pub
step 3: copy the generated key 
step 4: Open GitHub> Settings>SSh and GPG keys
step 5: Title the SSh key and Paste the Key and save 
then finally ,
$ ssh -T git@github.com
You've successfully authenticated, but GitHub does not provide shell access.


•	In GitHub 
Create a Respositiory and also Create a Folder On your Local system 
then Open the folder in the vscode and bulid yout project

In vscode terminal ,
step 1: Initialize the git 
$git init
step 2: Add the file to the git to Track 
$git add ./add "filename"
step 3: Conform adding the file to the git 
$git commit -m "Message"
step 3: To connect remote github to the local git 
$git remote add origin "your github Repositiory Url"  
step 4: Again Follow the Process
$git add . 
$git commit -m "Message"
step 5: To Push /Upload the files in to the github using git                
$git push -u origin master     
step 6: There Is a Authentication of your account Dialog Box will display                
Then Authenticate your account
step 7: To Check the status of the processes in the git                
$git status  
step 8: then Refresh the github account To see the changes that you made 
step 7: To Again Push /Upload the files in to the github using git                
$git push origin master
