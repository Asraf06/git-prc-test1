status for vs code:
U - Untracked
A  - Added or staged
C  - Commited or Changed
M - Modified

<h1>Commit</h1>
# commit status
<p><code>git status</code></p>
<p><code>git status -s</code></p>

#  check commit
<p><code>git log --oneline</code></p>

# remove last commit
<p><code>git reset --hard HEAD~1</code></p>

# see commit history
<p><code>git reflog</code></p>
<p><code>git log --oneline</code></p>

# All history
<p><code>git log</code></p>

# get back to lost commit by hash code
<p><code>git reset --hard e4f5g6h</code></p>

<h1>Branch</h1>

# create branch
<p><code>git branch name</code></p>

# show branch
<p><code>git branch</code></p>

# create new branch
<p><code>git branch -m new_branch</code></p>


#  add remote
<p><code>git remote add origin https://github.com/username/repo.git</code></p>

# change remote name
<p><code>git remote rename origi origin</code></p>


# check remote name
<p><code>git remote -v</code></p>

# remove remote
<p><code>git remote remove origin</code></p>

# change remote url
<p><code>git remote set-url origin https://github.com/username/repo.git</code></p>

