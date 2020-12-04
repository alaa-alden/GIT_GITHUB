# the first tutorial :

 **git is reversion control system , a tool manage your source code history**
  
  **git-hub is a hosting service for git repositories**
  
---

# the second tutorial :

 ```git --version```
 
 ``` git config --global user.name ``` .... *empty for query*
  
 ```git config --global user.email``` .... *empty for query*
  
 **make file :** ```touch file.*```
  
 **open file by program:** ```program file.*```
  
 **remove folder :** ```rmdir folder```
  
---

# the fourth tutorial:

**go with project with git :**

 ```git intit```
  
---

# the fifth tutorial :

### modified --> staging --> committed
  
**what statue all file and folder in App ??? :**
  
```git status```
    
**convert file from modified to staging area :**
  
```git add file.*```
 
 *OR for all files*
  
``` git add .```

**remove file from staging :**

```git rm --cached file.*```
  
---
  
# the sixth tutorial  :

**convert staging to commit :**
  
```git commit -m "message"```

**show all changing of commit and all explain**
 
```git log```
    
**show all changing but not explain :**
   
```git log --oneline```
      
---
      
# the seventh tutorial :

**back or front your update app by :**
  
```git checkout number-update``` *or* **name** ex : master
    
**where update of your app by delete  fills or folder or code of a commit of a branch but not delete commit :**
  
```git revert number-update ``` *or* **name** ex : master *and* `wq`
    
**remove a commit of a branch** *or* **name** ex : master *by*:
  
```git reset number-update``` *or* **name** *-and->*`--hard`

  ---
    
# the eighth tutorial :

**create new branch :**
  
```git branch name```
    
*or* **create branch adn checkout**
    
```git checkout -b name-branch```
    
**show all branch :**

```git branch -a```
  
**select branch :**
  
```git checkout name-branch```
  
**delete branch :**
  
```git branch -D name-branch```

---

# the ninth tutorial :

**merge two branch s  when you in first branch:**

```git merge name-branch```

---

# the tenth tutorial :
  1.  **create repo in git-hub**
  2.  **push to :** ```git push url what_branch```  **replace url by name_url by used :**
  
  **name for url :** ```git remote add origin ```**for default**
  
  **show all remote by :** ```git remote -v```
  
  3. **and for all update by it push name name-branch**
  4. **for download repo from guthub :** ```git clone url```
  
  ----
  
# the eleventh tutorial:

**update all folder but not save so need save:**

  ```git pull URL name-branch```
  
**and update server-side compare with branch then merge**

---
# the twelfth tutorial:

**fork is upload app from any count in git-hub**

---

# note :
1. `git log` to show all commit of branch
2. `git branch -D <name-branch>` to delete branch
3. `git merge <name-branch-source>`  merge for current branch
4. `git rm file.?` to delete file both local and repository
5. `git rm --cached file.?` to delete only repository
6. `git push <remote_name> --delete <branch_name>` to remove branch on the server only
7. `git switch another_branch` to move to another an exsit
8. `git switch -c new_branch` to create and move to it
9. `git branch new_branch` to create with switch to it
10. `git branch -m <new-name>` to replace old name of a branch to new one
