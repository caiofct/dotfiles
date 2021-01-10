# dotfiles

Dotfiles for my Macbook Pro 16,1 running macOS Big Sur 11.1.

Alacritty with zsh, tmux, starship prompt and colorls

![alacritty with zsh, tmux, starship prompt and colorls](https://raw.githubusercontent.com/caiofct/dotfiles/main/images/alacritty%2Btmux.png)

Neovim

![neovim](https://raw.githubusercontent.com/caiofct/dotfiles/main/images/vim.png)

-   Terminal: [Alacritty](https://github.com/jwilm/alacritty) using zsh w/ [starship prompt](https://starship.rs/) and [color-ls](https://github.com/athityakumar/colorls)
-   Vim: [neovim](https://neovim.io/) with [vim-plug](https://github.com/junegunn/vim-plug) to manage plugins
-   Tools: [tmux](https://github.com/tmux/tmux), [z](https://github.com/rupa/z), [fzf](https://github.com/junegunn/fzf)

## Installation

**Before you get started** make sure you give full disk access permission to your terminal (for writing macos defaults). `System Preferences -> Privacy -> Full Disk Access`.

To install:

`curl -L https://git.io/JLpgP | sh`

This expands to [run.sh](https://github.com/caiofct/dotfiles/blob/master/run.sh) which will fetch this repo and run the install script.

## File overview

-   Configs for the following tools:
    -   Alacritty
    -   fzf
    -   z
    -   git
    -   colorls
    -   starship
-   Shell environment configs:
    -   `.zshrc`
    -   `.zlogin.sh`
    -   `.zshenv.sh`
    -   [Antigen](https://github.com/zsh-users/antigen) for zsh plugin management
    -   `.aliases`
    -   `.exports`
-   `Brewfile` (contains all homebrew packages, casks, and mac appstore apps)

The install script will also setup a better Python environment with [pyenv](https://github.com/pyenv/pyenv) and set the global Python version to 3.8 instead of 2 (macOS default)

## Acknowledgements

-   [gretzky/dotfiles](https://github.com/gretzky/dotfiles)
