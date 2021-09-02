<h1>&star;Branching and Merging in Git&star;</h1>

<li><code>git restore --staged filename.txt</code></li>
<p>When you modify some file and added to git repository you can remove at any time if you didn't made any commit on that file that is called staging. Once you commit that file you can stage that file.</p>

<li><code>rm -rf filename.txt</code></li>
<p>To delete file.</p>

<li><code>git reset <i>copy address</i></code></li>
<p>By default, git reset preserve the working directory. The commits are gone, but the contents are still on disk.</p>
<p><i><strong>How to remove the first commit in git?</strong><br>
  The first commit is what everything is built on. You could squash a few commits together, including the first commit, which becomes the new first commit, but what does it mean to even delete the first commit (or delete any but the last commit).</i></p>
