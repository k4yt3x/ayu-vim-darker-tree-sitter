# Ayu Vim Darker

This repository is a fork of [ayu-vim](https://github.com/ayu-theme/ayu-vim), with an extra `darker` theme.

![comparison](https://user-images.githubusercontent.com/21986859/136876927-4ca06322-965e-433a-b989-fdde5f09e304.png)

Below are the themes that are directly from the original version.

![ayu-vim](http://i.imgur.com/7vnF4Na.png)

## Warning

`ayu` is still in development and a lot of things need to be covered. Theme works only if VIM supports `termguicolors` option. This is true for [Neovim](https://neovim.io) and VIM from 7.4.1799.

## Installation

```VimL
Plug 'k4yt3x/ayu-vim-darker-tree-sitter' " or other package manager
"...
set termguicolors     " enable true colors support
let ayucolor="light"  " for light version of theme
let ayucolor="mirage" " for mirage version of theme
let ayucolor="dark"   " for dark version of theme
let ayucolor="darker" " for darker version of theme
colorscheme ayu
```

## Term colors

For now In `/term` you can find color schemes for iTerm. More to come.

## Indent line

To get indent line like in the screenshot install [indentLine](https://github.com/Yggdroot/indentLine) with my version of `Roboto Mono for Powerline` from this repo and add this config.

In this Roboto Mono version added powerline glyphs and increased line-height of the font itself.

```VimL
" IndentLine {{
let g:indentLine_char = ''
let g:indentLine_first_char = ''
let g:indentLine_showFirstIndentLevel = 1
let g:indentLine_setColors = 0
" }}
```
