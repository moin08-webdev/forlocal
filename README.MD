# from local

for push local repo to remote
first make directory on github account

and than use 

# use: git add origin main <link>

# for verify above process use
git remote -v

# for check branch
git branch

# for rename branch
git branch -M name

# for push our code 
git push origin main
here main is branch name

# if we write 
git push -u origin main
it means we are declaring origin as main
than we can arite only "git push"

# note 
if we have modified a file and we havnt made anew file so we can add and commit together by using 
git commit -am "some messaege"

# branches

<for rename branch> git branch -M name
<for checkout> git checkout "branchname" <!--it means you can change branch by usng this -->
<for make new branch> git checkout -b "new branch name"
<for delete asny branch> git branch -d "branch name"
<note if we make a new branch we upstream that branch before pushing usimng git push --set-upstream origin feature>
<if we want to merge branch to main branch>
  we can use three mathod
  <note whichever branch we want to merge we must have to stay in that branch>
  1. show diffrence between two branches 
  git diff <branch name>
  2. to merge with help of git
  git merge <branch name>
  3. we can merge with PR(pull request)
  from github < when we make PR in github the side branch merges to main branch in github but
    in our local system nothing chenges ocurrs so merge branches in local system we use pull command>
    <git pull origin main>

<fixing mistakes>

if accidentaly we add any file which we dont wanted to add we can reser it using
<git reset "file name">
for every file 
<git reser>