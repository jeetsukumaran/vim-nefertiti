# MochaLatte

<a href="http://jeetworks.org/wp-content/uploads/vim-mochalatte_1.png" target="_blank"><img src="http://jeetworks.org/wp-content/uploads/vim-mochalatte_1.png" width=350 /></a>

A warm dark-background color scheme for Vim, featuring dynamic control of
brightness-levels as needed.

Brighten select (normal and syntax) colors with "`:MochalatteBrighten`", or
darken them with "`:MochalatteDarken`". Conveniently bound to "`META-2`" and
"`META-1`", respectively, but you can, of course, suppress the key mappings
and/or replace them with others of your own preference.

**NOTE**: GUI Vim only at the present time.

## Installation

### [pathogen.vim](https://github.com/tpope/vim-pathogen)

    $ cd ~/.vim/bundle
    $ git clone git://github.com/jeetsukumaran/vim-mochalatte

### [Vundle](https://github.com/gmarik/vundle.git)

    :BundleInstall jeetsukumaran/vim-mochalatte

### Manually

Copy the file "`colors/mochalatte.vim`" to your "`~.vim/colors/`"
subdirectory.

## Usage

As with any other color scheme, simply use the "`:colorscheme`" command, e.g.:

    :colors mochalatte

To set the color scheme permanently, add the following to your "`~/.vimrc`":

    if has("gui")
        colorscheme mochalatte
    endif

Three commands are provided to control the brightness levels: "`:MochalatteBrighten`", "`:MochalatteDarken`", and "`MochalatteReset`"; see [the help](https://github.com/jeetsukumaran/vim-mochalatte/blob/master/doc/mochalatte.txt) for more details.

By default, "`META-2`" ("`ALT-2`" on some keyboards) increases the brightness of the text while "`META-1`" ("`ALT-1`" on some keyboards) decreases the brightness of text. These key-mappings can be suppressed and or customized: see [the help](https://github.com/jeetsukumaran/vim-mochalatte/blob/master/doc/mochalatte.txt) for more details.

Note that for the default (or any other "`META`" or "`ALT`") key mappings to
work, if you are using [MacVim](https://code.google.com/p/macvim/), you will
also need something like the following in your "`~/.vimrc`":

    if has("gui_macvim")
        set macmeta
    endif

## Samples

<a href="http://jeetworks.org/wp-content/uploads/vim-mochalatte_1.png" target="_blank"><img src="http://jeetworks.org/wp-content/uploads/vim-mochalatte_1.png" width=200 /></a>
<a href="http://jeetworks.org/wp-content/uploads/vim-mochalatte_2.png" target="_blank"><img src="http://jeetworks.org/wp-content/uploads/vim-mochalatte_2.png" width=200 /></a>
<a href="http://jeetworks.org/wp-content/uploads/vim-mochalatte_3.png" target="_blank"><img src="http://jeetworks.org/wp-content/uploads/vim-mochalatte_3.png" width=200 /></a>
<a href="http://jeetworks.org/wp-content/uploads/vim-mochalatte_4.png" target="_blank"><img src="http://jeetworks.org/wp-content/uploads/vim-mochalatte_4.png" width=200 /></a>
<a href="http://jeetworks.org/wp-content/uploads/vim-mochalatte_5.png" target="_blank"><img src="http://jeetworks.org/wp-content/uploads/vim-mochalatte_5.png" width=200 /></a>
<a href="http://jeetworks.org/wp-content/uploads/vim-mochalatte_6.png" target="_blank"><img src="http://jeetworks.org/wp-content/uploads/vim-mochalatte_6.png" width=200 /></a>
