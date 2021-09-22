
<h1>&star;Basics of Git commands&star;</h1>

<li><code>git config --global user.name "user_name"</code></li>
<p>Set a name that is identifiable for credit when review version history.</p>

<li><code>git config --global user.email "valid email"</code></li>
<p>Set an email address that will be associated with each history marker.</p>

<li><code>git config --global color.ui auto</code></li>
<p>Set automatic command line colouring for git for easy reviewing.</p>

<li><code>mkdir folder name</code></li>
<p>mkdir means <b>"make directory".</b> the new directory is made below the current one.</p>

<li><code>cd foldername</code></li>
<p>also known as <b>chdir</b>(change directory),is a command - line shell command used to change the current working directory.</p>

<li><code>git init</code></li>
<p>Creates a new Git repository. We must maintain history of the project(delete, update, create etc) using git. This all history is stored in another folder that git provides us is known as git repository it named as .git .</p>

<li><code>ls</code></li>
<p>Lists the current directory contents and by default will not show hidden files.</p>

<li><code>git ls -a</code></li>
<p>To display hidden files.If any folder start with dot is hidden folder.</p>

<li><code>ls .git</code></li>
<p>List the content of .git folder. The .git folder contains all the information that is necessary for your project in version control and all the information about commit, remote repository address, etc. In general it tracks all the changes in our repository</p>

<li><code>touch filename.txt</code></li>
<p>Creates empty file.</p>

<li><code>git status</code></li>
<p>Display the state of the working directory and the staging area. It lets you see which changes have been staged, which haven't, and which files aren't being tracked by Git. Status output does not show you any information regarding the committed project history.</p>

<li><code>git add filename.txt</code></li>
<p>To add particular file to a staging area </p>

<li><code>git add .</code></li>
<p>To add all files to a staging area</p>

<li><code>git commit -m "Message"</code></li>
<p>Git commit messages are necessary to look back and see the changes made during a particular commit.Commits messages are the short description of the changes we make.</p>

<li><code>git log</code></li>
<p>The git log command display committed snapshots. It lets you list the project history, filter it, and search for specific changes. While 
  <br>
</p>

