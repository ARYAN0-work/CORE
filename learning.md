🧱 PHASE 0 → CHECKPOINT 1 — SUMMARY
What you did (step-wise)

Created a project folder → container for your code

Initialized git → started version tracking

Added JS files → gave git something to track

Checked status → saw what git is aware of

Added files to staging → marked changes for commit

Committed changes → created a saved checkpoint

Created GitHub repo → remote storage

Connected local to remote → linked your machine to GitHub

Pushed commits → uploaded history to GitHub

Made more commits → practiced repeatability

Outcome: Git is now mechanical, not scary.

🔹 GIT COMMANDS — ONE-LINE MEANING EACH

git init → start git tracking in this folder

git status → show current state of files

git add . → stage all changes for commit

git commit -m "msg" → save a snapshot with a message

git branch → list branches

git branch -M main → rename current branch to main

git remote add origin URL → connect local repo to GitHub

git push → send commits to remote repo

git push -u origin main → push and set default upstream

git clone URL → copy a repo from GitHub to local

git checkout -b name → create + switch to new branch

🧠 What this checkpoint really means

Git commands = muscle memory

Commits = save points

GitHub = public proof

What U and A mean in git status
🟥 U → Untracked

File exists but git is NOT tracking it

Happens when you:

create a new file

copy a file into the repo

➡️ Fix:

git add filename

🟩 A → Added (staged)

File is marked to be included in next commit

Git is now tracking it

➡️ Happens after:

git add .

One-line mental model

U = “git doesn’t know this file yet”

A = “git will save this file in the next snapshot”

Flow in one line
New file → U → git add → A → git commit → saved forever


That’s it.