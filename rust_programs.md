# Rust programs

Inspired by [this article](https://zaiste.net/posts/shell-commands-rust)

- [exa](#exa)
- [tealdeer](#tealdeer)
- [bat](#bat)
- [ripgrep](#ripgrep)
- [fd](#fd)
- [procs](#procs)
- [sd](#sd)
- [zoxide](#zoxide)
- [starship](#starship)
- [alacritty](#alacritty)
- [amp](#amp)

## `bat`

`sudo zypper install bat`

## `exa`

`sudo zypper install exa`

## `fd`

`sudo zypper install fd`

`sudo apt install fd-find && sudo ln -s $(which fdfind) /usr/local/bin/fd`

`cargo install fd-find`

## `ripgrep`

`sudo zypper install ripgrep`

## `tealdeer`

`sudo zypper install tealdeer && tldr --update`

On Ubuntu

`sudo apt install pkg-config libssl-dev`

## `procs`

`cargo install procs`

## `sd`

`cargo install sd`

## `zoxide`

`cargo install zoxide`

Add `eval "$(zoxide init zsh)"` to `~/.profile`

## `starship`

Requires a (nerd font](https://www.nerdfonts.com/)

- Unzip fonts
- Move fonts to `/usr/local/share/fonts`
- Update font cache with `fc-cache -fv`

Requires openssl development packages

`sudo zypper install libopenssl-devel`

`sudo apt install pkg-config libssl-dev`

Install with cargo

`cargo install starship`

Add line to `.profile`

`eval "$(starship init zsh)"`

For WSL, you must install the font in Windows and then add the line `"fontFace": "FiraCode Nerd Font"` to `settings.json` of windows terminal

### pi4

`sudo apt install build-essential libssl-dev pkg-config`

config file: `~/.config/starship.toml`

## `alacritty`

`sudo apt install cmake libfontconfig1-dev libxcb-shape0-dev libxcb-xfixes0-dev`

`cargo install alacritty`

`sudo zypper install alacritty`

config file: `~/.config/alacritty/alacritty.yml`

## `amp`

`sudo zypper install libxcb-devel`

`sudo apt install libxcb-shape0-dev libxcb-xfixes0-dev`

`cargo install amp`

config file: `~/.config/amp/config.yml`

