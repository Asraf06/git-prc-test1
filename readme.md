status for vs code:
U - Untracked
A  - Added or staged
C  - Commited or Changed
M - Modified

<h1>Commit</h1>
<h3>commit status</h3>
<p><code>git status</code></p>
<p><code>git status -s</code></p>

<h3> check commit</h3>
<p><code>git log --oneline</code></p>

<h3>remove last commit</h3>
<p><code>git reset --hard HEAD~1</code></p>

<h3>see commit history</h3>
<p><code>git reflog</code></p>
<p><code>git log --oneline</code></p>

<h3>All history</h3>
<p><code>git log</code></p>

<h3>get back to lost commit by hash code</h3>
<p><code>git reset --hard e4f5g6h</code></p>

<h1>Branch</h1>

<h3>create branch</h3>
<p><code>git branch name</code></p>

<h3>show branch</h3>
<p><code>git branch</code></p>

<h3>create new branch</h3>
<p><code>git branch -m new_branch</code></p>

<h3>switch branch</h3>
<p><code>git checkout name</code></p>

<h3>switch branch with files in local computer</h3>
<p><code>git switch new_branch</code></p>

<h3> add remote</h3>
<p><code>git remote add origin https://github.com/username/repo.git</code></p>

<h3>change remote name</h3>
<p><code>git remote rename origi origin</code></p>


<h3>check remote name</h3>
<p><code>git remote -v</code></p>

<h3>remove remote</h3>
<pre><code id="cmd">git remote remove origin</code></pre>
<button onclick="navigator.clipboard.writeText(document.getElementById('cmd').innerText)">Copy</button>


<h3>change remote url</h3>
<p><code>git remote set-url origin https://github.com/username/repo.git</code></p>



