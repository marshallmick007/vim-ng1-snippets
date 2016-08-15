# vim-ng1-snippets

VIM port of John Papa's [Angular 1 VSCode Snippets for
Javascript](https://github.com/johnpapa/vscode-angular1-snippets)

## Installation

These snippets work with
[vim-snippets](https://github.com/honza/vim-snippets) or other
[compatible](https://github.com/honza/vim-snippets#snippet-engines-supporting-vim-snippets) plugins.

##[vundle](https://github.com/gmarik/vundle)

    Plugin 'marshallmick007/vim-ng1-snippets'

to `.vimrc`, and then run `:PluginInstall`.

##[pathogen.vim](https://github.com/tpope/vim-pathogen)

    cd ~/.vim/bundle
    git clone https://github.com/marshallmick007/vim-ng1-snippets.git
    # Or, via git submodules
    git submodule add
https://github.com/marshallmick007/vim-ng1-snippets.git vim-ng1-snippets

## Snippets Provided

```shell
  ng1mod  # creates an angular module declaration
  ng1c    # creates an angular controller
  ng1s    # creates an angular service
  ng1comp # creates an angular component
  ng1d    # creates an angular directive
```
