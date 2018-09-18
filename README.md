# Vim C/C++ ide

Want to use Vim for C++? The steps below are what you are looking for.

Copy .vimrc and .ycm_extra_conf.py file to your home directory.

Install Vundle (https://github.com/VundleVim/Vundle.vim)

Load vim and run `:PluginInstall`.

Follow the installation steps for YouCompleteMe (https://github.com/Valloric/YouCompleteMe#installation). You need `--clang-completer` support so run ycm installer with that option.

Read up on

* CtrlP https://github.com/kien/ctrlp.vim
* NerdTree https://github.com/scrooloose/nerdtree
* NerdCommenter https://github.com/scrooloose/nerdcommenter
* EasyMotion https://github.com/easymotion/vim-easymotion
* YouCompleteMe https://github.com/Valloric/YouCompleteMe
* Fugitive https://github.com/tpope/vim-fugitive

Jump between files using Ctrl-P or NerdTree.

Auto complete with Ycm is amazing.

Use nerd commenter to help with commenting/uncommenting blocks.

All git related work can be done using Fugitive.
