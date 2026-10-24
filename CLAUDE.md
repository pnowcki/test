# Instructions for Claude

## Save work to GitHub

The cloud container is deleted after the session goes idle. Files that are not pushed are lost, and no one is warned.

- After every file change, commit it and push it to the session branch.
- Before ending a turn, check that nothing is uncommitted or unpushed (`git status`, `git log origin/<branch>..HEAD`). If anything is, commit and push it.
- Sessions often run without the user watching, so do this without being asked.
