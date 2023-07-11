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