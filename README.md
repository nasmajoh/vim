# vim

Installation:

    git clone git://github.com/nasmajoh/vim.git ~/.vim

Create symlinks:

    ln -s ~/.vim/vimrc ~/.vimrc
    ln -s ~/.vim/gvimrc ~/.gvimrc

Switch to the `~/.vim` directory, and fetch submodules:

    cd ~/.vim
    git submodule init
    git submodule update
    
Add new plugins:

    git submodule add https://github.com/xxxx ~/.vim/bundle/xxx
   
