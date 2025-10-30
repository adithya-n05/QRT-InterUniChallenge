# List all worktrees
git worktree list

# Remove a specific worktree
git worktree remove ../path-to-worktree

# Force remove (if there are uncommitted changes)
git worktree remove --force ../path-to-worktree


# After removing the worktree, the branch still exists, so you may want to delete it too:

bash
# Delete the branch
git branch -d branch-name

# Force delete (if not merged)
git branch -D branch-name