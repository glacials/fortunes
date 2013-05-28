Instructions
============

Linux
-----

1. Remove any existing `/usr/share/fortune` folder.
2. `git clone` into `/usr/share` to end up with `/usr/share/fortune`
3. `/usr/share/fortune/strfile` to generate dat files

OS X (with a Homebrew-installed fortune)
----------------------------------------
1. `cd /usr/local/Cellar/fortune/<version>/share/games/`
2. `rm -r fortunes`
3. `git clone git@github.com:skoh-fley/fortune`
4. `mv fortune{,s}`
5. `./fortunes/strfile`
