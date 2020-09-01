# SSD-Lab-Activity-2

#### Created new repo from github UI

#### Cloned the repo using SSH
* `git clone git@github.com:sailee-shingane/SSD-Lab-Activity-2.git` : SSH keys were already configured on the system.

#### Git workflow

* `cd SSD-Lab-Activity-2`
* `mkdir LabActivity2`
* `touch README.md`  
* `git status`
* `git add README.md`
* `git status`
* `git commit -m "Adding README.md"`
* `git status'
* `git log`


#### Add Another file

* `touch hello_world.txt`
* `git status`
* `vi README.md` : Added text "This is my first git project!"
* `git status`
* `git add README.md`
* `git status`
* `git add .`
* `git status`
* `git commit -m "Adding hello_world.txt and updating README.md."`
* `git status`
* `git log`


#### Push Work to Github

* `git push origin master`
* `git status`


#### Create Pull Request and Merge new_branch

* `git checkout -b new_branch`
* `touch test.txt` : Created the file in SSD-Lab-Activity-2 folder
* `git add test.txt`
* `git commit -m "Adding test.txt"`
* `git push origin new_branch`
* Created a PR from github UI and merged the new_branch to master branch. This can be done from bash as well navigating to master <p>`git checkout master` and then <p>using `git merge new_branch -m "Merging new_branch"` <p>`git push origin master`
* `git checkout master` <p> `git branch -D new_branch` : locally deletes `new_branch`
