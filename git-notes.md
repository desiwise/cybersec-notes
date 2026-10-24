# GIT AND TERMINAL NOTES (Oct 24)

## Git workflow
git clone URL        -> download a repo to my machine
git status           -> shows what changed and if I'm ahead of GitHub
git add file         -> stage a file for the commit
git commit -m "msg"  -> save a snapshot with a message
git push             -> upload my commits to GitHub
"Everything up-to-date" -> GitHub already has all my commits

## Setup
git --version        -> checks Git is installed
git config --global user.name "Name"    -> sets my name for commits
git config --global user.email "email"  -> sets my email for commits
git config --list    -> shows saved settings

## Authentication
GitHub no longer accepts my account password for git push.
I use a personal access token instead (Settings > Developer settings).
The token is typed or pasted ONCE at the password prompt. Nothing shows on screen.
Never share a token. If it leaks, delete it and make a new one.

## Terminal tips
cat file             -> shows a file, no editing
nano file            -> opens a file for editing (Ctrl+O save, Ctrl+X exit)
cp file .            -> copies a file into the current folder
Ctrl+C               -> cancels the running command (shows ^C)
A ">" prompt         -> an unfinished command (usually a missing quote). Ctrl+C fixes it.
# in the terminal    -> starts a comment, ignored by the computer

## Markdown
# Heading, ## Heading, ### Heading  -> big to small headings (space after #)
1. 2. 3.            -> numbered list
- item               -> bullet
