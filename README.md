# GIT_WORKFLOW
Q1 How git workflow works?
Q2 What are the different stages of a git 
project as commit,add?
Ans.
1. Working directory - Workspace.
2. Index ie stage
3. Local Repository ie Head
4. Remote Repository
----------------------------------
There is one central repository. 
Each developer clones the repo,
works locally on the code,
Modifies and makes the changes as required
Commit the changes using command commit -a with changes
and push it to the central repository 
for other developers to pull and use in their work.


Q3 Is it possible to do a git commit before git add .
If you have made any changes? Explain why?
Ans. No because according to the process
first we have to add the file and then commit changes to it
After making the changes we will add them using "git add ."
and then we can commt it using (commit -a).

Q4 Why is git diff used?
Ans. git diff is used to track the difference between 
the changes made on a file.This commands shows all the
changes which are done. Diff command takes two inputs and 
reflects the differences between them. It is not necessary
that these inputs are files only. 
It can be branches, working trees, commits and more. 

Q5 Can we leave the commit message as blank?
Ans. git commit -a --allow-empty-message -m ""
It is a valid request,commit can have no message at all.
 
Github repository link
https://github.com/priya8936/java-JFrames-Listeners

Regards
Priya Aggarwal
