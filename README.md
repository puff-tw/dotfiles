# dotfiles
my custom dotfiles

Useage : 

# go to your home dir
cd ~ 

# clone this repo
git clone git@github.com:puff-tw/dotfiles.git

# custom

vim ~/.bashrc

```
if [ -f ~/dotfiles/.bash_aliases ]; then
    . ~/dotfiles/.bash_aliases
fi
```

vim ~/.profile

```
if [ -f ~/dotfiles/.profile ]; then
    . ~/dotfiles/.profile
fi
```

