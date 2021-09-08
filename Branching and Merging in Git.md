
<h1>&star;Branching and Merging in Git&star;</h1>
<li><code>vi filename.txt</code></li>
<p>Command used to write content in file.
  <br>
  <b>How do you use vi in text editor.</b>
 <ol>
  <li>To enter vi, type vi filename.txt</li>
  <li>To enter insert mode, type i</li>
  <li>Type in the text:------</li>
  <li>To leave insert mode and return to command mode, press: &ltEsc&gt</li>
  <li>To exit vi by typing :x You are back at the git bash.</li>
</ol> 
<em><b>Note: vi(Visual Instrument)</b> is the default editor. Using this we can edit an existing file.</em></p>

<li><code>cat filename.txt</code></li>
<p>To see the content of file.</p>

<li><code>git remote add origin <i>_repository url_</i></code></li>
 <p>This is command that says "push the commits in the local branch named master to the remote named origin". Once this is executed, all the stuff that you last synchronised with origin will be sent to the remote repository and other people will be able to see them there. </p>

<li><code>git remote -v</code></li>
<p>Shows URLs of remote repositories when listing your current remote connections.</p>

<li><code>git remote rm origin</code></li>
<p>All it means that your local copy of a repository is no longer associated with a particular remote. Alternatively, you can use the git remote rm command. git remote rm is simply a shorter version of the fit remote remove command. We can see our "origin" remote has been successfully removed.</p>

<li><code>git push origin master</code></li>
<p>In simple words git push command updates the remote repository with local commits. The origin represent a remote name where the user wants to push the changes. git push command push commits made on a local branch to a remote repository.</p>

<li><code>git restore --staged filename.txt</code></li>
<p>When you modify some file and added to git repository you can remove at any time if you didn't made any commit on that file that is called staging. Once you commit that file you can not unstage that file.</p>

<li><code>rm -rf filename.txt</code></li>
<p>To delete file.</p>

<li><code>git reset <i>copy address</i></code></li>
<p>By default, git reset preserve the working directory. The commits are gone, but the contents are still on disk.</p>
<p><i><strong>How to remove the first commit in git?</strong><br>
  The first commit is what everything is built on. You could squash a few commits together, including the first commit, which becomes the new first commit, but what does it mean to even delete the first commit (or delete any but the last commit).</i></p>

<li><code>git stash</code></li>
<p>The git stash command takes your uncommitted changes (bth staged and unstaged), saves them away for later uses, and then reverts them from your working copy.</p>

<li><code>git stash pop</code></li>
<p>Git allows the user to re-apply the previous commits by using git stash pop command. The popping option removes the changes from stash and appies them to your working file.</p>

<li><code>git stash clear</code></li>
<p>Clear the stash area.</p>

<li><code>git clone  <i>__URL of forked repo in your repo__</i></code></li>
<p>It is primarily used to point to an existing repo and make a clone or copy of that repo at in new directory, at another location. The original repository can be loacted on the local file system or on remote machine accessible supported protocols. The git clone command copies an existing Git repository.</p>

<li><code>git remote add upstream <i>__URL from where you have forked this repo__</i></code></li>
<p>You must configure a remote that points to the upstream repository in Git to sync changes made in the original repository with the fork.</p>

<li><code>git branch <i>branch name</i></code></li>
<p>A branch represents an independent line of development. The git branch command lets you create, list, rename, and delete branches. It doesn't let you switch between branches or put a forked history back together again. For this reason, git branch is tightly integrated with the git checkout and git merge commands.</p>

<li><code>git checkout <i>branch name</i></code></li>
<p>The git checkout command lets you navigate between the branches created by git branch . Checking out a branch updates the files in the working directory to match the version stored in that branch, and it tells Git to record all new commits on that branch.</p>

<li><code>git push origin <i>branch name</i></code></li>
<p>Pushing changes to the remote makes your commits accessible to others who you may be collaborating with. This will also update any open pull requests with the branch that you're working on. </p>

<li><code>git push origin <i>branch name</i> -f</code></li>
<p>Origin stands for <b>your remote repository. </b>So when you use <code>git push origin <i>branch name</i> </code>, you are saying push my code to a branch called [branch name] in this specific remote repository called "origin".</p>

<li><code>git fetch --all --prune</code></li>
<p>git fetch --prune is the best utility for cleaning outdated branches. It will connect to a shared remote repository remote and fetch all remote branch refs. It will then delete remote refs that are no longer in use on the remote repository</p>

<li><code>git reset --hard upstream/main</code></li>
<p></p>

<li><code>git pull upstream main</code></li>
<p>The git pull command is used to fetch and download content from a remote repository and immediately update the local repository to match that content. Merging remote upstream changes into your local repository is a common task in Git-based collaboration work flows.</p>
