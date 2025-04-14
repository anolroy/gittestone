`git init` _To initialize git in your directory_

`git status` _To see the files / directory status, Here status means the status of the files whether those are untracked or not, needed to add or not etc._

`git add .` _To add any changed or untracked file into stage._

`git commit -m "my commit message"` _commit the staged files with a message_

`git push` _To push the commits into remote repository_

`git branch` _To see all the branches and your current branch_

`git log` _To see the commits with details_

`git log -2` _To see last 2 commits_

One flow

git checkout development _
git checkout -b dev-2  _
//now make change in code  _

git add . _
git commit -m "Your update message"  _
git push origin dev-2 _

git checkout development _
git pull origin development  # Make sure it's up to date
git merge dev-2
git push origin development

git checkout main
git pull origin main
git merge development
git push origin main
