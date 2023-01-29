Youssef
My First Readme

##AlX SE

•	Git

Create repository and file and all u want then 

Git add .

Git commit  -m ‘the is a commitment message’

Git push 
-------------------------------------------------------------------------------------------

Git config –global user.name “write the username”
Git config –global user.email “write ur email”
-------------------------------------------------------------------------------------------
 
If u want to download a specific file on a specific location, enter the location using cd command and after that use 
Git clone (paste the https or ssh link of ur repository)
-------------------------------------------------------------------------------------------

The following code will give u access directly to push ur data without the need of username and password but first make sure to create a github clasic token with all permission (Note: replace the words in <> with ur own personal data).

git remote set-url origin https://<githubtoken>@github.com/<username>/<repositoryname>.git
-------------------------------------------------------------------------------------------

git branch <enter a branch name> ----- to create a branch but make sure that u r working on the repository file (cd)
git checkout <branch name> ------- to switch the branch 
-------------------------------------------------------------------------------------------

use the following in order to make a push in a branch rather than the main branch 
  Note: git push --set-upstream origin <name of the branch>

