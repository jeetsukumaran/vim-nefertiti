# Nefertiti


<a href="http://jeetblogs.org/media/images/vim-nefertiti_1.png" target="_blank"><img src="http://jeetblogs.org/media/images/vim-nefertiti_1.png" width=350 /></a>

A warm dark-background color scheme for Vim (previously known as "MochaLatte"),
featuring dynamic control of brightness-levels as needed.

Brighten select (normal and syntax) colors with "`:NefertitiBrighten`", or
darken them with "`:NefertitiDarken`". Conveniently bound to "`META-2`" and
"`META-1`", respectively, but you can, of course, suppress the key mappings
and/or replace them with others of your own preference.

**NOTE**: GUI Vim only at the present time.

## Installation

### [Pathogen](https://github.com/tpope/vim-pathogen)

    $ cd ~/.vim/bundle
    $ git clone git://github.com/jeetsukumaran/vim-nefertiti

### [Vundle](https://github.com/VundleVim/Vundle.vim)

    :BundleInstall jeetsukumaran/vim-nefertiti

### Manually

Copy the file "`colors/nefertiti.vim`" to your "`~.vim/colors/`"
subdirectory.

### Updating from "MochaLatte"

This color scheme was previously known as "MochaLatte", as was the repository. If you cloned this repository from its "MochaLatte" days, everything should still work fine, though you will probably need to update your "~/.vimrc" to set the color scheme correctly.

If you installed this color scheme as a Git submodule, you might want to update by:

    $ cd ~/.vim/bundle
    $ git submodule deinit vim-mochalatte
    $ git submodule add git://github.com/jeetsukumaran/vim-nefertiti vim-nefertiti
    $ git commit -a -m "Updated MochaLatte to Nefertiti"

## Usage

As with any other color scheme, simply use the "`:colorscheme`" command, e.g.:

    :colors nefertiti

To set the color scheme permanently, add the following to your "`~/.vimrc`":

    if has("gui")
        colorscheme nefertiti
    endif

Three commands are provided to control the brightness levels: "`:NefertitiBrighten`", "`:NefertitiDarken`", and "`NefertitiReset`"; see [the help](https://github.com/jeetsukumaran/vim-nefertiti/blob/master/doc/nefertiti.vim) for more details.

By default, "`META-2`" ("`ALT-2`" on some keyboards) increases the brightness of the text while "`META-1`" ("`ALT-1`" on some keyboards) decreases the brightness of text. These key-mappings can be suppressed and or customized: see [the help](https://github.com/jeetsukumaran/vim-nefertiti/blob/master/doc/nefertiti.vim) for more details.

Note that for the default (or any other "`META`" or "`ALT`") key mappings to
work, if you are using [MacVim](https://github.com/macvim-dev/macvim), you will
also need something like the following in your "`~/.vimrc`":

    if has("gui_macvim")
        set macmeta
    endif

## Samples

<a href="http://jeetblogs.org/media/images/vim-nefertiti_1.png" target="_blank"><img src="http://jeetblogs.org/media/images/vim-nefertiti_1.png" width=200 /></a>
<a href="http://jeetblogs.org/media/images/vim-nefertiti_2.png" target="_blank"><img src="http://jeetblogs.org/media/images/vim-nefertiti_2.png" width=200 /></a>
<a href="http://jeetblogs.org/media/images/vim-nefertiti_3.png" target="_blank"><img src="http://jeetblogs.org/media/images/vim-nefertiti_3.png" width=200 /></a>
<a href="http://jeetblogs.org/media/images/vim-nefertiti_4.png" target="_blank"><img src="http://jeetblogs.org/media/images/vim-nefertiti_4.png" width=200 /></a>
<a href="http://jeetblogs.org/media/images/vim-nefertiti_5.png" target="_blank"><img src="http://jeetblogs.org/media/images/vim-nefertiti_5.png" width=200 /></a>
<a href="http://jeetblogs.org/media/images/vim-nefertiti_6.png" target="_blank"><img src="http://jeetblogs.org/media/images/vim-nefertiti_6.png" width=200 /></a>
