# image.vim
View images in Vim, because Vim is awesome!

![](https://github.com/ashisha/image.vim/blob/master/screenshot/image.vim.jpg)



Features
=========
* Let's you open (preview) images in Vim!
* It's safe, never modifies the original image (unless you force write)


Requirements
============
* Vim with *python* support. You can verify if your Vim is compiled with python using:
  
  `vim --version | grep python`

  If you see `+python`, your Vim has python support. If not, figure out how to get one.

* Also needs the Python library PIL. You can install PIL using `pip install Pillow`

Installation
============
* [Pathogen](https://github.com/tpope/vim-pathogen)
  *  `git clone https://github.com/itsvinayak/image.vim ~/.vim/bundle/image.vim`
* [plug](https://github.com/junegunn/vim-plug)
  *  `Plug 'itsvinayak/image.vim'`
* [Vundle](https://github.com/gmarik/vundle)
  * `Plugin 'itsvinayak/image.vim'`
* [NeoBundle](https://github.com/Shougo/neobundle.vim)
  * `NeoBundle 'itsvinayak/image.vim'`
* Manual
  * Copy image.vim into your `~/.vim/plugin/` directory

Thank you!
