# Git and GitHub - Lesson 1
<hr/>
##### Commits
- fix off-by-one bug
- add new feature
- improve user docs

##### keep track of changes
<code> $ git log </code>

##### check changes
<code> $ git diff <em>commit id1 commit id2</em> </code>

##### show statistics about which files has changed
<code> $ git log ---stat </code>

##### Cloning a Repository
clone the entire repository from one computer to another.<br>
<code> $ git clone <em>url to other repository</em></code>

<b>Example</b><br>
<code> $ git clone https://github.com/udacity/asteroids.git<br>
Cloning into 'asteroids'...<br>
remote: Counting objects: 209, done.<br>
remote: Total 209 (delta 0), reused 0 (delta 0), pack-reused 209<br>
Receiving objects: 100% (209/209), 184.58 KiB | 294.00 KiB/s, done.<br>
Resolving deltas: 100% (127/127), done.<br>
Checking connectivity... done.<br>
