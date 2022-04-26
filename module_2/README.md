# Subtasks 11-20

#### 16. View commits from last week
```sh
git log --after={2022-04-17} --before={2022-04-24}
git log --before='last Friday'
```

#### 17. View commits by "Laura Pacilio"
```sh
git log --author='Laura Pacilio'
```
The latest commit was:
```sh
commit e68ad5ec463fbfa2a9c19abc54f60efb4b779141 (origin/update-TF-WORKSPACE-variable)
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Wed Apr 20 18:57:50 2022 -0400
```

#### 18. Were there any commits from "Laura Pacilio" during 2022-10
```sh
git log --author='Laura Pacilio' --after={2021-08-31} --before={2021-09-30}
```

Yes, there were 11 commits, the last one was:
```sh
commit 8f09e27597c9e792d7d9acea158429f10269572d
Merge: 5386d6c5b c8e2be76d
Author: Laura Pacilio <83350965+laurapacilio@users.noreply.github.com>
Date:   Mon Sep 20 17:24:31 2021 -0400
```

#### 19. For {22-04-26} - No. The last commit was on 22-04-20
```sh
 git log --author='Laura Pacilio' --before='Today'
```

#### * Why the date for a commit is 16.04.22?
```sh
git log --after={2021-04-20} --before={2021-04-21}
```

Quick google [search](https://stackoverflow.com/a/26956694) says that a local 'GIT_AUTHOR_DATE' could be set.