1. Create a folder for your git repository and initialize the new git repository in that folder.

mkdir git
cd git
git init

2 Write one program in your repository which will be print "Hello World" and commit your program file.(You can use any programming language)

vim hello.js
git add hello.js
git commit         # bacvac failum grum enq commity

3.Add a function to your program which will print "Second Commit" and with that create second commit.

vim hello.js      # popoxutyun enq katarum
git add hello.js
git commit        # nor commit enq grum


4. Create a new branch from master and add a function to your program which will print "New branch" and with that create commit.


git branch new_branch

5. Create another branch from master and use revert to revert the last commit.

git branch new_branch1
git checkout new_branch1
git revert d02e94f775dba8514e13edae15ad2ef3da77792

7. Merge second branch to first branch.

git checkout new_branch
git merge New_branch1

