<h1>&star;Branching and Merging in Git&star;</h1>

<li><code>git restore --staged filename.txt</code></li>
<p>When you modify some file and added to git repository you can remove at any time if you didn't made any commit on that file that is called staging. Once you commit that file you can not stage that file.</p>

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
