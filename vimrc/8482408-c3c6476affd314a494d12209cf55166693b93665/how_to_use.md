This .vimrc is designed to work with MacVim, but works pretty well with vanilla Vim too.

It was inspired by [Janus](https://github.com/carlhuda/janus) and [YADR](https://github.com/skwp/dotfiles/blob/master/vimrc).
I decided to maintain my own .vimrc instead of using these great tools once I understood how YADR was using [Vundle](https://github.com/gmarik/vundle/wiki/Examples) it to manage customizations (and saw that it wasn't that complex).

When you add a Vundle to the .vimrc, you do:

    vim +BundleInstall +qall

You can debug where key mappings are coming from via:

    :verbose map [keycombo]
    OR
    :map [keycombo]