# Git Basics

- `git init`: initialize repo
- `git clone <url>`: clone remote
- `git add .`: stage all
- `git commit -m "msg"`: commit
- `git checkout -b test-branch`: create and go to new branch

✅ Git & GitHub--Summary
- Git is a distributed version control system. It tracks changes in code via commits, which are snapshots of the code at a certain time.

- The latest commit is pointed to by HEAD. A branch (e.g., main, feature-x) is like a separate timeline of changes; useful to avoid polluting the main code with experimental work.

- Commits are local by default. You use git push to upload them to a remote repository (like GitHub), and git pull to bring in changes from that remote.

- Pull requests (PRs) are created on GitHub, not in Git. They propose changes from one branch (usually in your fork or repo) into another branch (often the main branch of the original repo).

- If you don’t have push access to a repo, you fork it (your own copy on GitHub), clone it locally, push changes to your fork, and then create a PR to the original repo.

- Git is essential in DevOps and collaborative development because it keeps a clean history, allows parallel feature work, and ensures reproducibility.