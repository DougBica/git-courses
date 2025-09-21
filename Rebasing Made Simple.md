
Git makes copies of the commits and put them in order, point to the parent as the last commit of the other branch and move the HEAD of the branch to point to the last copied commit.


It working different then merge, because merge create a new commit which sync both branches. 


Trade-off of Merge
- It preserve history 
- Merges never lie 

Trade-off of Rebase
- Refactor history
- More neat history
- Commits parallel looks in line 

When in doubt, just merge.

## Tag

```
git tag tagName  -a -m "message"
```

Stay in folder .git/refs/tags

Annotated Tags 
- A reference to a object called tag
- Then that object points to a commit
Tags
- Just points to a commit
- Without metadata

Tags doesn't move like branch

