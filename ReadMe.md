<h1> Bundle 1</h1>

PS C:\Users\user\gitsub> git init
Initialized empty Git repository in C:/Users/user/gitsub/.git/
PS C:\Users\user\gitsub> git branch -m master main
PS C:\Users\user\gitsub> git commit -m "Commit message"
[main (root-commit) 9f1fa1d] Commit message
 1 file changed, 1 insertion(+)
 create mode 100644 name.js
PS C:\Users\user\gitsub> git remote add origin https://github.com/Kevinemug/gitsub.git    
PS C:\Users\user\gitsub> git push -u origin main
Enumerating objects: 3, done.
To https://github.com/Kevinemug/gitsub.git
PS C:\Users\user\gitsub>
PS C:\Users\user\gitsub> git checkout dev
Switched to branch 'dev'
PS C:\Users\user\gitsub> git branch test
PS C:\Users\user\gitsub> git checkout dev
Already on 'dev'
PS C:\Users\user\gitsub> git branch -d test
Deleted branch test (was 9f1fa1d).
PS C:\Users\user\gitsub> 

<h1>bundle 2</h1>
 
 PS C:\Users\user\gitsub> git add . ut -b ft/bundle-2 
PS C:\Users\user\gitsub> git commit -m"new changes"
[ft/bundle-2 7dabc78] new changes
 1 file changed, 11 insertions(+)
 create mode 100644 services.html
fatal: a branch named 'main' already exists
PS C:\Users\user\gitsub> git checkout master
error: pathspec 'master' did not match any file(s) known to git
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
git: 'cheout' is not a git command. See 'git --help'.

        checkout
PS C:\Users\user\gitsub> git cheout ft/bundle-2
git: 'cheout' is not a git command. See 'git --help'.

The most similar command is
        checkout
PS C:\Users\user\gitsub> git checkout ft/bundle-2
Switched to branch 'ft/bundle-2'
PS C:\Users\user\gitsub> git commit -m "Add/modify files in the project"
On branch ft/bundle-2
nothing to commit, working tree clean
PS C:\Users\user\gitsub> git push origin ft/bundle-2
Enumerating objects: 4, done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 484 bytes | 484.00 KiB/s, done.                                                        e.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0      
remote:
remote: Create a pull request for 'ft/bundle-2' on GitHub by visiting:
by visiting:                                              ft/bundle-2
remote:      https://github.com/Kevinemug/gitsub/pull/new/ft/bundle-2
remote:
To https://github.com/Kevinemug/gitsub.git
 * [new branch]      ft/bundle-2 -> ft/bundle-2
PS C:\Users\user\gitsub>