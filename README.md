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

# List of Plugins used

 - [DelimitMate](https://github.com/Raimondi/delimitMate)
 - [Gruvbox](https://github.com/morhetz/gruvbox)
 - [Nerdcomment](https://github.com/preservim/nerdcommenter)
 - [Nerdtree](https://github.com/preservim/nerdtree)
 - [Simplyfold](https://github.com/tmhedberg/simpylfold)
 - [Sparkup](https://github.com/rstacruz/sparkup)
 - [Supertab](https://github.com/ervandew/supertab)
 - [Synstastic](https://github.com/vim-syntastic/syntastic)
 - [Vim Fugitive](https://github.com/tpope/vim-fugitive)
 - [Vim Git](https://github.com/tpope/vim-git)
 - [Vim Monokai Tasty](https://github.com/patstockwell/vim-monokai-tasty)
 - [Vim Monokai](https://github.com/ku1ik/vim-monokai)
 - [Vim-addon-mw-utils](https://github.com/MarcWeber/vim-addon-mw-utils)
 - [Vim-autoformat](https://github.com/vim-autoformat/vim-autoformat)
 - [Vim-colorschemes](https://github.com/flazz/vim-colorschemes)
 - [Vim-snippets](https://github.com/honza/vim-snippets)
