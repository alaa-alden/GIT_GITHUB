#the first tutorial :

  git is reversion control system , a tool manage your source code history
  git-hub is a hosting service for git repositories

#the second tutorial :

git --version
git config --global user.name .... // empty for query

git config --global user.email .... // empty for query

\\ make file : touch file.*

\\ open file by program : program file.*

\\remove folder :rmdir folder

#the fourth tutorial:
git intit

#the fifth tutorial :
modified --> staging --> committed
\\ what statue all file and folder in App ??? :
  git status
\\convert file from modified to staging area :
  git add file.*
  *#OR for all files*
  git add .

\\ remove file from staging :
  git rm --cached file.*


#the sixth tutorial  :
  \\ convert staging to commit :
    git commit -m "message"

  \\ show all changing of commit and all explain
    git log
    \\ show all changing but not explain :
      git log --oneline
#the seventh tutorial :
    \\ back or front your update app by :
      git checkout number-update */or name ex : master/*
    \\where update of your app :
      git revert number-update */or name ex : master/*  wq
    \\remove all update after this   number-update */or name ex : master/* :
    git reset number-update */or name /* */ --hard/*


#the eighth tutorial :
  \\create new branch :
    git branch name
    **/or git checkout -b name /**
  \\show all branch :
  git branch -a
  \\ select branch :
  git checkout name-branch
  \\ delete branch :
  git branch -D name
