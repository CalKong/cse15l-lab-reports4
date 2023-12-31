# Lab Report 4

## Log into ieng6

![Image](SSHLogin.png)

Keys pressed:
```
ssh<space>cs15lfa23jq@ieng6.ucsd.edu<enter>
```
Summary:
Remotely connected to ieng6 account

## Clone your fork of the repository from your Github account (using the SSH URL)

![Image](Clone.png)

Keys Pressed:
```
git<space>clone<space>git@github.com:CalKong/lab7.git<enter>
```
Summary:
Cloned the fork of my repository using SSH url

## Run the tests, demonstrating that they fail

![Image](TestsFail.png)

Keys Pressed:
```
cd<space>l<tab><enter>
bash<space>t<tab><enter>
```
Summary: Changed working directory to lab7 and used tab to autocomplete. Then ran the tests using the script test.sh and used autocomplete as well. 

## Edit the code file to fix the failing test

![Image](Vim.png)

Keys Pressed:
```
vim<space>L<tab>.<tab><enter>
:15llllllllllllllli<delete><delete><delete>
?index1<enter>lllllr2<esc>:wq<enter>
```
Summary: Opened ListExamples.java in vim mode using autocomplete. Went to line 15 and then deleted "0, " to fix the add method. The searched for "index1" stating from the bottom, moved cursor 5 steps right, and replaced the character the cursor was on with 2. Then entered normal mode and saved and quit vim mode. 

## Run the tests, demonstrating that they now succeed

![Image](TestsPass.png)

Keys Pressed:
```
bash<space>t<tab><enter>
```
Summary: Ran the tests using the script test.sh and used autocomplete as well. 

## Commit and push the resulting change to your Github account (you can pick any commit message!)

![Image](Git.png)

Keys Pressed:
```
git<space>add<space>L<tab><enter>
git<space>commit<space>-m<space>Fixed<enter>
git<space>push<enter>
```
Summary:
Added the edited file to prepare for commit and used autocomplete. Then committed the changes using the -m option to include the commit message as the next arguemnt, and then pushed the changes to github account. 
