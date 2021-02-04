# dotfiles

Based on @Emocat's private terminal settings.

I found it particularly useful and efficient for configuring new machines, therefore I forked it and changed some settings to match my personal preferences.

## Install

```bash
git clone https://github.com/arcpen/dotfiles ~/.dotfiles
cd ~/.dotfiles && ./install.sh
```

## Vim

```bash
curl -fLo ~/.vim/autoload/plug.vim --create-dirs https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
cp $HOME/.dotfiles/vimrc ~/.vimrc
vim -c "PlugInstall"
```

You may need to use **network scientificalliy** to download some plugins.
