# my dotfiles

## dotfiles

This repo is a mix of different repos I forked and cloned modified to my needs. It contains:

- [oh-my-zsh](http://github.com/robbyrussell/oh-my-zsh) by [Robby Russell](http://github.com/robbyrussell)
- [vimfiles](http://github.com/scrooloose/vimfiles) by [Martin Grenfell](http://github.com/scrooloose)
- And a set of scripts/functions that I usually use
- To be added: [todo.txt-cli](https://github.com/ginatrapani/todo.txt-cli)

## install

Clone the repo: `git clone https://github.com/miconof/dotfiles.git ~/repos/dotfiles`

Grab the submodules: `cd ~/repos/dotfiles && git submodule init && git submodule update`

At the moment it is recomended to use the installation steps described in `oh-my-zsh` and `vimfiles`.
I plan to add some sort of automatic installation in the parent repository soon.

## bugs

I want this to work for everyone; that means when you clone it down it should
work. However, I do use this as *my* dotfiles, so there's a good chance I may break
something if I forget to make a check for any dependency.

If you run into any problems, please
[open an issue](https://github.com/miconof/dotfiles/issues) on this repository
and I'd love to get it fixed for you!
