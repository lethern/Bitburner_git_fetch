## Bitburner_git_fetch
Used to fetch scripts from git to game<br />
No passwords or anything required - which means works only with public github repositories (for now)

## Usage
Download both files

Edit `git_fetch.txt`<br />
Remove the example and put the list of files you would want to be fetched from your git directory<br />
Make sure to keep that file a valid JSON (no stray commas etc.), don't use leading slashes

Edit `git_fetch.js`<br />
Change a few of first lines, according to comments

## Notes
Git can delay updating changes to files up to 5 minutes. The limitation of raw.githubusercontent.com

## Working with private repo?
Not supplied here, check https://github.com/cscheid/bitburner-lib/blob/main/install.js