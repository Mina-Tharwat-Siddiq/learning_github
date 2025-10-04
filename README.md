# learning_github
# First day in github, I learned how to make repo and get clone from it using following command:
### git clone ***-->(Link of repo)<--***
# Second day and I learned the following:
### my machine has 3 steps before remote repo , They are  [1] Working directory [2] Staging area [3] local repo first of all to know status about files where in those steps we use ***-->(git status)<--***
### To send data from **working area** to **staging area** we use command -->***git add -->(File name)<--***<-- or add all files -->***git add ***<-- ---- to cancle that action we use -->***git rest head (File name)<--***
### To send data from **Staging area** to **local repo** we use ***-->git commit -m "text to explain what I did"<--***

# Third day: I learned the following commands:
### ***-->(git branch)<--*** We use it to know how many branches are avilable in local branch , ***-->(git remote -v)<--*** We use it to know the remote repo
### ***-->(git push origin main)<--*** This command used to push data from **local repo** to **remote repo** after using these commands ***(git add fileName , git commit -m "message to explain")***
### ***-->(git pull origin)<--*** To get all updates happened in the remote repo ,**git pull** do two things ***fetch*** and ***Merge***
### ***-->(git config -l)<--*** To display configurations list & ***-->(git help config)<--*** To open configuration website & ***-->(git config --global --edit)<-- *** To open vsCode and edit configurations.
### ***-->(git config --(global or local) user.name)<--*** To get username or ***-->(git config --(global or local) user.email)<--*** To get user email
### ***-->(git config --(global or local) user.name "mina-tharwat")<--*** To set username & ***-->(git config --(global or local) user.email "mina@gmail.com")<--*** To set user email.
### ***-->(git config --global --unset user.name|email)<--*** To unset user name or email
### ***-->(git config -l --show-origin)<--*** It Shows Where This Configurations come from.
# Fourth day: I learned how to make repo on my pc and upload it to github using the following instructions:
### [1] Make folder and name it anything then move to this folder and write this command ***-->(git init)<--*** to convert this folder from normal To github repo
### [2] Create any file inside the repo ex) index.html and then move it from **Staging area** to **Working area** using ***-->(git add fileName)<--*** then  move it from **Working area** to **Local repo** using ***-->(git commit -m "message")<--*** 
### [3]  ***-->(git remote add origin git@github.com:Mina-Tharwat-Siddiq/e-commerce.git)<--*** We use this command to add the repo that I have made on remote repo then we move changes from **Local repo** to **Remote repo** using ***-->(git push -u origin master)<--*** we use **-u** to make pull and push from and to the repo at the same time.
# Day Five: I learned how to make branch and push changes to master of the same repo **OR** push changes to .... using these instructions:
### ***-->(git branch)<--*** to know the available branches.
### ***-->(git branch branchName)<--*** To create new branch.
### ***-->(git branch -b branchName)<--*** To create new branch and move to it.
### ***-->(git checkout brancName)<--*** To move from one branch to another.
### ***-->(git branch -d branchName)<--*** To remove this branch **but if it contains it will not be deleted**.
### ***-->(git branch -d branchName)<--*** To remove this branch **Force delete even if this branch contains data**.
