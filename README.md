# purging-passwords-from-git

```bash
git clone git@github.com:deadlift1226/purging-passwords-from-git
cd purging-passwords-from-git
l
echo "password" > password-file
gita
gitcm 'password posted'
gitpm
git rm password-file
git commit --amend --no-edit
l
gita
gitcm 'password file removed'
gitpm
ls
git pull --force
git reset --hard HEAD^
ls
git checkout -b temp 8dfcbd3
git rm password-file
git commit --amend --no-edit
git rebase --preserve-merges --onto temp 595f99a master
git diff master@{1}
l
gitpm
git push origin master --force
```
