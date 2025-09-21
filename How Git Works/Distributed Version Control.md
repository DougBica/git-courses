git clone ->  copy main  branch .git to your pc

- Need a reference repository (on cloud)

**Local and Remote

- Git add feel lines in a clone, as information about remote "origin"
```
-  git branch --add
```
- Lista all branches even the remote branches, that list is storage in .git/refs/remotes
- To performance, git pack some branches info in a object called packed-refs

**Synchronizing 

- Git push, update de reference in remote to same refence commit as the local branch that changed some objects 
- When other local branch changes the main, our local branch needs to sync first or force a push (not recommended because you can lose commits)

Strategy to merge 
- Git fetch, update references with remote
- And then merge, creating a new commit 
- And then we can push to remote 
- A fetch + merge have is own command, that is called pull

And about rebase 
-  If  you rebase locally and try to push with conflict, and you use the pull strategy, you will end with you commits duplicated  
-  As a general rule: Never rebase shred commits.

