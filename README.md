# [Website](https://carmenx.github.io/ "Carmen's website")
personal website 
will this ever get done?? who knows

designed with HTML / CSS / Javascript

| under construction for a while| deadline: august 2020 ish

background - floating bubbles / gradients 
Pages for about me / contact me / education / experience / volunteer / 

find tutorial like Wealthsimple UI/UX layout for the floating cards
add links to navigation bar 
remember to write content for website - include things like Nook / Udemy / Coursea 

tabs vs links to new pages - figure out what would look better - implement javascript so you can be able to toggle between tabs and to learn some stuff


git workflow
(first time setup) pull the repository git clone https://github.com/dryu99/infinite-animal-crossing-lofi.git
checkout into a new branch git checkout -b NAME-OF-BRANCH
make your changes, go wild!
tell git to track your changes by doing git add .
save your changes and give it a meaningful name by doing git commit -m "describe your changes here"
double check to see what git is keeping track of by doing git status
push those changes up to github git push origin NAME-OF-BRANCH
go to github and make a pull request!
merge it into master

common pitfalls
help! what do i do if my git says "failed to push some refs to origin"
you wanna pull your changes and do git pull origin master
help! i wanna revert to an earlier version!
find the last time you saved your work by doing git log and keep track of the hash
then git reset --hard <hash>
how do i update my local version to be up to date with github?
git pull origin master
how do i switch branches?
git checkout NAME-OF-BRANCH
  
  revert 
` git reset --hard HEAD^

why is the ^ important 

git push -f 

=f = force - allows you to overwrite the remote stuff with what you have locally even with out of sync

which they are since you threw garbage away 

do ~ or ^

tells you to go back

when you merge
A
 /  \
B  C
 \  /
  D
  
  branch A
  branched off it
  did commit B on one branch and commit C on another
  merged them them back together to D
  
  using the tree
  A^0 = A
  A^1 = A^ = B
  A^2 = C
  & is for selecting which parent commit you  want 
  
  don't necessarily need to understand this to use git
  
  figure out design - sketching on paper! - what colours to use
