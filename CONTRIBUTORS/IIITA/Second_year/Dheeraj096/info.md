Hello, I am Dheeraj bhardwaj 2nd year student at IIITA.


Github profile : https://github.com/Dheeraj096


Ques - What do you really understand from SSH keys? What are the advantages of using it?


Ans  - Basically from my understanding SSH keys are secure alternate to email and password like we don't have to write everytime email and password for authentication. SSH key  is automated for implementing single sign-on system method. It comes in pairs <public and private>  public key -  sharing with github. private key - stays on local machine. As when both keys matches we are allowed to make changes.

  Advantage:-
  
  SSH keys are much securer and easier because we don't have to write anything email and password. Also there is no chance of spelling mistake.
  
  It easily identify yourself no one can identify our private informations like password.
  
  Answering issue of #366
  Ans:- After making two commits and making PR
  Checking branch with git checkout -b my_branch_with_extra_commits
  then opens git console using gitk
  then look for the commit that we want to keep  and copy the SHA of that commit.
  then git checkout my_branch
  then gitk
  then right click on the commit we want to revert
  then do a git pull --rebase origin branch_name_to_merge_to
  then git cherry-pick <SHA we copied earlier
