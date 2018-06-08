# Notes &c.

## Markdown Notes

- [Basic syntax](https://daringfireball.net/projects/markdown/syntax)

## Git

Basic Sequence:

1. Navigate to a Git project: `cd ~/Desktop/BeltonOscarJournal`
1. Be sure you have the latest stuff! `git pull`
1. Do some work, for example, editing `README.md`
1. After working… `git add README.md`
1. Commit that: `git commit -m "a message about what you did."`
1. Push: `git push`
1. Repeat

Useful stuff:

- Rename a file without confusing Git: `git mv OldName.md NewName.md`. Followed by `git add NewName.md`, then `git commit -m "renamed OldName.md to NewName.md"`, and `git push`.
- Remove a file from your computer and from Git: `git rm FileToDelete.md` (followed by `commit`, `push`).

We might want to talk about Branches…

## Validating CEX

Note:

Path to CEX directory: `/Users/briennadipietro/Documents/Belton\ Journal/BeltonOscarJourna/cex`