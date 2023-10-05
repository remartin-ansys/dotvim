# .dotvim

Configuration for vim installations

# Installation:

First get the repository in place

```bash
git clone git://github.com/remartin-ansys/dotvim.git ~/.vim
```

Then, create the symlinks:

```bash
ln -s ~/.vim/vimrc ~/.vimrc
ln -s ~/.vim/gvimrc ~/.gvimrc
```

Switch to the `~/.vim` directory, and fetch submodules:

```bash
cd ~/.vim
git submodule init
git submodule update
```

Proceed to open *.vimrv* using `vim` and then update the file as needed, when done run `:PluginInstall`

Check [Vundle.vim](https://github.com/VundleVim/Vundle.vim) for more information.

