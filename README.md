# My personal dotfiles on ubuntu or fedora

This is an initial system configuration file without sensitive information (such as account passwords, etc.), which is used to quickly build the environment.

If you want to use my dotfiles to experience my environment, please write an additional `init.sh` to reference my dotfiles, for example, in the `init.sh`, you can move the `dotfiles/nvim` to `~/.config/nvim`.
just like this

```bash
#!/bin/bash
git clone https://github.com/Archer-Shan/dotfiles.git
cp ./dotfiles/*vimconfig/nvim ~/.config/nvim -r
```

