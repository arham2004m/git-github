# All concepts and Commands used in Github
git installation - git scm;
stages:-
U - untracked 
A - added or staged
C - Commited
# Commands you need to know
->git status -s => to know current status of unstaged and staged files
->git log oneline => to know current status of saved points
# Managing your own projects
-> Managing locally - git
-> Managing over internet - github(central codebase)
making git available in our project - git init;
making a checkpoint or saved point - git commit -m "Some Message";
adding files - git add <-filename> or git add .  ;
staging them - when add command is exec. changes are staged ;
commiting them - git commit -m "some message" ;
going back to some previous saved point - git checkout "commitID" or git reset --hard/soft/mixed HEAD~2(i.e.RollbackCount)
logging everything
reverting back to the previous saved point