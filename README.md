# dotfiles

Dotfiles for my Macbook Pro 16,1 running macOS Big Sur 11.1.

![zsh with starship prompt and colorls](https://user-images.githubusercontent.com/15176096/71632895-ff0d0980-2bde-11ea-966f-65e5d564361f.png)
![vim and tmux](https://user-images.githubusercontent.com/15176096/71633424-2f09dc00-2be2-11ea-9c15-a4f492b7ea68.png)

-   Terminal: [Alacritty](https://github.com/jwilm/alacritty) using zsh w/ [starship prompt](https://starship.rs/) and [color-ls](https://github.com/athityakumar/colorls)
-   Vim: [neovim](https://neovim.io/) with [Vundle](https://github.com/VundleVim/Vundle.vim) to manage plugins
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
