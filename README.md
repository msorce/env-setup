# 💊💻 env-setup
## Terminal Emulator

I really wanted to be able to use the default terminal.app, however, it does not support true colors, and it had some mouse issues with neovim

### Installation
```brew install --cask alacritty```

TODO: configure with YAML file, check github repo

check installed fonts
```fc-list```
Or if you want to check for one font in particular you can use:

```fc-match NameOfFont -s```
Where ‘NameOfFont’ is the font you’re checking for.
---
## Neovim

### Installation
`brew install neovim`

TODO: https://www.twitch.tv/teej_dv told me to use this for LSP setup https://github.com/nvim-lua/kickstart.nvim


if you need to erase nvim settings and start from scratch, rm ~/.config/nvim && rm ~/.local/share/nvim
### Options 
1. create init.lua in ~/.config/nvim

### Plugins
https://github.com/wbthomason/packer.nvim

installing for unix/linux
```
git clone --depth 1 https://github.com/wbthomason/packer.nvim\
 ~/.local/share/nvim/site/pack/packer/start/packer.nvim
```
### Keymaps

### Colorschemes

### Completion

### Fonts

### LSP 

### Telescope (fizzy finder)

### Treesitter (syntax highlighting)

### Autopairs

### Comments

### Git Signs

### Nvim Tree (explorer)

### Bufferline

### Formatting, Linting

### Toggle Term
