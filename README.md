# cohort2026-HTML-assin

This is my first Resume page (cohort2026 HTML assignment) #open https://janardan-mondal.github.io/cohort2026-HTML-assin/

#How you can deploy like me ?

step-1 : Create a index.html page that was our assignment task.
step-2 : Open your github account and create a new repository with README.md . 
step-3 : Run in VS Code terminal-> a) git init, b) git add . , c) git commit -m "<your comment>"
step-4 : Please check the branch of git in local and github server also, if not same then ***Note 
step-5 : Now run d) git remote add origin <your created respo link> , e) git push -u origin main , to push your index.html to github.

Here might be and error... 
! [rejected] main -> main (non-fast-forward) error: failed to push some refs to <your created respo link> Because you have README.md in github respository but not in local machine.
So, solution will be **) git pull origin main --rebase (if the rejection come), This command must be run before "d)" then run d),e)

***Note -To get parmanent solution -> if in github indicate "main" branch and your local machine (VS Code -> terminal -> git branch) indicate master then you must run "git config --global init.defaultBranch main" in terminal and create another github repository and delete .git file from HTMLAssignment folder then try from step-1
