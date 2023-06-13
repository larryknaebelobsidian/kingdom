# Obsidian Repository of notes on
# The Theocratic Kingdom
## by George N. H. Peters

Using Obsidian Git plugin for auto backups and commits to github.

Modified ***.git/config*** with 2 lines noted below:
This allowed for long file names and to leave the crlf warnings alone so commits would work.

```
[core]
	repositoryformatversion = 0
	filemode = false
	bare = false
	logallrefupdates = true
	symlinks = false
	ignorecase = true
	longpaths = true #addedthisline
	safecrlf = false #addedthisline
[remote "origin"]
	url = git@github.com:larryknaebelobsidian/kingdom.git
	fetch = +refs/heads/*:refs/remotes/origin/*
[branch "main"]
	remote = origin
	merge = refs/heads/main
```