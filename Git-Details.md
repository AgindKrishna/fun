Version Control 

Collabration 


LVCS(Local Version Control system )
CVCS(Centrliced Version Control System )
DVCS(Distributed Version Control System)

Create a project folder testProject

git init -b main (need to change master to main)

now the test project has .git folder 

so create our works files test.txt

now we can add that in to git so git add test.txt

ok  now the test file is traking on staging now we can add commits

so add git commit -m "this is my first commit "

when we modifiy the file test.txt it will add modified version 

so we need to commit the changes then do first add the file to statging then git add test.text then 

git commit -m "it will 2nd commit"

so we sussess fully updated ouer sectond commit 

so we need to see how much commits we done do that git log

now we need to add commit directly with out git use 

git commit -a -m "this will be the thrid commit "

so it will add directly to the commit with out going the staging

Now    if We want to see what the diffrent are chaged using on working directory ------ git diff

if our file should be in staging it no work git diff so use git diff --staged

How to remove file directory form git : git rm --cached test.txt

We need to clone some items to our computer so git clone Url


clone 
git clone <url>

need to list git commit and it id listed formet


…or create a new repository on the command line
echo "# fun" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/AgindKrishna/fun.git
git push -u origin main




git remote add origin https://github.com/AgindKrishna/fun.git
git branch -M main
git push -u origin main


We Can Also use SSH : ssh-keygen -o

need to see how much origin we have 

git remote -v

now we can use some tag for our projects releases 

git tag v1.01 -m "New releases"

to see how many tags we have .
git tag 

now we can push the tags live 

git push origin <tagname>

in our case

git push origin v1.01

git log --pretty=oneline

Creating branch

git checkout -b branch3