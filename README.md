### Learning Git

| Commands   | Purpose |
|------------|---------------------------------------------|
| git status | checks the status of current git repository |
| git init   | initialize a new git repository  |
| git add --a / git add . / git add fileName | add files to git|
| git commit -m "your-commit" | commits your files or changes |
| git push | push the changes to github repository |
| git pull | pull the changes from firhub repository that you haven't locally |
| git log | list of all commits of repository |
| rmdir /s /q .git | deletes the .git folder ( for windows ) |
| git clone "github repository url" | clone the github repository |
| git clone "github repository url" "custom name" | clone the github repository named with your custom name |
| git diff | see the difference between staging area and working directory |
| git diff --staged | see the difference between last commit and working directory |
| git commit -a -m "your commit" | skip the staging area  ( all tracked files will be staged but untracked files not be staged ) |
| git rm "fileName" | delete the file |
| git mv "fileNameToChange" "updatedFileName" | rename the file |
| git rm --cached | untrack .gitignored files |
| git log -p | see all the diferences in previous commits |
| git log -p -3 | see the last 3 commits with difference ( you can also provide your own number of commits ) |
| git log --stat | see a short summary of previous commits |
| git log --pretty=oneline | see summary of all previous commits in one line |
| git log --pretty=short | see a short summary of all previous commits |
| git log --pretty=full | little more detailed summary of all previous commits |
| git log --since =2.days | see all commits of last 2 days ( you can also provide your own number of days ) |
| git log --since =2.weeks | see all commits of last 2 weeks ( you can also provide your own number of weeks ) |
| git log --since =2.months | see all commits of last 2 months ( you can also provide your own number of months ) |
| git log --since =2.years | see all commits of last 2 years ( you can also provide your own number of years ) |
| git log --pretty=format:"%h -- %an" | format your all commits according to your needs ( see "%h and %an" and others in git scm documentation ) |
| git commit --amend | edit your commit ( use in rare cases ) command to exit from editor (i, esc, :, wq) |
| git restore --staged fileName | unstage file |
| git checkout -- fileName | get all the data from previous commit for that file ( if you delete accidentally ) |
| git checkout -f | get all the data from previous commit for all files |
|