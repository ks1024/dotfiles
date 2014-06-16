# Kuangshi's dotfiles

This is my dotfiles which was inspired by this [blog](http://mirnazim.org/writings/vim-plugins-i-use/) written by Mir Nazim.

# What it looks like

```
+-- ~/dotfiles
|	+-- bash
|	|	+-- bashrc
|	| 	+-- aliases
|	+-- vim
|	|	+-- autoload
|	|	+-- bundle
|	|	+--	vimrc
```
For Vim plugin manager, I've been using [Pathogen.vim](https://github.com/tpope/vim-pathogen) written by  [Tim Pope](https://github.com/tpope). You can find all vim plugins installed in bundle directory.

# Symbolic links

```
ln -s ~/dotfiles/vim ~/.vim
ln -s ~/dotfiles/vim/vimrc ~/.vimrc
ln -s ~/dotfiles/bash/bashrc ~/.bashrc
ln -s ~/dotfiles/bash/aliases ~/.bash_aliases
````

