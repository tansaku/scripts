# scripts
useful scripts

## installation

clone the repository locally

```
$ git clone git@github.com:tansaku/scripts.git
```

add location to PATH in your `~/.zshrc` or similar

```
export PATH="$PATH:$HOME/Documents/Github/tansaku/scripts"
```

reload config

```
source ~/.zshrc
```

set permissions

```
chmod a+x tansaku/scripts/git-single
```

## usage

Assuming you have unstaged changes and no new files, you can now add, commit and push these to a branch using the following command:

```
$ git single branch-name-and-commit-message
```

For example `git single add-jest-cli` would create the branch name `add-jest-cli` and run the command `git commit -am "add jest cli"`


