# DOTFILES

> Bash first on Linux and Mac

`WARNING I'M DUMB WARNING`

> Tips: last edite `20220531152558`

```sh
rm ~/.bashrc
ln -sv $DOTFILES/.bashrc ~/.bashrc
ln -sv $DOTFILES/.inputrc ~/.inputrc
ln -sv $DOTFILES/.dircolors ~/.dircolors

rm ~/.profile
ln -sv $DOTFILES/.profile ~/.profile

ln -sv $DOTFILES/shared/tmux/.tmux.conf ~/.tmux.conf
```