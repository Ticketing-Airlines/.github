## Hi there 👋
How to navigate github

Step by step guide to github
1. Repository - check if you are at the correct repository (e.g. Ticketing-Airlines/Backend)
open cmd prompt
navigate to where you want to copy code (e.g. to save in desktop, type cd desktop)
type:
  git clone (url of the repo)
  cd (name of the folder of the repo that you copied)

   
2. Branch - before you code always create a new branch, name it "feature" or "whatever-are-you-codihg-about"
type:
  git checkout -b (name of the new branch)

to check what branch u are on, type:
  git status
   
3. Do your code

4. When ready to commit, type:
   git add .
   git commit -m "label"
please use the following pattern for labeling ur commits:
feat - new features, big changes
fix - bug fixes
chore - others
e.g. git commit -m "fix: fixed this bug" or git commit -m "feat: added this feature"
finally, type:
   git push remote origin

5. Open github website
open ur repository
click pull requests
click new pull requests
make sure that it is showing main << yourfeaturebranch
write a title using the same patterns for labeling commits (feat,fix,chore)
click create pull request
message jose in fb so he can approve the request
Done!

Repeat step 2
   
