we have to run" git inti" for creating git repository
#for checking status we use "git status"
for adding to track we use"git add foldername/" for single file
for total project we use "git add ."
for restoring  "git restore file name
"
for commiting
1.add changed files -status:staged
2.commit:records the changes
git commit -m "add message" with double quotes

for sending local files to github repository
create a brach for experimenting on it by "git branch -M main" if needed 
1.create any new repository without adding 1.readme.md and gitignore 

2.copy the link of the new repository and run 
  "git remote add origin "link"" for making default
  for checking "git remote -v"
  3.then use "git branch" for checking  we can see "main"
  then git push -u origin main //-u for upstreaming next time only git push 
  4. use git commit -m "new message" 
  now we need to connect to our github for that :git push -u origin main
  then every thing will be aadded to our new git repo
   now origin targets the repo and main creates the branch
   5.for creating new repo we use:git inti 
   order of flow :
   1.git init
   2.git remote add orgin "link"
   3.git remote -v //to verify
   4.git branch //checking 
   5.git branch -M main //changing name to main
   6.git push origin main //pushing into github if we use git push -u origin main then for next updating just git pull
   now every thing is ready

use git commit -am "and and commit at together "



