hello in readme file

Tell me how to remove them locally and remotely.
for Remotely 
git push origin --delete dev 

for locally 

git branch -d dev  

or 

git branch -D dev // if you merge 


Tell me how to checkout another branch without commit 
changes 

git stash 


Tell me how to list tags. 

git tag

Tell me how to delete tag locally and remotely. 

remotely
git push origin --delete v1.7

locally

git tag -d v1.7
