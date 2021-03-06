# kotlin-vim

## Installation

### [Vundle](https://github.com/gmarik/Vundle.vim)

Add `Plugin 'udalov/kotlin-vim'` to your `~/.vimrc` and run `PluginInstall`.

### [Pathogen](https://github.com/tpope/vim-pathogen)

    $ git clone https://github.com/udalov/kotlin-vim ~/.vim/bundle/kotlin-vim

### [vim-plug](https://github.com/junegunn/vim-plug)

Add `Plug 'udalov/kotlin-vim'` to your `~/.vimrc` and run `PluginInstall`.

### Manual

0. `mkdir -p ~/.vim/{syntax,indent,ftdetect,ftplugin}`
1. `cp syntax/kotlin.vim ~/.vim/syntax/kotlin.vim`
2. `cp indent/kotlin.vim ~/.vim/indent/kotlin.vim`
3. `cp ftdetect/kotlin.vim ~/.vim/ftdetect/kotlin.vim`
4. `cp ftplugin/kotlin.vim ~/.vim/ftplugin/kotlin.vim`
5. If you use [Syntastic](https://github.com/scrooloose/syntastic): `cp -r syntax_checkers/kotlin ~/.vim/syntax_checkers/`
6. Restart Vim

### Settings

* `g:kotlin_collections` - add standard Kotlin collections to the `Type` group (List, Map, Set etc.), default is 0 (off), set to 1 to enable
* `g:kotlin_more_operators` - add much more symbols to the `Operator` group ([{(=:,.)}] etc.), default is 0 (off), set to 1 to enable

##### Enjoy!
