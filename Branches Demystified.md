Branch is just a reference to a commit

.git -> refs -> heads 

What is HEAD ? 
- Its just a reference to a branch, the file path to the branch 

When we move between branches, with `git branch branchname` for example, the file HEAD is updated with the file path to that branch and the working area.

Git always focus in your database state of a commit, not the working area, which is transient. 


**Fast-forward merge
- That means that git move the reference of a branch to the last commit of the another.

**Checkout a commit
- Point directly to a commit hash
- Called detached head
- And the commits without use (unreachable) will be deleted to not consume resources by garbage collector. 