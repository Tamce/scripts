# setup steps

## install oh-my-zsh
* ohmyz.sh
```
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

## chsh
```
sudo chsh -s /bin/zsh {user}
```

## custom theme and set env
1. install custom theme into .oh-my-zsh/theme
2. add some important options
3. check `.bashrc` and see if needs to add `source ~/.bashrc`

```
unsetopt autopushd
ZSH_THEME="tamce"
TMC_ENV="hint"
```

## upgrade vim to 8.0+!!!
## install nvm for latest node!!!
## install vim-plug
## install plugins
## replace .vimrc
## install coc and related language server

