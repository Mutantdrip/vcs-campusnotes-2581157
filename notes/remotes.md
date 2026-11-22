# Remote repositories

- `git remote add origin <url>` links a local repo to GitHub.
- `git push -u origin main` pushes and sets upstream tracking.
- `git remote -v` lists fetch and push URLs.
- `git pull` fetches upstream changes and integrates them into your current branch. Use `git pull --ff-only` to update only when Git can fast-forward, or `git pull --rebase` to replay local commits on top of the fetched branch.
