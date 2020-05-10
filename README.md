# nixi

Command-line tool to enter predefined nix-shell environments.

## Examples:
```
# enter the llvm development environment
nixi llvm

# enter the linux kernel
nixi linux-kernel
```

# How to install

```
git clone https://github.com/marler8997/nixi

# replace ~/bin/nixi with a directory in your path
ln -s $(realpath nixi/nixi) ~/bin/nixi
```
