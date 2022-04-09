# commitlinter

An imperfect bash git hook linter for commit messages, ensuring compliance with conventional commits guidelines ala [conventional commits](https://www.conventionalcommits.org/en/v1.0.0/)

See the spec [here](https://github.com/conventional-commits/conventionalcommits.org/blob/master/content/v1.0.0/index.md).

To enable, copy `commit-msg` to `.git/hooks/` under your favorite git repo -- or if you're brave and want to use this globally, copy the script to your system git templates directory and future inits/clones will ensure it's present.

sudo sh -c 'cp commit-msg /usr/share/git-core/templates/hooks/ && chmod 0755 /usr/share/git-core/templates/hooks/commit-msg'

