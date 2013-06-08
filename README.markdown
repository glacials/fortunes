# Instructions

## Linux
1. `cd /usr/share`
2. `rm -r fortune`
3. `git clone git@github.com:skoh-fley/fortunes fortune`
4. `fortune/strfile`

## OS X (with a Homebrew-installed fortune)
1. `cd /usr/local/Cellar/fortune/<version>/share/games`
2. `rm -r fortunes`
3. `git clone git@github.com:skoh-fley/fortunes`
4. `fortunes/strfile`

# Adding entries

To add an entry just add it to the appropriately-titled file, then follow it
with a `%`. If you're making a new file, also add it to `strfile`.

In both cases, re-execute `strfile` to update the dat files so that your
changes will show up.
