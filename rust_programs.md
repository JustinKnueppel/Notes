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

Requires openssl development packages

`sudo zypper install libopenssl-devel`

Install with cargo

`cargo install starship`

Add line to `.profile`

`eval "$(starship init zsh)"

