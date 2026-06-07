# basic
1 - initial git
```git
git init
```

```git
git config user.name "Sipan M. Hameed"
```

```git
git config user.email "Sipan.cloud"
```


```git
git config --gloobal user.name "sipan M. Hameed"
```

```git
git config --global user.email "sipan.cloud"
```

add and change files(pyhton_script)
add to stage
```git
git add pyhton_script
```
remove from stage
```
git rm --cached .\python_script.py
```


add first commit\=:
```
git commit -m "added new file python_script.py"
```

log:(show 1 commmit)
```
PS D:\Learn coding LLM\projects\git test> git log  -v                                    
commit f409a2f27e57fb07710bd96784802d582b4e9013 (HEAD -> master)
Author: Sipan <sipan.cloud@gmail.com>
Date:   Sun Jun 7 23:12:55 2026 +0300

    add new file python_script.py
PS D:\Learn coding LLM\projects\git test>
```

download git project
```git
git clone https://github.com/user/repo.git
```
9. Show Branches
```
git branch
```
List local branches.

10. Create Branch
```
git branch new-feature
```
11. Switch Branch
```
git checkout main
```

or modern version:
```
git switch main
```



13. Rename Branch
```
git branch -M main
```
Rename current branch.

14. Delete Branch
```
git branch -d old-branch
```

Delete local branch.

15. Add Remote Repository
```
git remote add origin https://github.com/user/repo.git
```

Connect local repo to GitHub.



16. View Remote URLs
```
git remote -v
```

Show linked repositories.


17. Push to GitHub
```
git push -u origin main
```

Upload code.

18. Pull Latest Changes
```
git pull
```
Download + merge updates.

19. Fetch Without Merge
```
git fetch
```
Download updates only.

20. Merge Branch
```
git merge feature-login
```
Combine branches.

21. Rebase Branch
```
git rebase main
```
Replay commits on top of another branch.
