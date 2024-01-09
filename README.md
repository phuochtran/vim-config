# vim-config

* Create folder `.vim` in your home directory
```text
mkdir -p ~/.vim ~/.vim/autoload ~/.vim/backup ~/.vim/colors ~/.vim/plugged
```
* Copy `.vimrc` from repository into your home directory
* Install `vim-plug`
```bash
curl -fLo ~/.vim/autoload/plug.vim --create-dirs https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```
* Install theme `molokai`
```bash
curl -o ~/.vim/colors/molokai.vim https://raw.githubusercontent.com/tomasr/molokai/master/colors/molokai.vim
```
* Run Vim command `:PlugInstall` to install all plugins
