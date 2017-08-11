# vim.rc


```
set nocompatible              " be iMproved, required
filetype off                  " required

set rtp+=~/.vim/bundle/Vundle.vim
call vundle#begin()

Plugin 'VundleVim/Vundle.vim'
Plugin 'scrooloose/nerdtree'
Plugin 'tpope/vim-markdown'
Plugin 'nanotech/jellybeans.vim' 

call vundle#end()            " required
filetype plugin indent on    " required

syntax on
set autoindent
set cindent
set nu
set ts=4
set shiftwidth=4
set laststatus=2
set statusline=\ %<%l:%v\ [%P]%=%a\ %h%m%r\ %F\
set hlsearch
set sw=1 " 스크롤바 너비
set history=256
set smartcase
set showmatch
set smartindent


colorscheme jellybeans

map <C-n> :NERDTreeToggle<CR>
```
