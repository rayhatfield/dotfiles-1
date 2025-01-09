# dotfiles

my profile &amp; utility scripts

## Setup

```sh
git clone git@github.com:rayhatfield/dotfiles-1.git ~/.dotfiles
cd ~/.dotfiles
git submodule update --init --recursive
./install
```

I've also had to manually alias `~/.zshrc` to the one in the dotfiles dir. (I should sort this out to be automatic but haven't.)

```sh
ln -s ~/.dotfiles/zshrc .zshrc
```
