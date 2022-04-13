## https://anarchists.gay/

since this is a public repository, you may not want your name attached to the commit logs.

## option 1

make a new github account, and only make changes to this repository using github's web interface

## option 2

edit and commit locally, but commit without your typical configured name and email address. run these in your terminal while inside this repository (you only have to run these once):

```
git config --local user.name 'anarchists.gay'
git config --local user.email 'noreply@anarchists.gay'
```

after making a commit, run `git log` to verify that the commit you just made has the correct information, e.g.

```
git log

commit 5931058f519b1985c758b6437a6918bc0683d0ec (HEAD -> main, origin/main)
Author: anarchists.gay <noreply@anarchists.gay>
Date:   Thu Mar 31 22:46:40 2022 -0400

    first commit
```
