# .dotfiles
Personal dotfiles configuration.

## Move files
This repo is structured to support [Stow](https://www.gnu.org/software/stow/) for easier symlink creation

To start just install **Stow** using:
```
sudo apt update
sudo apt install stow
```

- In **home** directory make a new directory, let call it **.dotfiles** (can be any name you like)
- Clone this repo into that directory
- From **.dotfiles** direcotry execute the following command: `stow -D .`
- All done

All of the **.dotfiles** files should be symlinked correctly.

## Requirements

### Lazygit
To start using lazygit you first need to install it

Head to [Lazygit repo](https://github.com/jesseduffield/lazygit/releases) and grab the latest release

This repo uses [Delta](https://github.com/dandavison/delta) as a git pager for improved file changes highlighting, etc.

### Alacritty
To install allacrity head over to [Alacritty github](https://github.com/alacritty/alacritty) and use their instructions

### ZSH
It's BASH but much better.

To install head over to [ZSH github](https://github.com/ohmyzsh/ohmyzsh/wiki/Installing-ZSH)
Make it even better with [Oh My ZSH](https://ohmyz.sh/)

### Tmux
The one and only terminal multiplexer.

Install using [Tmux github](https://github.com/tmux/tmux/wiki)

### i3 WM
Install from [Homepage](https://i3wm.org/)

### NEOVIM
One and only text editor.

Install from [Neovim github](https://github.com/neovim/neovim/blob/master/INSTALL.md)

Open nvim and type `:checkhealth` and fix all issues seen there.
Not all warnings are required to be fixed

#### Clipboard
To use global clipboard in nvim install **xclip**.
To install execute:
```
sudo apt update
sudo apt install xclip
```

#### Blade support
To add blade support for laravel execute:  `:TSInstall blade`
