# My ZSH, TMUX, NVIM configs that I used to code
==========
Following contains my list of plugins that I used to mainly code Javascript and
Go. 
First install tmux, zsh, nvim for your Linux or Mac (Havent install on windows
but the configs should be the same).

## Steps to follow
Copy the config files to your home page and create a symlink for .nvimrc

```
ln -s .vimrc .nvimrc
```

Check you have exported the python path to the env variables.
I have been using Vundle to install plugins in my Vim. So install it from
following link
[Install Vundle](https://github.com/VundleVim/Vundle.vim)

The set of plugins that I use are as follows. You can see it in the .vimrc file

```
Plugin 'wincent/command-t'
Plugin 'davidhalter/jedi-vim'
Plugin 'bling/vim-bufferline'
Plugin 'ap/vim-css-color'
Plugin 'shougo/neocomplete.vim'
"Plugin 'tpope/vim-surround'

Plugin 'VundleVim/Vundle.vim'
Plugin 'fugitive.vim'
" Bundle 'powerline/powerline', {'rtp': 'powerline/bindings/vim/'}
" Bundle 'vim-scripts/ZoomWin'
Bundle 'airblade/vim-gitgutter'
" Bundle 'ctrlp/ctrlp.vim'
Plugin 'kien/ctrlp.vim'
Bundle 'easymotion/vim-easymotion'
Bundle 'edkolev/tmuxline.vim'
Bundle 'ervandew/supertab'
Bundle 'godlygeek/tabular'
Plugin 'Raimondi/delimitMate'
Plugin 'SirVer/ultisnips'
Plugin 'Valloric/YouCompleteMe'
Plugin 'fatih/vim-go'
"Plugin 'valloric/youcompleteme'
"Plugin 'davidhalter/jedi-vim'
Plugin 'Xuyuanp/nerdtree-git-plugin'
Plugin 'christoomey/vim-tmux-navigator'
Plugin 'honza/vim-snippets'
Plugin 'jistr/vim-nerdtree-tabs'
Plugin 'mileszs/ack.vim'
Plugin 'moll/vim-node'
Plugin 'nelstrom/vim-visual-star-search'
Plugin 'othree/javascript-libraries-syntax.vim'
Plugin 'pangloss/vim-javascript'
Plugin 'scrooloose/nerdtree'
Plugin 'scrooloose/syntastic'
Plugin 'sheerun/vim-polyglot'
Plugin 'stefandtw/quickfix-reflector.vim'
Plugin 'terryma/vim-expand-region'
Plugin 'terryma/vim-multiple-cursors'
Plugin 'tomtom/tcomment_vim'
Plugin 'tpope/vim-repeat'
Plugin 'tpope/vim-surround'
Plugin 'tpope/vim-unimpaired'
Plugin 'vim-airline/vim-airline'
Plugin 'vim-airline/vim-airline-themes'
Plugin 'vim-scripts/vis'
Plugin 'scrooloose/nerdcommenter'

" Plugin 'xolox/vim-easytags'
Plugin 'majutsushi/tagbar'

"Plugin 'xolox/vim-misc'
Bundle 'geekjuice/vim-mocha'
Plugin 'janko-m/vim-test'
Plugin 'docunext/closetag.vim'
Plugin 'moll/vim-bbye'
" Plugin 'alvan/vim-closetag'
" Plugin 'altercation/vim-colors-solarized'
" Plugin 'ayu-theme/ayu-vim' " or other package manager
Plugin 'crusoexia/vim-monokai'
```

Some I have commented out either not working or deprecated. I have been yet
keeping them in case I try to install it again.

For neovim do the following task too.

Create a symlink in the .config folder for the vim

```
ln -s ~/.vim ~/.config/nvim
ln -s ~/.vimrc ~/.config/nvim/init.vim
```

Thats it. Enjoy coding!


