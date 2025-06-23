# custombookmark
to save all the website url use our own chrome extension

first commit 




first we add the files which copies or created 
git add filename or git add .


After add the files 
now we commit 

git commit -m "change the nav bar color according my 12345 ticket number in navbar-color-change branch"

after u commit it saves changes to you local git repository(code in laptop)



after commit push the code to remote repository
git push




we create a branch in github with name feature/add-new-nav-bar


in ur code git bash

everytime u create a new branch

run 
git fetch


git pull origin "from which branch  u create the new branch "
git pull origin main


to go into the new brancg new start write new code 

git checkout branchname
git checkout feature/create-new-nav-bar


then once add all the code in new branch again repeat 

git add .
git commit -m "added navbar"
git push



then come to github and click on pull request and create new pull request 

base === from which branch u create the current branch

then create pr and the merge ur code if review required add reviewers

there will be three main branches

then ur have fo back to ur main branch

then pull all the code into ur local

git pull origin main


main------live (which is deployed version and which under access to everyone)
staging ----non-live (this also deployed and before u deploy the main branch  u test staging  branch and site,if all ok then u merge ur code to main )
developement ---- it ur local code when u develop and test by ur self which deployed


feature --- adding new things to ur code 

bug  ---- fixing the problem in ur code


refactor --- if u have to rewrite the existing code in better way