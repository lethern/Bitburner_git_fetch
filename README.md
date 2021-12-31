## Bitburner_git_fetch
Use to fetch scripts from git into the game<br />
No passwords or anything required - which means it works only with public github repositories (for now)

## Usage
Download the .txt and js files

Edit `git_fetch.txt`<br />
Remove the example and put the list of files you would want to be fetched from your git directory<br />
Make sure to keep that file a valid JSON (no stray commas etc.), don't use leading slashes

Edit `git_fetch.js`<br />
Change a few of first lines, according to comments

## Notes - limitation
Git may delay changes to files, from 0 up to 5 minutes. If your install doesn't fetch new commited files, wait a bit. There is probaly a work-around, but it didn't make it to this repo

## Working with private repo?
Not supplied, consider: <br />
https://github.com/cscheid/bitburner-lib/blob/main/install.js <br />
https://github.com/SlyCedix/bitburner-scripts/blob/752bdb2350ad549740e7deeede0d63a022c6705b/scripts/fetcher.js <br />
https://github.com/hexnaught/vscode-bitburner-connector/blob/master/src/extension.js
