# tasks of this repository

1. Created a new Gh repository for testing
1. Created local repository for testing
1. created a readme file having all the tasks
1. connected both local and remote repositories
1. created an html file with **hello galaxy** and pushed it in the remote repository
1. chaged something in the remote repository

# how I resolved merge conflict issue

I made a remote repository change which created a conflict. after that i changed in my local repo and and pushed it. then terminal showed me error and told me to give

```
git config pull.rebase true   # rebase
```

then i pulled it again and gave me hint to resolve all the conflicts manually and gave me a hint:

```
hint: "git add/rm <conflicted_files>", then run "git rebase --continue".
```

then I changed it manually and tried again and it pushed perfectly
