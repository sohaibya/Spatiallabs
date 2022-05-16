We can work in separate branches and once our code is finalized we can merge it into main.
Squash commits before merging (for more commits in the feature branch).
git rebase -I HEAD~40  # look at up to 40 commits to consider squashing. 
Merge all 40 commit messages(this step is done if we have many commit messages and to avoid lot of commits messages in master we can just add it at one place..

Also i will use better tags for adding details.
