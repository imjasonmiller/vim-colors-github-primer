# vim-colors-github-primer

A Vim colorscheme that is based on [`vim-colors-github`](https://github.com/cormacrelf/vim-colors-github) and GitHub's design system, Primer.

This theme differs from `vim-colors-github` in its dark mode being based on GitHub's Primer.

It supports the following plugins:

* [`airline`](https://github.com/vim-airline/vim-airline)
* [`lightline`](https://github.com/itchyny/lightline.vim)
* [`fzf`](https://github.com/junegunn/fzf.vim)
* [`gitgutter`](https://github.com/airblade/vim-gitgutter)

## Install

Using [`vim-plug`](https://github.com/junegunn/vim-plug):

```viml
Plug 'imjasonmiller/vim-colors-github-primer'
```

Set your color scheme to `github_primer`:

```viml
colorscheme github_primer
```

In addition, if you use `airline` or `lightline`:

```viml
let g:airline_theme = "github_primer"
```
```viml
let g:lightline = { 'colorscheme': 'github_primer' }
```

## License

Distributed under the same terms as Vim itself. See `:help license`.
