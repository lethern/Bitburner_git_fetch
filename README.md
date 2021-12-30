# Bitburner_git_fetch
Used to fetch scripts from git to game
No passwords or anything required - which means works only with public github repositories (for now)

# Usage
Download both files

Config: edit the `.txt` file
Remove the example and list files you would want to be fetched from your git directory
Make sure to keep that file a valid JSON (no stray commas etc.), don't use leading slashes

Script: edit the `.js` file, change the first 

# Notes
Git can delay updating changes to files up to 5 minutes. The limitation of raw.githubusercontent.com

# Working with private repo?
check [https://github.com/cscheid/bitburner-lib/blob/main/install.js]