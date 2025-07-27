Before interactive rebase
git log --oneline
62dd37d (HEAD -> development) Add line 6
c220aca Add line 5 new_text
4a26d8d Update new_text
8429da0 (master) Initial commit

After interactive rebase
git log --oneline
ae18db3 (HEAD -> master, development) Update new_text
8429da0 Initial commit

git reflog

ae18db3 (HEAD -> master, development) HEAD@{0}: me
rge development: Fast-forward
8429da0 HEAD@{1}: checkout: moving from main to ma
ster
ae18db3 (HEAD -> master, development) HEAD@{2}: ch
eckout: moving from master to main
8429da0 HEAD@{3}: checkout: moving from developmen
t to master
ae18db3 (HEAD -> master, development) HEAD@{4}: re
base (finish): returning to refs/heads/development
ae18db3 (HEAD -> master, development) HEAD@{5}: re
base (squash): Update new_text
70816bc HEAD@{6}: rebase (squash): # This is a com
bination of 2 commits.
4a26d8d HEAD@{7}: rebase (start): checkout HEAD~3
