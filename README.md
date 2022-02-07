# ddu-ui-ff

Fuzzy finder UI for ddu.vim

This UI is standard fuzzy finder.

## Required

### denops.vim

https://github.com/vim-denops/denops.vim

### ddu.vim

https://github.com/Shougo/ddu.vim

## Configuration

```vim
" Use ff ui.
call ddu#custom#patch_global({
    \ 'ui': 'ff',
    \ })
```
