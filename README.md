# nx

Command-line tool to enter predefined nix-shell environments.

## Examples:
```
# enter the llvm development environment
nx llvm

# enter the linux kernel
nx linux-kernel
```

# How to install

```
git clone https://github.com/marler8997/nx

# replace ~/bin/nx with a directory in your path
ln -s $(realpath nx/nx) ~/bin/nx
```

# TODO:

* add auto-complete
* maybe have multiple search paths for environments?  This repo?  $HOME/nx?  The user's home directory would take precedence of course.
