# The script that automatically updates KDE plugins and updates git

## Usage

```bash
git clone <repo> ~/.local/share/kwin
ln -s ~/.local/share/kwin ~/.local/bin/ # or whatewer bin directory you are using
kdeu
```

## Description

The `kdeu` script is the main script. Under the hood it uses the `sera` binary
from [sera](https://gitlab.com/cscs/sera) repo.

## Making your own git repo

If you want to use my workflow:

- copy the `./sera` and `./kdeu` files to `~/.local/share/kwin` and enjoy
- create a git repo there
- set remote

After it - use `kdeu` scrit for updates
