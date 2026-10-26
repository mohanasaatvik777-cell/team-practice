   # Team Practice - A and B

   ## Git notes

   ### Why git reset is dangerous on shared branches
   Reset rewrites history. Teammates' copies no longer match the branch, and fixing it needs a force push that can erase their work. Use revert on shared branches.

   ### Merge vs rebase
   - Merge joins two branches with a merge commit and keeps the real history.
   - Rebase replays your commits on top of another branch for a straight line.
   - Rebase rewrites history, so avoid it on shared branches.