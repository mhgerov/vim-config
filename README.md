# vim-config
Vim files for various IDEs

## Vim Setup

Create `.vimrc` file and add these lines:
```vim
source vim-config/.vimrc
source vim-config/common.vim
```

Follow Vundle instructions for installation.

Windows gVim might have scaling issues. Try following the thread on [Reddit](https://www.reddit.com/r/vim/comments/fdr7bf/vim_is_too_small_on_windows/). Use `:set guifont=*` to interactively decide on font and size, then update the local *.vimrc*:

```vim
set guifont=Consolas:h12
```