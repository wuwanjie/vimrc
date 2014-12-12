vimrc
=====
Hello guys
Welcome to my hub.
This is my Vim script file.
You can git clone it, then do following steps, you will have pretty sense when you work.

Step 1 :
You need to git clone Vundle plugin, it is very flexible tools for vim plugins.
git clone https://github.com/gmarik/Vundle.vim.git ~/.vim/bundle/Vundle.vim

Setp 2 :
Then you can mv .vimrc file to your home path. Next just do the following
commond .
vim +BundleInstall +qall

Step 3 :
I use the famous colorscheme solarized. If you want pretty experience, you 
also need edit your .bashrc.
export TERM=xterm-256color

Step 4 :
If you vim version is below 7.0, you just need to disenable neocomplecache plugin,
and you can add Youcompleteme instead.

My  first vim script file. This file makes vim works like IDE, when you are php programmer, it is pretty good.
