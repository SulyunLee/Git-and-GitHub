# Git and GitHub - Lesson 2
<hr/>
##### Repositories
- git repositores store bunch of metadata about the history of the repository since it was created.
- start with <code>.git</code>

##### initialize and create a git repository
<code> $ git init </code>
- The new repository contains no Commits. <br>

<b> Example </b><br>
<code> $ git init<br>
Initialized empty Git repository in C:/Users/Hankyu/Desktop/Git and GitHub/version-control/reflections/.git/<br>
$ git status<br>
On branch master<br>
Initial commit<br>
<br>
Untracked files:
  (use "git add <file>..." to include in what will be committed)<br>
  lesson_1_reflections.txt<br>
<br>
nothing added to commit but untracked files present (use "git add" to track)</code>

##### show which file has changed since the last commit
<code> $ git status </code>

##### add changes to repository
- when you add commit to your repository, use intermediate area called 'staging area'.
- add files one at a time at the staging area.<br>

<code> $ git add  <em>filename</em></code><br>
<b>Example</b><br>
<code> $ git add lesson_1_reflections.txt<br>

##### git diff Revisited Solution
1. <code> git diff</code> : comparing working directory and staging area.
2. <code> git diff --staged</code> : comparing staging area and commit 1.
3. <code> git diff commit1 commit2</code> : comparing commit1(most recent commit) and commit2.

##### Branches
- <b>master</b> : name given to the main branch. Every time you create a new repository, master branch is created automatically.<br>
- When you want to change file in the master branch(not a official update), you can change the branch.
- branch helps you when you keep your project organized particularly when you share publicly.

##### show the current branch
<code> $ git branch<br>* master<code>

##### run branch easy-mode
<code>$ git branch easy-mode  # create a new branch with this name<br/>
$ git branch<br/>
easy-mode<br/>* master<br/>
$ git checkout easy-mode<br/>
Switched to branch 'easy-mode'<br/>
$ git branch<br/>* easy-mode
master<br/>## easy-mode is checked out!</code>

##### Merging files
<b>Example: merging coin branch and master branch</b></br>
<code>$ git merge master coins

##### Deleting branch
<code>$ git branch -d coins<br>
Deleted branch coins (was 354dfdd).</code>
