status for vs code:
U - Untracked
A  - Added or staged
C  - Commited or Changed
M - Modified

<h1>Commit</h1>
<h3>commit status</h3>
<pre><code>git status</code></pre>
<button onclick="navigator.clipboard.writeText(document.getElementById('cmd').innerText)"></button>
<pre><code>git status -s</code></pre>
<button onclick="navigator.clipboard.writeText(document.getElementById('cmd').innerText)"></button>

<h3> check commit</h3>
<pre><code>git log --oneline</code></pre>
<button onclick="navigator.clipboard.writeText(document.getElementById('cmd').innerText)"></button>

<h3>remove last commit</h3>
<pre><code>git reset --hard HEAD~1</code></pre>
<button onclick="navigator.clipboard.writeText(document.getElementById('cmd').innerText)"></button>

<h3>see commit history</h3>
<pre><code>git reflog</code></pre>
<button onclick="navigator.clipboard.writeText(document.getElementById('cmd').innerText)"></button>
<pre><code>git log --oneline</code></pre>
<button onclick="navigator.clipboard.writeText(document.getElementById('cmd').innerText)"></button>

<h3>All history</h3>
<pre><code>git log</code></pre>
<button onclick="navigator.clipboard.writeText(document.getElementById('cmd').innerText)"></button>

<h3>get back to lost commit by hash code</h3>
<pre><code>git reset --hard e4f5g6h</code></pre>
<button onclick="navigator.clipboard.writeText(document.getElementById('cmd').innerText)"></button>

<h1>Branch</h1>

<h3>create branch</h3>
<pre><code>git branch name</code></pre>
<button onclick="navigator.clipboard.writeText(document.getElementById('cmd').innerText)"></button>

<h3>show branch</h3>
<pre><code>git branch</code></pre>
<button onclick="navigator.clipboard.writeText(document.getElementById('cmd').innerText)"></button>

<h3>create new branch</h3>
<pre><code>git branch -m new_branch</code></pre>
<button onclick="navigator.clipboard.writeText(document.getElementById('cmd').innerText)"></button>

<h3>switch branch</h3>
<pre><code>git checkout name</code></pre>
<button onclick="navigator.clipboard.writeText(document.getElementById('cmd').innerText)"></button>

<h3>switch branch with files in local computer</h3>
<pre><code>git switch new_branch</code></pre>
<button onclick="navigator.clipboard.writeText(document.getElementById('cmd').innerText)"></button>

<h3>Create branch with switch branch</h3>
<pre><code>git switch -C new_branch</code></pre>
<button onclick="navigator.clipboard.writeText(document.getElementById('cmd').innerText)"></button>

<h3>Merge branch</h3>
<p>Make sure you switch to main branch first.</p>
<pre><code>git merge new_branch</code></pre>
<p>After merge push the code to github.</p>
<button onclick="navigator.clipboard.writeText(document.getElementById('cmd').innerText)"></button>

<h3>Delete branch</h3>
<p>Get the latest changes from the remote repository and immediately merge them into my current branch.</p>
<pre><code>git pull</code></pre>
or use
<pre><code>git pull origin main</code></pre>
<button onclick="navigator.clipboard.writeText(document.getElementById('cmd').innerText)"></button>

<h3>Delete branch</h3>
<pre><code>git branch -d branch_name</code></pre>
<button onclick="navigator.clipboard.writeText(document.getElementById('cmd').innerText)"></button>

<h3>Switch branch without commit</h3>
<p>Git will not give you permision to change branch without commit new line. So first you need to hide new line code.</p>
<pre><code>git stash</code></pre>
<p>Now you can switch branch. And see your code. Now to get back your main branch. And run this command to get back the hidden line.</p>
<pre><code>git stash apply</code></pre>
<button onclick="navigator.clipboard.writeText(document.getElementById('cmd').innerText)"></button>
<p>To delete saved line use this code.</p>
<pre><code>git stash clear</code></pre>
<button onclick="navigator.clipboard.writeText(document.getElementById('cmd').innerText)"></button>

<h3>Fetch branch</h3>
<p>git fetch is a safe command that downloads new data (commits, branches, tags) from a remote repository — without changing your local code.</p>
<pre><code>git fetch</code></pre>
<button onclick="navigator.clipboard.writeText(document.getElementById('cmd').innerText)"></button>

<h1>Remote</h1>
<h3> add remote</h3>
<pre><code>git remote add origin https://github.com/username/repo.git</code></pre>
<button onclick="navigator.clipboard.writeText(document.getElementById('cmd').innerText)"></button>

<h3>change remote name</h3>
<pre><code>git remote rename origi origin</code></pre>
<button onclick="navigator.clipboard.writeText(document.getElementById('cmd').innerText)"></button>

<h3>check remote name</h3>
<pre><code id="cmd">git remote -v</code></pre>
<button onclick="navigator.clipboard.writeText(document.getElementById('cmd').innerText)"></button>

<h3>remove remote</h3>
<pre><code id="cmd">git remote remove origin</code></pre>
<button onclick="navigator.clipboard.writeText(document.getElementById('cmd').innerText)"></button>

<h3>change remote url</h3>
<pre><code>git remote set-url origin https://github.com/username/repo.git</code></pre>
<button onclick="navigator.clipboard.writeText(document.getElementById('cmd').innerText)"></button>



