# The script that automatically updates KDE plugins and updates git

## Usage

```bash
git clone <repo> ~/.local/share/kwin
ln -s ~/.local/share/kwin ~/.local/bin/ # or whatewer bin directory you are using
kdeu
```

### Environment variable flags

- FORCE
You can use it to force push your changes in the repo, for example after you
installed some new plugin

## Description

The `kdeu` script is the main script. Under the hood it uses the `sera` binary
from [sera](https://gitlab.com/cscs/sera) repo.

## Making your own git repo

If you want to use my workflow:

- copy the `./sera` and `./kdeu` files to `~/.local/share/kwin`
- create a git repo there
- set remote

After it - use `kdeu` script for updates
